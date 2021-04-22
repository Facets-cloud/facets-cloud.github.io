# dbs Schema

```txt
https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../out/application.schema.json "open original schema") |

## dbs Type

`object` ([dbs](application-properties-credentialrequests-properties-dbs.md))

# dbs Properties

| Property        | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                            |
| :-------------- | :------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [mysql](#mysql) | `array` | Required | cannot be null | [Application](application-properties-credentialrequests-properties-dbs-properties-mysql.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql") |
| [mongo](#mongo) | `array` | Required | cannot be null | [Application](application-properties-credentialrequests-properties-dbs-properties-mongo.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mongo") |

## mysql



`mysql`

*   is required

*   Type: an array where each item follows the corresponding schema in the following list:

    1.  [mysqlElement](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement.md "check type definition")

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-dbs-properties-mysql.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mysql")

### mysql Type

an array where each item follows the corresponding schema in the following list:

1.  [mysqlElement](application-properties-credentialrequests-properties-dbs-properties-mysql-items-mysqlelement.md "check type definition")

## mongo



`mongo`

*   is required

*   Type: an array where each item follows the corresponding schema in the following list:

    1.  [mongoElement](application-properties-credentialrequests-properties-dbs-properties-mongo-items-mongoelement.md "check type definition")

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-dbs-properties-mongo.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/dbs/properties/mongo")

### mongo Type

an array where each item follows the corresponding schema in the following list:

1.  [mongoElement](application-properties-credentialrequests-properties-dbs-properties-mongo-items-mongoelement.md "check type definition")
