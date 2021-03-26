# Roadmap

**AMJ 2021**

Epic | Roadmap | Jobs To Be Done (JTBD) |
-------|-------------------| ----------
`Extensibility` | Custom Terraform Modules (GA)| Devops teams can write custom TF modules and add to Facets|
`Extensibility` | Plugin Model (GA)| Devops Teams can write a complete facet module and deploy|
`Unified Observability` | Real Time Log Alerts| Developers will receive commonly found log based alerts and custom rules|
`Infosec Enablement` | Unified Compliance Dashboard|Infosec teams can monitor/pull information specific to the compliance needs from a single dashboard|
`Developer Productivity` | [`Facets.local`](../deploy/local.md) distribution mechanism|Developers will be able to deploy [`Facets.local`](../deploy/local.md) of their [FSDL](../fsdl/README.md) stack locally with a single click|
`Unified Observability` | Application Custom Metrics|Developers can define metric scraping in an easy to define FSDL|
`Deployment Strategies` | Canary Deployment | DevOps can choose [Canary deployment](https://semaphoreci.com/blog/what-is-canary-deployment) as a deployment strategy among others|
`Multi-Cloud`| Azure Support for Common Infra ([AKS](https://azure.microsoft.com/en-in/services/kubernetes-service/) + [Blob](https://azure.microsoft.com/en-in/services/storage/blobs/)| Developers can deploy a stack on Azure for cloud agnostic components|


**JAS 2021**

Epic | Roadmap | Jobs To Be Done (JTBD) |
-------|-------------------| ----------
`Multi-Cloud`| Object Storage Gateway|Developers can define / use cloud storage like S3 agnostic of the cloud/hybrid/on-prem|
`Customer Request`| MongoDB Atlas support| Developers can run heavy mongo instances on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) |
`Business Continuity`| Disaster Recovery Drill| Define a backup region during a cluster launch and can perform DR|
`Deployment Strategies` | Blue-Green Deployment | DevOps can choose [Blue-Green deployment](https://www.redhat.com/en/topics/devops/what-is-blue-green-deployment) as a deployment strategy among others|
`Unified Observability` | Istio deployment| DevOps teams can use [Istio](https://istio.io/) as a service mesh|
`Customer Request` | Postgres Integration| Developers can use Postgres as a FSDL component with schema management|
`Multi-Cloud`| [Azure Database Service](https://azure.microsoft.com/en-in/services/mysql/) (MySQL), [Monitor](https://azure.microsoft.com/en-in/services/monitor/), [app gateway](https://docs.microsoft.com/en-us/azure/application-gateway/overview)| Developers can use cloud native solutions for these services on Azure|
`Multi-Cloud`| GCP Support for Common Infra ([GKE](https://cloud.google.com/kubernetes-engine) + [GCS](https://cloud.google.com/storage))| Developers can deploy a stack on GCP for cloud agnostic components|
`Unified Observability` | Anomaly Detection| Developers can get metric anomaly reports on interested/important metrics|

**OND 2021**

Epic | Roadmap | Jobs To Be Done (JTBD) |
-------|-------------------| ----------
`Research and Exploration`| Cloud Storage Abstractions| Developers can use Cloud Storage Abstractions like [ONTAP](https://www.netapp.com/data-management/ontap-data-management-software/) or opensource alternatives to simplify Stateful operations|
`Cost Facet`|Cost Leaderboard| Attribute Cloud cost to Teams and Modules and create leader boards for cost optimization focus identification|
`Multi-cloud`|GCP [CloudSQL](https://cloud.google.com/sql/docs/mysql), [Cloud Metrics](https://cloud.google.com/monitoring/api/metrics_gcp), [BigTable](https://cloud.google.com/bigtable)| Developers can use cloud native solutions for these services on GCP|
`Core`|Continuous Verification System (GA)| Continuously verify the production infrastructure against FSDL stack|
`Unified Observability` | [Index Free Logging](https://thenewstack.io/yes-index-free-log-management-works/) Options| Developers can choose an Index free logging option like Loki|
`Core`|Post Deployment Hooks for QA (GA)|QA teams can control deployment progress in a CD pipeline|
`Unified Observability` | Cross Deployment Observability| Developers and Devops can compare cross deployment metrics (standard and custom)|

**JFM 2022**

Epic | Roadmap | Jobs To Be Done (JTBD) |
-------|-------------------| ----------
`Multi-cloud`| Native Support for Mixed Cloud| Deveops teams can deploy mixed cloud strategy like Azure + S3|
`On-prem / Hybrid`| [AWS Outpost](https://aws.amazon.com/outposts/)| Devops teams can manifest a FSDL stack on AWS outposts|
`On-prem / Hybrid`| [Openstack](https://www.openstack.org/) Support| Devops teams can manifest a FSDL stack on openstack|
`Infosec Enablement` | Unified Inventory View| Infosec teams can pull inventory of all cloud resources at one place|
`Core`| Application and Resource View| Developers can get details view and history of each resource| 
`Extensibility` | Central Control Plane Events store| Devops teams can hook in to Facets CP events and build custom workflows| 
`Features` | Data platforms support| Developers can deploy big data pipelines over languages like [Apache Spark](http://spark.apache.org/)| 
`Customer Requests`| GPU Support| Developers can use GPUs for suitable workloads like ML/Video processing|
