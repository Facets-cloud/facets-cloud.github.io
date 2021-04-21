# readiness Schema

```txt
https://facets.cloud/application.schema.json#/properties/readiness
```

This section is to describe the readiness probe for an application. The kubelet uses readiness probes to know when a container is ready to start accepting traffic. A Pod is considered ready when all of its containers are ready. One use of this signal is to control which Pods are used as backends for Services. When a Pod is not ready, it is removed from Service load balancers.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../../../assets/out/application.schema.json "open original schema") |

## readiness Type

`object` ([readiness](application-properties-readiness.md))

# readiness Properties

| Property                                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                        |
| :------------------------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [enableReadinessHTTP](#enablereadinesshttp)             | `boolean` | Optional | cannot be null | [Application](application-properties-readiness-properties-enablereadinesshttp.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/enableReadinessHTTP")             |
| [readinessHTTPEndpoint](#readinesshttpendpoint)         | `string`  | Optional | cannot be null | [Application](application-properties-readiness-properties-readinesshttpendpoint.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessHTTPEndpoint")         |
| [readinessInitialDelay](#readinessinitialdelay)         | `integer` | Required | cannot be null | [Application](application-properties-readiness-properties-readinessinitialdelay.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessInitialDelay")         |
| [readinessFailureThreshold](#readinessfailurethreshold) | `integer` | Required | cannot be null | [Application](application-properties-readiness-properties-readinessfailurethreshold.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessFailureThreshold") |
| [readinessSuccessThreshold](#readinesssuccessthreshold) | `integer` | Required | cannot be null | [Application](application-properties-readiness-properties-readinesssuccessthreshold.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessSuccessThreshold") |
| [readinessPort](#readinessport)                         | `integer` | Required | cannot be null | [Application](application-properties-readiness-properties-readinessport.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessPort")                         |
| [readinessTimeout](#readinesstimeout)                   | `integer` | Required | cannot be null | [Application](application-properties-readiness-properties-readinesstimeout.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessTimeout")                   |
| [readinessPeriod](#readinessperiod)                     | `integer` | Required | cannot be null | [Application](application-properties-readiness-properties-readinessperiod.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessPeriod")                     |

## enableReadinessHTTP



`enableReadinessHTTP`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Application](application-properties-readiness-properties-enablereadinesshttp.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/enableReadinessHTTP")

### enableReadinessHTTP Type

`boolean`

## readinessHTTPEndpoint



`readinessHTTPEndpoint`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-readiness-properties-readinesshttpendpoint.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessHTTPEndpoint")

### readinessHTTPEndpoint Type

`string`

## readinessInitialDelay



`readinessInitialDelay`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-readiness-properties-readinessinitialdelay.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessInitialDelay")

### readinessInitialDelay Type

`integer`

## readinessFailureThreshold



`readinessFailureThreshold`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-readiness-properties-readinessfailurethreshold.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessFailureThreshold")

### readinessFailureThreshold Type

`integer`

## readinessSuccessThreshold



`readinessSuccessThreshold`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-readiness-properties-readinesssuccessthreshold.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessSuccessThreshold")

### readinessSuccessThreshold Type

`integer`

## readinessPort



`readinessPort`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-readiness-properties-readinessport.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessPort")

### readinessPort Type

`integer`

## readinessTimeout



`readinessTimeout`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-readiness-properties-readinesstimeout.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessTimeout")

### readinessTimeout Type

`integer`

## readinessPeriod



`readinessPeriod`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-readiness-properties-readinessperiod.md "https://facets.cloud/application.schema.json#/properties/readiness/properties/readinessPeriod")

### readinessPeriod Type

`integer`
