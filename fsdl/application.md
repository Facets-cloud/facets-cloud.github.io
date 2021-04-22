# Application Schema

```txt
https://facets.cloud/assets/fsdl/application.schema.json
```

Facets Stack Definition for Applications

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                          |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json](../../out/application.schema.json "open original schema") |

## Application Type

`object` ([Application](application.md))

# Application Properties

| Property                                                  | Type      | Required | Nullable       | Defined by                                                                                                                                                            |
| :-------------------------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [size](#size)                                             | `string`  | Required | cannot be null | [Application](application-properties-size.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/size")                                             |
| [deploymentStrategy](#deploymentstrategy)                 | `string`  | Required | cannot be null | [Application](application-properties-deploymentstrategy.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/deploymentStrategy")                 |
| [lbType](#lbtype)                                         | `string`  | Required | cannot be null | [Application](application-properties-lbtype.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/lbType")                                         |
| [elbIdleTimeoutSeconds](#elbidletimeoutseconds)           | `integer` | Required | cannot be null | [Application](application-properties-elbidletimeoutseconds.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/elbIdleTimeoutSeconds")           |
| [secretFileMounts](#secretfilemounts)                     | `array`   | Required | cannot be null | [Application](application-properties-secretfilemounts.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/secretFileMounts")                     |
| [protocolGroup](#protocolgroup)                           | `string`  | Required | cannot be null | [Application](application-properties-protocolgroup.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/protocolGroup")                           |
| [scaling](#scaling)                                       | `object`  | Required | cannot be null | [Application](application-properties-scaling.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/scaling")                                       |
| [liveness](#liveness)                                     | `object`  | Required | cannot be null | [Application](application-properties-liveness.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness")                                     |
| [readiness](#readiness)                                   | `object`  | Required | cannot be null | [Application](application-properties-readiness.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/readiness")                                   |
| [ports](#ports)                                           | `array`   | Required | cannot be null | [Application](application-properties-ports.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ports")                                           |
| [build](#build)                                           | `object`  | Required | cannot be null | [Application](application-properties-build.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/build")                                           |
| [credentialRequests](#credentialrequests)                 | `object`  | Required | cannot be null | [Application](application-properties-credentialrequests.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests")                 |
| [environmentVariables](#environmentvariables)             | `object`  | Required | cannot be null | [Application](application-properties-environmentvariables.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/environmentVariables")             |
| [k8s_service_names](#k8s_service_names)                   | `array`   | Required | cannot be null | [Application](application-properties-k8s_service_names.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/k8s_service_names")                   |
| [ingress_rules](#ingress_rules)                           | `array`   | Required | cannot be null | [Application](application-properties-ingress_rules.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules")                           |
| [resourceAllocationStrategy](#resourceallocationstrategy) | `string`  | Required | cannot be null | [Application](application-properties-resourceallocationstrategy.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/resourceAllocationStrategy") |

## size

Size as per sizing.json, determines number of VCPUs and Memory

`size`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-size.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/size")

### size Type

`string`

## deploymentStrategy

A deployment strategy determines the deployment process. E.g. Rolling Recreate

`deploymentStrategy`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-deploymentstrategy.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/deploymentStrategy")

### deploymentStrategy Type

`string`

### deploymentStrategy Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"RollingUpdate"` |             |
| `"ReCreate"`      |             |

## lbType

This setting determines kind of LB to be used

`lbType`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-lbtype.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/lbType")

### lbType Type

`string`

### lbType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"internal"` |             |

## elbIdleTimeoutSeconds

This setting allows you to specify the length of time that a connection should remain open while in an idle state.

`elbIdleTimeoutSeconds`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-elbidletimeoutseconds.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/elbIdleTimeoutSeconds")

### elbIdleTimeoutSeconds Type

`integer`

## secretFileMounts

Key Values to be injected as a secret.

`secretFileMounts`

*   is required

*   Type: `string[]`

*   cannot be null

*   defined in: [Application](application-properties-secretfilemounts.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/secretFileMounts")

### secretFileMounts Type

`string[]`

## protocolGroup

Used on the service to specify the protocol spoken by the backend (pod) behind a listener.

`protocolGroup`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-protocolgroup.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/protocolGroup")

### protocolGroup Type

`string`

### protocolGroup Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"http"` |             |
| `"tcp"`  |             |

## scaling

This Section allows you to configure autoscaling features of your application

`scaling`

*   is required

*   Type: `object` ([scaling](application-properties-scaling.md))

*   cannot be null

*   defined in: [Application](application-properties-scaling.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/scaling")

### scaling Type

`object` ([scaling](application-properties-scaling.md))

## liveness

This section is to decribe the liveness probe for an application. Liveness probes are used to know when to restart a container. For example, liveness probes could catch a deadlock, where an application is running, but unable to make progress. Restarting a container in such a state can help to make the application more available despite bugs.

`liveness`

*   is required

*   Type: `object` ([liveness](application-properties-liveness.md))

*   cannot be null

*   defined in: [Application](application-properties-liveness.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness")

### liveness Type

`object` ([liveness](application-properties-liveness.md))

## readiness

This section is to describe the readiness probe for an application. The kubelet uses readiness probes to know when a container is ready to start accepting traffic. A Pod is considered ready when all of its containers are ready. One use of this signal is to control which Pods are used as backends for Services. When a Pod is not ready, it is removed from Service load balancers.

`readiness`

*   is required

*   Type: `object` ([readiness](application-properties-readiness.md))

*   cannot be null

*   defined in: [Application](application-properties-readiness.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/readiness")

### readiness Type

`object` ([readiness](application-properties-readiness.md))

## ports

All the ports the application interacts on

`ports`

*   is required

*   Type: an array where each item follows the corresponding schema in the following list:

    1.  [items](application-properties-ports-items-items.md "check type definition")

*   cannot be null

*   defined in: [Application](application-properties-ports.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ports")

### ports Type

an array where each item follows the corresponding schema in the following list:

1.  [items](application-properties-ports-items-items.md "check type definition")

## build

This section describes how to fetch build for this application

`build`

*   is required

*   Type: `object` ([build](application-properties-build.md))

*   cannot be null

*   defined in: [Application](application-properties-build.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/build")

### build Type

`object` ([build](application-properties-build.md))

## credentialRequests

This section is to lineup all access request for this application to all databases and cloud resources

`credentialRequests`

*   is required

*   Type: `object` ([credentialRequests](application-properties-credentialrequests.md))

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests")

### credentialRequests Type

`object` ([credentialRequests](application-properties-credentialrequests.md))

## environmentVariables

This section is to define all the environment variables to be used in application runtime

`environmentVariables`

*   is required

*   Type: `object` ([environmentVariables](application-properties-environmentvariables.md))

*   cannot be null

*   defined in: [Application](application-properties-environmentvariables.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/environmentVariables")

### environmentVariables Type

`object` ([environmentVariables](application-properties-environmentvariables.md))

## k8s_service_names

The service name to be used in kubernetes with which application may be discovered, default is \<filename(without extension)>.default

`k8s_service_names`

*   is required

*   Type: an array where each item follows the corresponding schema in the following list:



*   cannot be null

*   defined in: [Application](application-properties-k8s_service_names.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/k8s_service_names")

### k8s_service_names Type

an array where each item follows the corresponding schema in the following list:



## ingress_rules

This section is to map applications with public facing lbs by specifying their path/ subdomain based router configurations

`ingress_rules`

*   is required

*   Type: an array where each item follows the corresponding schema in the following list:

    1.  [ingress_rule_Element](application-properties-ingress_rules-items-ingress_rule_element.md "check type definition")

*   cannot be null

*   defined in: [Application](application-properties-ingress_rules.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules")

### ingress_rules Type

an array where each item follows the corresponding schema in the following list:

1.  [ingress_rule_Element](application-properties-ingress_rules-items-ingress_rule_element.md "check type definition")

## resourceAllocationStrategy



`resourceAllocationStrategy`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-resourceallocationstrategy.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/resourceAllocationStrategy")

### resourceAllocationStrategy Type

`string`
