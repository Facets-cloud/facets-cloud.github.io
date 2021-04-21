# Untitled string in Application Schema

```txt
https://facets.cloud/application.schema.json#/properties/deploymentStrategy
```

A deployment strategy determines the deployment process. E.g. Rolling Recreate

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [application.schema.json*](../../../assets/out/application.schema.json "open original schema") |

## deploymentStrategy Type

`string`

## deploymentStrategy Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"RollingUpdate"` |             |
| `"ReCreate"`      |             |
