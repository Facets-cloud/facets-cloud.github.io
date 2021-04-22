# liveness Schema

```txt
https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness
```

This section is to decribe the liveness probe for an application. Liveness probes are used to know when to restart a container. For example, liveness probes could catch a deadlock, where an application is running, but unable to make progress. Restarting a container in such a state can help to make the application more available despite bugs.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../out/application.schema.json "open original schema") |

## liveness Type

`object` ([liveness](application-properties-liveness.md))

# liveness Properties

| Property                                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                |
| :---------------------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [enableLivenessHTTP](#enablelivenesshttp)             | `boolean` | Optional | cannot be null | [Application](application-properties-liveness-properties-enablelivenesshttp.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/enableLivenessHTTP")             |
| [livenessHTTPEndpoint](#livenesshttpendpoint)         | `string`  | Optional | cannot be null | [Application](application-properties-liveness-properties-livenesshttpendpoint.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessHTTPEndpoint")         |
| [livenessPort](#livenessport)                         | `integer` | Required | cannot be null | [Application](application-properties-liveness-properties-livenessport.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessPort")                         |
| [livenessInitialDelay](#livenessinitialdelay)         | `integer` | Required | cannot be null | [Application](application-properties-liveness-properties-livenessinitialdelay.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessInitialDelay")         |
| [livenessTimeout](#livenesstimeout)                   | `integer` | Required | cannot be null | [Application](application-properties-liveness-properties-livenesstimeout.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessTimeout")                   |
| [livenessFailureThreshold](#livenessfailurethreshold) | `integer` | Required | cannot be null | [Application](application-properties-liveness-properties-livenessfailurethreshold.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessFailureThreshold") |
| [livenessPeriod](#livenessperiod)                     | `integer` | Required | cannot be null | [Application](application-properties-liveness-properties-livenessperiod.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessPeriod")                     |
| [livenessSuccessThreshold](#livenesssuccessthreshold) | `integer` | Required | cannot be null | [Application](application-properties-liveness-properties-livenesssuccessthreshold.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessSuccessThreshold") |

## enableLivenessHTTP



`enableLivenessHTTP`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Application](application-properties-liveness-properties-enablelivenesshttp.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/enableLivenessHTTP")

### enableLivenessHTTP Type

`boolean`

## livenessHTTPEndpoint



`livenessHTTPEndpoint`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-liveness-properties-livenesshttpendpoint.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessHTTPEndpoint")

### livenessHTTPEndpoint Type

`string`

## livenessPort



`livenessPort`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-liveness-properties-livenessport.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessPort")

### livenessPort Type

`integer`

## livenessInitialDelay



`livenessInitialDelay`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-liveness-properties-livenessinitialdelay.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessInitialDelay")

### livenessInitialDelay Type

`integer`

## livenessTimeout



`livenessTimeout`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-liveness-properties-livenesstimeout.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessTimeout")

### livenessTimeout Type

`integer`

## livenessFailureThreshold



`livenessFailureThreshold`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-liveness-properties-livenessfailurethreshold.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessFailureThreshold")

### livenessFailureThreshold Type

`integer`

## livenessPeriod



`livenessPeriod`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-liveness-properties-livenessperiod.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessPeriod")

### livenessPeriod Type

`integer`

## livenessSuccessThreshold



`livenessSuccessThreshold`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-liveness-properties-livenesssuccessthreshold.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/liveness/properties/livenessSuccessThreshold")

### livenessSuccessThreshold Type

`integer`
