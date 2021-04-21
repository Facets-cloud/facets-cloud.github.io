# scaling Schema

```txt
https://facets.cloud/application.schema.json#/properties/scaling
```

This Section allows you to configure autoscaling features of your application

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [application.schema.json*](../../../assets/out/application.schema.json "open original schema") |

## scaling Type

`object` ([scaling](application-properties-scaling.md))

# scaling Properties

| Property                                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                      |
| :---------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [hpaEnabled](#hpaenabled)                 | `boolean` | Required | cannot be null | [Application](application-properties-scaling-properties-hpaenabled.md "https://facets.cloud/application.schema.json#/properties/scaling/properties/hpaEnabled")                 |
| [hpaMinReplicas](#hpaminreplicas)         | `integer` | Required | cannot be null | [Application](application-properties-scaling-properties-hpaminreplicas.md "https://facets.cloud/application.schema.json#/properties/scaling/properties/hpaMinReplicas")         |
| [hpaMaxReplicas](#hpamaxreplicas)         | `integer` | Required | cannot be null | [Application](application-properties-scaling-properties-hpamaxreplicas.md "https://facets.cloud/application.schema.json#/properties/scaling/properties/hpaMaxReplicas")         |
| [hpaMetricThreshold](#hpametricthreshold) | `integer` | Required | cannot be null | [Application](application-properties-scaling-properties-hpametricthreshold.md "https://facets.cloud/application.schema.json#/properties/scaling/properties/hpaMetricThreshold") |

## hpaEnabled

The Horizontal Pod Autoscaler automatically scales the number of Pods in a replication controller, deployment, replica set or stateful set based on observed CPU utilization

`hpaEnabled`

*   is required

*   Type: `boolean`

*   cannot be null

*   defined in: [Application](application-properties-scaling-properties-hpaenabled.md "https://facets.cloud/application.schema.json#/properties/scaling/properties/hpaEnabled")

### hpaEnabled Type

`boolean`

## hpaMinReplicas

Minimum count of replicas which should always be running

`hpaMinReplicas`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-scaling-properties-hpaminreplicas.md "https://facets.cloud/application.schema.json#/properties/scaling/properties/hpaMinReplicas")

### hpaMinReplicas Type

`integer`

## hpaMaxReplicas

Maximum count of replicas which this application can scale upto

`hpaMaxReplicas`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-scaling-properties-hpamaxreplicas.md "https://facets.cloud/application.schema.json#/properties/scaling/properties/hpaMaxReplicas")

### hpaMaxReplicas Type

`integer`

## hpaMetricThreshold

Threshold for the metric value (Default is CPU) on which to spawn a new replica.

`hpaMetricThreshold`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [Application](application-properties-scaling-properties-hpametricthreshold.md "https://facets.cloud/application.schema.json#/properties/scaling/properties/hpaMetricThreshold")

### hpaMetricThreshold Type

`integer`
