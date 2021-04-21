# environmentVariables Schema

```txt
https://facets.cloud/application.schema.json#/properties/environmentVariables
```

This section is to define all the environment variables to be used in application runtime

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../../../assets/out/application.schema.json "open original schema") |

## environmentVariables Type

`object` ([environmentVariables](application-properties-environmentvariables.md))

# environmentVariables Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                          |
| :------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [static](#static)   | `object` | Required | cannot be null | [Application](application-properties-environmentvariables-properties-static.md "https://facets.cloud/application.schema.json#/properties/environmentVariables/properties/static")   |
| [dynamic](#dynamic) | `object` | Required | cannot be null | [Application](application-properties-environmentvariables-properties-dynamic.md "https://facets.cloud/application.schema.json#/properties/environmentVariables/properties/dynamic") |

## static

Define all static environment variables for this application here as key value pairs. These are typically tuning parameters for your applications that can be changed from environment to environment

`static`

*   is required

*   Type: `object` ([static](application-properties-environmentvariables-properties-static.md))

*   cannot be null

*   defined in: [Application](application-properties-environmentvariables-properties-static.md "https://facets.cloud/application.schema.json#/properties/environmentVariables/properties/static")

### static Type

`object` ([static](application-properties-environmentvariables-properties-static.md))

## dynamic



`dynamic`

*   is required

*   Type: `object` ([dynamic](application-properties-environmentvariables-properties-dynamic.md))

*   cannot be null

*   defined in: [Application](application-properties-environmentvariables-properties-dynamic.md "https://facets.cloud/application.schema.json#/properties/environmentVariables/properties/dynamic")

### dynamic Type

`object` ([dynamic](application-properties-environmentvariables-properties-dynamic.md))
