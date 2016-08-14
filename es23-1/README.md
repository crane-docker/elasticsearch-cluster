### Elasticsearch 2.3.5 cluster node 1 of 3

## Docker script :
docker run -d -v {host_data_path_for cluster}:/usr/share/elasticsearch/data/ -p 9200:9200 -p 9300:9300 --name es0 cranelana/es-node0

## See cluster state at:
http://localhost:9200/_plugin/head
