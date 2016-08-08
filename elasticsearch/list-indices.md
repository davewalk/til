### list indices

The [cat API](https://www.elastic.co/guide/en/elasticsearch/reference/current/cat-indices.html)
provides stats on Elasticsearch indices in a human-friendly format. 

`curl http://localhost:9200/_cat/indices`

```text
yellow open  logstash-2016.08.05 5 1 21267808       0    3gb    3gb 
yellow open  logstash-2016.08.06 5 1 50171237       0  6.8gb  6.8gb 
yellow open  health              5 1        0       0   575b   575b 
yellow open  logstash-2016.08.04 5 1 41160949       0  5.7gb  5.7gb 
yellow open  logstash-2016.08.08 5 1   191580       0 40.2mb 40.2mb 
       close logstash-2016.08.01                                    
yellow open  .kibana             1 1       31       4 80.2kb 80.2kb 
yellow open  logstash-2016.08.07 5 1 12574414       0  1.7gb  1.7gb
```
