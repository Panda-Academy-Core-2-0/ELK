# ELK
Elasticsearch, Logstash, Kibana with Filebeat example. To start run `docker-compose up -d` in root directory of the repository. This will setup ELK stack collecting docker logs through Filebeat.

Available services:

 * Elasticsearch: 192.168.44.44:9200
 * Kibana: 192.168.44.44:5601

 This repo is a slight modified copy of https://github.com/elkninja/elastic-stack-docker-part-one. To know more how it works checkout official Elastic blog article: https://www.elastic.co/blog/getting-started-with-the-elastic-stack-and-docker-compose
