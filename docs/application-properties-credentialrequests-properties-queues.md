# queues Schema

```txt
https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/queues
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../out/application.schema.json "open original schema") |

## queues Type

`object` ([queues](application-properties-credentialrequests-properties-queues.md))

# queues Properties

| Property              | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :-------------------- | :------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [rabbitmq](#rabbitmq) | `array` | Required | cannot be null | [Application](application-properties-credentialrequests-properties-queues-properties-rabbitmq.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/queues/properties/rabbitmq") |

## rabbitmq



`rabbitmq`

*   is required

*   Type: an array where each item follows the corresponding schema in the following list:

    1.  [rabbitmqElement](application-properties-credentialrequests-properties-queues-properties-rabbitmq-items-rabbitmqelement.md "check type definition")

*   cannot be null

*   defined in: [Application](application-properties-credentialrequests-properties-queues-properties-rabbitmq.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/credentialRequests/properties/queues/properties/rabbitmq")

### rabbitmq Type

an array where each item follows the corresponding schema in the following list:

1.  [rabbitmqElement](application-properties-credentialrequests-properties-queues-properties-rabbitmq-items-rabbitmqelement.md "check type definition")
