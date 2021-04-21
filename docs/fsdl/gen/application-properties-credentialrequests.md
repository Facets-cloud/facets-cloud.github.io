# credentialRequests Schema

```txt
https://facets.cloud/application.schema.json#/properties/credentialRequests
```

This section is to lineup all access request for this application to all databases and cloud resources

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../../../assets/out/application.schema.json "open original schema") |

## credentialRequests Type

`object` ([credentialRequests](application-properties-credentialrequests.md))

# credentialRequests Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                                    |
| :---------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [dbs](#dbs)       | `object` | Required | cannot be null | [Application](application-properties-credentialrequests-properties-dbs.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs")       |
| [queues](#queues) | `object` | Required | cannot be null | [Application](application-properties-credentialrequests-properties-queues.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/queues") |
| [cloud](#cloud)   | `array`  | Required | cannot be null | [Application](application-properties-credentialrequests-properties-cloud.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/cloud")   |

## dbs



`dbs`

*   is required

*   Type: `object` ([dbs](application-properties-credentialrequests-properties-dbs.md))

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-dbs.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/dbs")

### dbs Type

`object` ([dbs](application-properties-credentialrequests-properties-dbs.md))

## queues



`queues`

*   is required

*   Type: `object` ([queues](application-properties-credentialrequests-properties-queues.md))

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-queues.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/queues")

### queues Type

`object` ([queues](application-properties-credentialrequests-properties-queues.md))

## cloud



`cloud`

*   is required

*   Type: an array where each item follows the corresponding schema in the following list:

    1.  [cloudElement](application-properties-credentialrequests-properties-cloud-items-cloudelement.md "check type definition")

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-cloud.md "https://facets.cloud/application.schema.json#/properties/credentialRequests/properties/cloud")

### cloud Type

an array where each item follows the corresponding schema in the following list:

1.  [cloudElement](application-properties-credentialrequests-properties-cloud-items-cloudelement.md "check type definition")
