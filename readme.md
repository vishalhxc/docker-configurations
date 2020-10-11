# Docker Configurations
This repository has some useful tech stack configurations for local development. In any folder, just `docker-compose up`.
 - **kafka-zookeeper**:  Creates Kafka/Zookeeper servers with a single topic to start
 - **pihole**:  DNS sinkhole to block unwanted advertising
 - **postgres-pgadmin**:  PostgreSQL database with PG Admin as a UI
 - **splunk**:  Splunk enterprise to aggregate different data sources
 - **telegraf-prometheus-grafana**:  Telegraf server in which to push metrics, stored in Prometheus format, scraped by a Prometheus server and visualized with Grafana
 - **telegraf-influxdb-chronograf-kapacitor**:  TICK stack setup, standing up a Telegraf server in which to push Statsd metrics (stored in an InfluxDB database), visualized with Chronograf and alerting with Kapacitor