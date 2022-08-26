# Elastic Search config files

## docker-compose.yml
***Only for development usecase***

This is basic docker configuration of single node elastic search api and kibana web UI. Both services works in different containers that are in a network called es-net. There are 2 exposed ports: <code>9200</code> to access the API and <code>5601</code> for kibana.
