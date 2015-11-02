Ansible Role: ElasticSearch
===========================

Downloads, Installs and configures ElasticSearch

Requirements
------------

None

Role Variables
--------------

```yaml

elasticsearch_version: 2.0.0
elasticsearch_download_url: https://download.elasticsearch.org/elasticsearch/release/org/elasticsearch/distribution/deb/elasticsearch

elasticsearch_heap_size: 1g
elasticsearch_node_master: true
elasticsearch_node_data: true
elasticsearch_cluster_name: elasticsearch
elasticsearch_http_port: 9200
elasticsearch_transport_tcp_port: 9300
elasticsearch_network_host: _local_
elasticsearch_discovery_zen_ping_unicast_hosts:
- "127.0.0.1"
- "[::1]"

```

Dependencies
------------

- redouane.java

License
-------

BSD