# Observability
There are typically three aspects to observability
* Metrics
* Logs
* Tracing

## Metrics
The deployments created through Facets ships with a built-in [Grafana](https://grafana.com/) and [Prometheus](https://prometheus.io/) set up with pre-integrations to standard components and relevant dashboards.
The Grafana dashboard can be accessed through the control plane or with cluster specific URLs by the develops, devops or NOC staff.

![Grafana Dashboard](../media/grafana.png)

The metrics collected by Prometheus are usually of the following types
* Infrastructure Metrics (Pre-built metric exporters and integrations)
* Application Metrics ([Open telemetry](https://opentelemetry.io/))

### Infrastructure Metrics
Any components instantiated through Facets comes with the pre-built metrics dashboard without any additional work. The following
shows a pre-built redis dashboard. 
![Redis Dashboard](../media/redis.png)



### Application Metrics




## Logs



## Security Information and Event Management (SIEM)




## Traces



## Alerts

  





  


