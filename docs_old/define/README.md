# **Define Your Product**

## **Before you start** ##
* [Prerequisites - Onboarding Applications to facets](../getting_started/prerequisites.md)

## **How a Stack is organized**

**Stack** is a **git repository**. The top level folders of the repository denote application, infrastructure components,
database schemas and a few miscellaneous categories. Typically, a file specified in [FSDL](./README.md) can be placed inside `/instances` directory of these top level folders for 
instantiating an object of that type.

| Folder Category | Top Folder Name | Description |
| --- | --- | --- |
| Application | `application` | Application/ Container Specifications |
| Application | `statefulsets` | Any statefulsets applications that are not databases |
| Application | `jobs` | Applications that need to be invoked once during the launch. (Eg. One time migrations or bootstrap scripts) |
| Application | `cronjob` | Any scheduled jobs |
| Application | `daemonsets` | Applications that hold state and might need volumes |
| Cloud Agnostic Components | `kafka` | Kafka inside K8s |
| Cloud Agnostic Components | `mongo` | Mongo inside k8s |
| Cloud Agnostic Components | `openfire` | openfire inside k8s |
| Cloud Agnostic Components | `elasticsearch` | Elasticsearch inside k8s |
| Cloud Agnostic Components | `neo4j` | neo4j inside k8s |
| Cloud Agnostic Components | `postfix` | postfix inside k8s |
| Cloud Agnostic Components | `rabbitmq` | rabbitmq inside k8s |
| Cloud Agnostic Components | `solr` | solr inside k8s |
| Cloud Agnostic Components | `zookeeper` | Zookeeper inside k8s |
| Ingress | `ingress` | Ingress instances that are used to expose the application to public |
| Ingress | `ingress_rules_infra` | Ingress rules for internal applications required to be securely expored to company staff |
| Cloud Specific | `redis` | AWS/Elasticache |
| Cloud Specific | `aurora` | AWS/Aurora |
| Cloud Specific | `cloudfront` | AWS/Cloudfront |
| Cloud Specific | `documentdb` | AWS/DocumentDB |
| Cloud Specific | `dynamodb` | AWS/DynamoDB |
| Cloud Specific | `kinesis` | AWS/kinesis |
| Cloud Specific | `s3` | AWS/S3 |
| Cloud Specific | `serverless` | AWS/Lambda |
| Cloud Specific | `sqs` | AWS/SQS |
| Cloud Specific | `additional_peering` | Any common VPC peering required for any cluster provisioned through this stack |
| Database Management | `schema` | Schema specifications for each MySQL/Aurora instances (Create statements)  |
| Database Management | `seed_data` | Seed Data (Common meta data) that needs to be shipped for each instance/Aurora |
| Database Management | `database_views` | Any database view for each instance in MySQL/Aurora |
| Misc | `cluster_migration` | One-time Data migration definitions for external database to facets managed database |
| Misc | `logparser` | RLA rules to alert based on logs |
| Misc | `qasuites` | Define your QASuites here, they can be called post deployments |
| Misc | `redisk8s` | Kubernetes hosted redis server |
| Misc | `stack.json` | Stack level variable declarations and metadata like substacks |

