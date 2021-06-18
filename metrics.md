# Metrics entity Schema

```txt
https://streaminlinedata.ai/entity/data/metrics.json
```

Entity that represents a Metrics

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                      |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [metrics.json](../out/data/metrics.json "open original schema") |

## Metrics entity Type

`object` ([Metrics entity](metrics.md))

# Metrics entity Properties

| Property                                  | Type          | Required | Nullable       | Defined by                                                                                                                                       |
| :---------------------------------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                 | Not specified | Required | cannot be null | [Metrics entity](metrics-properties-id.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/id")                                 |
| [name](#name)                             | `string`      | Required | cannot be null | [Metrics entity](metrics-properties-name.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/name")                             |
| [fullyQualifiedName](#fullyqualifiedname) | `string`      | Optional | cannot be null | [Metrics entity](metrics-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/fullyQualifiedName") |
| [description](#description)               | `string`      | Optional | cannot be null | [Metrics entity](metrics-properties-description.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/description")               |
| [href](#href)                             | Not specified | Optional | cannot be null | [Metrics entity](metrics-properties-href.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/href")                             |
| [owner](#owner)                           | Not specified | Optional | cannot be null | [Metrics entity](metrics-properties-owner.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/owner")                           |
| [service](#service)                       | Not specified | Required | cannot be null | [Metrics entity](metrics-properties-service.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/service")                       |
| [usageSummary](#usagesummary)             | Not specified | Optional | cannot be null | [Metrics entity](metrics-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/usageSummary")             |

## id

Unique identifier that identifies this metrics instance

`id`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Metrics entity](metrics-properties-id.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/id")

### id Type

unknown

## name

Name that identifies the this metrics instance uniquely.

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Metrics entity](metrics-properties-name.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## fullyQualifiedName

Unique name that identifies a metric in the format 'ServiceName.MetricName'

`fullyQualifiedName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Metrics entity](metrics-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/fullyQualifiedName")

### fullyQualifiedName Type

`string`

### fullyQualifiedName Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## description

Description of metrics instance. What is has and how to use it

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Metrics entity](metrics-properties-description.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

`href`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Metrics entity](metrics-properties-href.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/href")

### href Type

unknown

## owner

Owner of this metrics

`owner`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Metrics entity](metrics-properties-owner.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/owner")

### owner Type

unknown

## service

Link to service where this metrics is hosted in

`service`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Metrics entity](metrics-properties-service.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/service")

### service Type

unknown

## usageSummary

Latest usage information for this database

`usageSummary`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Metrics entity](metrics-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/metrics.json#/properties/usageSummary")

### usageSummary Type

unknown
