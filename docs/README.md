# README

## Top-level Schemas

*   [Application](./application.md "Facets Stack Definition for Applications") – `https://facets.cloud/assets/fsdl/application.schema.json`

## Other Schemas

### Objects

*   [Service Endpoint](./application-properties-environmentvariables-properties-dynamic-properties-service-endpoint.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/environmentVariables/properties/dynamic/properties/SERVICE_ENDPOINT`

*   [build](./application-properties-build.md "This section describes how to fetch build for this application") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/build`

*   [cloudElement](./application-properties-credentialrequests-properties-cloud-items-cloudelement.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/cloud/items/0`

*   [credentialRequests](./application-properties-credentialrequests.md "This section is to lineup all access request for this application to all databases and cloud resources") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests`

*   [dbs](./application-properties-credentialrequests-properties-dbs.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs`

*   [dynamic](./application-properties-environmentvariables-properties-dynamic.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/environmentVariables/properties/dynamic`

*   [environmentVariableElement](./application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-environmentvariables-items-environmentvariableelement.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/environmentVariables/items/0`

*   [environmentVariableElement](./application-properties-credentialrequests-properties-dbs-properties-mongo-items-mongoelement-properties-environmentvariables-items-environmentvariableelement.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mongo/items/0/properties/environmentVariables/items/0`

*   [environmentVariableElement](./application-properties-credentialrequests-properties-queues-properties-rabbitmq-items-rabbitmqelement-properties-environmentvariables-items-environmentvariableelement.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/queues/properties/rabbitmq/items/0/properties/environmentVariables/items/0`

*   [environmentVariables](./application-properties-environmentvariables.md "This section is to define all the environment variables to be used in application runtime") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/environmentVariables`

*   [ingress_rule_Element](./application-properties-ingress_rules-items-ingress_rule_element.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0`

*   [items](./application-properties-ports-items-items.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/ports/items/0`

*   [liveness](./application-properties-liveness.md "This section is to decribe the liveness probe for an application") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness`

*   [mongoElement](./application-properties-credentialrequests-properties-dbs-properties-mongo-items-mongoelement.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mongo/items/0`

*   [mysqlElement](./application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0`

*   [queues](./application-properties-credentialrequests-properties-queues.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/queues`

*   [rabbitmqElement](./application-properties-credentialrequests-properties-queues-properties-rabbitmq-items-rabbitmqelement.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/queues/properties/rabbitmq/items/0`

*   [readiness](./application-properties-readiness.md "This section is to describe the readiness probe for an application") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/readiness`

*   [scaling](./application-properties-scaling.md "This Section allows you to configure autoscaling features of your application") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/scaling`

*   [static](./application-properties-environmentvariables-properties-static.md "Define all static environment variables for this application here as key value pairs") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/environmentVariables/properties/static`

### Arrays

*   [cloud](./application-properties-credentialrequests-properties-cloud.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/cloud`

*   [environmentVariables](./application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-environmentvariables.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/environmentVariables`

*   [environmentVariables](./application-properties-credentialrequests-properties-dbs-properties-mongo-items-mongoelement-properties-environmentvariables.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mongo/items/0/properties/environmentVariables`

*   [environmentVariables](./application-properties-credentialrequests-properties-queues-properties-rabbitmq-items-rabbitmqelement-properties-environmentvariables.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/queues/properties/rabbitmq/items/0/properties/environmentVariables`

*   [ingress_rules](./application-properties-ingress_rules.md "This section is to map applications with public facing lbs by specifying their path/ subdomain based router configurations") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules`

*   [k8s_service_names](./application-properties-k8s_service_names.md "The service name to be used in kubernetes with which application may be discovered, default is \<filename(without extension)>") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/k8s_service_names`

*   [mongo](./application-properties-credentialrequests-properties-dbs-properties-mongo.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mongo`

*   [mysql](./application-properties-credentialrequests-properties-dbs-properties-mysql.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql`

*   [ports](./application-properties-ports.md "All the ports the application interacts on") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/ports`

*   [rabbitmq](./application-properties-credentialrequests-properties-queues-properties-rabbitmq.md) – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/queues/properties/rabbitmq`

*   [secretFileMounts](./application-properties-secretfilemounts.md "Key Values to be injected as a secret") – `https://facets.cloud/assets/fsdl/application.schema.json#/properties/secretFileMounts`

## Version Note

The schemas linked above follow the JSON Schema Spec version: `https://json-schema.org/draft/2020-12/schema`
