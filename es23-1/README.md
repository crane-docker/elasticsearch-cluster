### Elasticsearch 2.3.5 cluster node 1 of 3

## Docker script :
docker run -d -v {host_data_path_for_cluster}:/usr/share/elasticsearch/data/ -p 9200:9200 -p 9300:9300 --name es0 cranelana/es-node0 

{host_data_path_for_cluster} is the full path of the cluster data on the host. Different nodes of the same cluster can share the same data path.

## See cluster state at:
http://localhost:9200/_plugin/head

## Attention 
If built with Dockerfile, make sure to download the folder 'config' to Dockerfile path.
