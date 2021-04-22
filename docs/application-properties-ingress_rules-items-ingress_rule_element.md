# ingress_rule_Element Schema

```txt
https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../out/application.schema.json "open original schema") |

## 0 Type

`object` ([ingress_rule_Element](application-properties-ingress_rules-items-ingress_rule_element.md))

# 0 Properties

| Property                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                     |
| :---------------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ingress](#ingress)           | `string`  | Required | cannot be null | [Application](application-properties-ingress_rules-items-ingress_rule_element-properties-ingress.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0/properties/ingress")           |
| [path](#path)                 | `string`  | Required | cannot be null | [Application](application-properties-ingress_rules-items-ingress_rule_element-properties-path.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0/properties/path")                 |
| [targetPort](#targetport)     | `integer` | Required | cannot be null | [Application](application-properties-ingress_rules-items-ingress_rule_element-properties-targetport.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0/properties/targetPort")     |
| [domainPrefix](#domainprefix) | `string`  | Required | cannot be null | [Application](application-properties-ingress_rules-items-ingress_rule_element-properties-domainprefix.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0/properties/domainPrefix") |

## ingress

Name of the defined ingress on which this application needs to be mapped. (Double check the name in ingress directory.)

`ingress`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-ingress_rules-items-ingress_rule_element-properties-ingress.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0/properties/ingress")

### ingress Type

`string`

## path



`path`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-ingress_rules-items-ingress_rule_element-properties-path.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0/properties/path")

### path Type

`string`

## targetPort



`targetPort`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-ingress_rules-items-ingress_rule_element-properties-targetport.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0/properties/targetPort")

### targetPort Type

`integer`

## domainPrefix



`domainPrefix`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-ingress_rules-items-ingress_rule_element-properties-domainprefix.md "https://facets.cloud/assets/fsdl/application.schema.json#/properties/ingress_rules/items/0/properties/domainPrefix")

### domainPrefix Type

`string`
