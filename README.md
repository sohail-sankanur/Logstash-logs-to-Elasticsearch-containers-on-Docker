# Logstash-logs-to-Elasticsearch-containers-on-Docker
Logs sent to network of Elasticsearch containers using Logstash, Kibana used for analysis. This repo contains the docker yml configuration file which is used to make one elasticsearch master node and 2 elasticsearch data nodes. And Kibana is used for log analysis and visualisations. Logstash is used for sending the logs to the network of elasticsearch containers.

## Steps to perform:
* Run the command 'docker-compose up' to get the containers up and running.
* Then run the command 'location_to_logstash_folder/bin/logstash -f logstashConfig.conf'.
* then open the URL 'http://localhost:5601/' on a web browser for Kibana.
