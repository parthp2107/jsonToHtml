# Pipeline entity Schema

```txt
https://streaminlinedata.ai/entity/data/pipeline.json
```

Entity that represents a Pipeline

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [pipeline.json](pipeline.md "open original schema") |

## Pipeline entity Type

`object` ([Pipeline entity](pipeline.md))

# Pipeline entity Properties

| Property                                  | Type          | Required | Nullable       | Defined by                                                                                                                                          |
| :---------------------------------------- | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                 | Not specified | Required | cannot be null | [Pipeline entity](pipeline-properties-id.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/id")                                 |
| [name](#name)                             | `string`      | Required | cannot be null | [Pipeline entity](pipeline-properties-name.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/name")                             |
| [fullyQualifiedName](#fullyqualifiedname) | `string`      | Optional | cannot be null | [Pipeline entity](pipeline-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/fullyQualifiedName") |
| [description](#description)               | `string`      | Optional | cannot be null | [Pipeline entity](pipeline-properties-description.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/description")               |
| [href](#href)                             | Not specified | Optional | cannot be null | [Pipeline entity](pipeline-properties-href.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/href")                             |
| [owner](#owner)                           | Not specified | Optional | cannot be null | [Pipeline entity](pipeline-properties-owner.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/owner")                           |
| [service](#service)                       | Not specified | Required | cannot be null | [Pipeline entity](pipeline-properties-service.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/service")                       |

## id

Unique identifier that identifies a pipeline instance

`id`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Pipeline entity](pipeline-properties-id.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/id")

### id Type

unknown

## name

Name that identifies the this pipeline instance uniquely.

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Pipeline entity](pipeline-properties-name.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## fullyQualifiedName

Unique name that identifies a pipeline in the format 'ServiceName.PipelineName'

`fullyQualifiedName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Pipeline entity](pipeline-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/fullyQualifiedName")

### fullyQualifiedName Type

`string`

### fullyQualifiedName Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## description

Description of this pipeline.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Pipeline entity](pipeline-properties-description.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

`href`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Pipeline entity](pipeline-properties-href.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/href")

### href Type

unknown

## owner

Owner of this pipeline

`owner`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Pipeline entity](pipeline-properties-owner.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/owner")

### owner Type

unknown

## service

Link to service where this pipeline is hosted in

`service`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Pipeline entity](pipeline-properties-service.md "https://streaminlinedata.ai/entity/data/pipeline.json#/properties/service")

### service Type

unknown
