# items Schema

```txt
https://facets.cloud/application.schema.json#/properties/ports/items/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../../../assets/out/application.schema.json "open original schema") |

## 0 Type

`object` ([items](application-properties-ports-items-items.md))

# 0 Properties

| Property                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                            |
| :------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [name](#name)                   | `string`  | Required | cannot be null | [Application](application-properties-ports-items-items-properties-name.md "https://facets.cloud/application.schema.json#/properties/ports/items/0/properties/name")                   |
| [containerPort](#containerport) | `integer` | Required | cannot be null | [Application](application-properties-ports-items-items-properties-containerport.md "https://facets.cloud/application.schema.json#/properties/ports/items/0/properties/containerPort") |
| [lbPort](#lbport)               | `integer` | Required | cannot be null | [Application](application-properties-ports-items-items-properties-lbport.md "https://facets.cloud/application.schema.json#/properties/ports/items/0/properties/lbPort")               |

## name



`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-ports-items-items-properties-name.md "https://facets.cloud/application.schema.json#/properties/ports/items/0/properties/name")

### name Type

`string`

## containerPort



`containerPort`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-ports-items-items-properties-containerport.md "https://facets.cloud/application.schema.json#/properties/ports/items/0/properties/containerPort")

### containerPort Type

`integer`

## lbPort



`lbPort`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-ports-items-items-properties-lbport.md "https://facets.cloud/application.schema.json#/properties/ports/items/0/properties/lbPort")

### lbPort Type

`integer`
