### Elasticsearch 2.3.5 cluster node 2 of 3

## Docker script : 
docker run -d -v {host_data_path_for cluster}:/usr/share/elasticsearch/data/ -p 9201:9201 -p 9301:9301 --name es1 crasa/es-node1 

{host_data_path_for_cluster} is the full path of the cluster data on the host. Different nodes of the same cluster can share the same data path.

## See cluster state at: 
http://localhost:9201/_plugin/head

## Attention 
If built with Dockerfile, make sure to download the folder 'config' to Dockerfile path.
