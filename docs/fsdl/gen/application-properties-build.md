# build Schema

```txt
https://facets.cloud/application.schema.json#/properties/build
```

This section describes how to fetch build for this application

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../../../assets/out/application.schema.json "open original schema") |

## build Type

`object` ([build](application-properties-build.md))

# build Properties

| Property  | Type     | Required | Nullable       | Defined by                                                                                                                                  |
| :-------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------ |
| [ci](#ci) | `string` | Required | cannot be null | [Application](application-properties-build-properties-ci.md "https://facets.cloud/application.schema.json#/properties/build/properties/ci") |
| [id](#id) | `string` | Required | cannot be null | [Application](application-properties-build-properties-id.md "https://facets.cloud/application.schema.json#/properties/build/properties/id") |

## ci

The artifactory name from which the builds are fetched, or external_image with fixed images

`ci`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-build-properties-ci.md "https://facets.cloud/application.schema.json#/properties/build/properties/ci")

### ci Type

`string`

## id

The id of the build in the artifactory.

`id`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Application](application-properties-build-properties-id.md "https://facets.cloud/application.schema.json#/properties/build/properties/id")

### id Type

`string`
