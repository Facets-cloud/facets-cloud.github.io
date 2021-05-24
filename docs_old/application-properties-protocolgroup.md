# Untitled string in Application Schema

```txt
https://facets.cloud/assets/fsdl/application.schema.json#/properties/protocolGroup
```

Used on the service to specify the protocol spoken by the backend (pod) behind a listener.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                        |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [application.schema.json*](../out/application.schema.json "open original schema") |

## protocolGroup Type

`string`

## protocolGroup Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"http"` |             |
| `"tcp"`  |             |
