# Architecture

This SIEM system consists of three machines:

- SIEM Server (Elasticsearch, Kibana, NGINX)
- IDS Server (Snort)
- Log Server (UFW + Filebeat)

Logs are collected, processed and visualized through the Elastic Stack.
