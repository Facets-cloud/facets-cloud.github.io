# mysqlElement Schema

```txt
https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../../../assets/out/application.schema.json "open original schema") |

## 0 Type

`object` ([mysqlElement](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement.md))

# 0 Properties

| Property                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                           |
| :-------------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [resourceType](#resourcetype)                 | `string` | Required | cannot be null | [Application](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-resourcetype.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/resourceType")                 |
| [resourceName](#resourcename)                 | `string` | Required | cannot be null | [Application](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-resourcename.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/resourceName")                 |
| [permission](#permission)                     | `string` | Required | cannot be null | [Application](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-permission.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/permission")                     |
| [environmentVariables](#environmentvariables) | `array`  | Required | cannot be null | [Application](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-environmentvariables.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/environmentVariables") |

## resourceType



`resourceType`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-resourcetype.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/resourceType")

### resourceType Type

`string`

## resourceName



`resourceName`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-resourcename.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/resourceName")

### resourceName Type

`string`

## permission



`permission`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-permission.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/permission")

### permission Type

`string`

## environmentVariables



`environmentVariables`

*   is required

*   Type: an array where each item follows the corresponding schema in the following list:

    1.  [environmentVariableElement](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-environmentvariables-items-environmentvariableelement.md "check type definition")

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-environmentvariables.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql/items/0/properties/environmentVariables")

### environmentVariables Type

an array where each item follows the corresponding schema in the following list:

1.  [environmentVariableElement](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement-properties-environmentvariables-items-environmentvariableelement.md "check type definition")
