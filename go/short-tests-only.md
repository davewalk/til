### short tests only

the `-short` flag for `go test` allows you to run only a subset of your tests when used with `testing.Short()`:

```go
func TestSomethingThatTakesAWhile(t *testing.T) {
    if testing.Short() {
        t.Skip("skipping test that takes too long")
    }
    ...
}
```
