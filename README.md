Ansible Role: ElasticSearch
===========================

Downloads, Installs and configures ElasticSearch

Requirements
------------

None

Role Variables
--------------

```yaml

elasticsearch_discovery_zen_ping_unicast_hosts: []

elasticsearch_version: 1.7.1
elasticsearch_user: elasticsearch
elasticsearch_group: elasticsearch
elasticsearch_download_url: https://download.elastic.co/elasticsearch/elasticsearch

elasticsearch_http_port: 9200
elasticsearch_node2node_port: 9300

elasticsearch_node_master: 'true'
elasticsearch_node_data: 'true'

```

Dependencies
------------

- redouane.java

License
-------

BSD