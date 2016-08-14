### Elasticsearch 2.3.5 cluster node 3 of 3

## Docker script : 
docker run -d -v {host_data_path_for cluster}:/usr/share/elasticsearch/data/ -p 9202:9202 -p 9302:9302 --name es2 cranelana/es-node2

## See cluster state at: 
http://localhost:9202/_plugin/head
