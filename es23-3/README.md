### Elasticsearch 2.3.5 cluster node 3 of 3

## Docker script : 
docker run -d -v {host_data_path_for cluster}:/usr/share/elasticsearch/data/ -p 9202:9202 -p 9302:9302 --name es2 crasa/es-node2 

{host_data_path_for_cluster} is the full path of the cluster data on the host. Different nodes of the same cluster can share the same data path.

## See cluster state at: 
http://localhost:9202/_plugin/head

## Attention 
If built with Dockerfile, make sure to download the folder 'config' to Dockerfile path.
