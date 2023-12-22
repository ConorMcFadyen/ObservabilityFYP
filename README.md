# Observability Appliation Interim
 This Repo contains two folders reperesenting the software and configuration for both the RasPi4 and Router.

## RasPi4
The monitoring stack running on the RasPi

### Alertmanager
This contains the installation instructions, config file and rule group file

### Grafana
This contains the installation of grafana used
 - Dashboards: This subfolder contains the json representation of the dashboards used in the interim demo

### Prometheus
  This contains the Prometheus setup and configuration file

### RasPi
  This contains the OS used on the RasPi and the service files to enable the prometheus and alertmanager instance

## Router
Software running on the router

### Node_Exporter
This file outlines the instructions to get the node exporter packages

### OS
The RasPi 64 bit OS used on the RasPi. 

### prometheus-node-exporter-lua
This is the file located at /etc/config/prometheus-node-exporter-lua to expose metrics for Prometheus to scrape

