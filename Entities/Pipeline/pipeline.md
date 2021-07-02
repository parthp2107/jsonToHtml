---
layout: default
title: Pipeline
---

# pipeline

## Pipeline entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/pipeline.json
```

Entity that represents a Pipeline

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [pipeline.json](pipeline.md) |

### Pipeline entity Type

`object` \([Pipeline entity](pipeline.md)\)

## Pipeline entity Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [id](pipeline.md#id) | `string` | Required | cannot be null | [Pipeline entity](../../Types/Common/common-definitions-uuid.md) |
| [name](pipeline.md#name) | `string` | Required | cannot be null | [Pipeline entity](pipeline-properties-name.md) |
| [fullyQualifiedName](pipeline.md#fullyqualifiedname) | `string` | Optional | cannot be null | [Pipeline entity](pipeline-properties-fullyqualifiedname.md) |
| [description](pipeline.md#description) | `string` | Optional | cannot be null | [Pipeline entity](pipeline-properties-description.md) |
| [href](pipeline.md#href) | `string` | Optional | cannot be null | [Pipeline entity](../../Types/Common/common-definitions-href.md) |
| [owner](pipeline.md#owner) | `object` | Optional | cannot be null | [Pipeline entity](../../Types/Common/common-definitions-entityreference.md) |
| [service](pipeline.md#service) | `object` | Required | cannot be null | [Pipeline entity](../../Types/Common/common-definitions-entityreference.md) |

### id

Unique id used to identify an entity

`id`

* is required
* Type: `string`
* cannot be null
* defined in: [Pipeline entity](../../Types/Common/common-definitions-uuid.md)

#### id Type

`string`

#### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

### name

Name that identifies the this pipeline instance uniquely.

`name`

* is required
* Type: `string`
* cannot be null
* defined in: [Pipeline entity](pipeline-properties-name.md)

#### name Type

`string`

#### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

### fullyQualifiedName

Unique name that identifies a pipeline in the format 'ServiceName.PipelineName'

`fullyQualifiedName`

* is optional
* Type: `string`
* cannot be null
* defined in: [Pipeline entity](pipeline-properties-fullyqualifiedname.md)

#### fullyQualifiedName Type

`string`

#### fullyQualifiedName Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

### description

Description of this pipeline.

`description`

* is optional
* Type: `string`
* cannot be null
* defined in: [Pipeline entity](pipeline-properties-description.md)

#### description Type

`string`

### href

Link to the resource corresponding to this entity

> Link to the resource

`href`

* is optional
* Type: `string`
* cannot be null
* defined in: [Pipeline entity](../../Types/Common/common-definitions-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

### owner

Owner of this pipeline

> Entity reference that includes entity ID and entity type

`owner`

* is optional
* Type: `object` \([Details](../../Types/Common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [Pipeline entity](../../Types/Common/common-definitions-entityreference.md)

#### owner Type

`object` \([Details](../../Types/Common/common-definitions-entityreference.md)\)

### service

Link to service where this pipeline is hosted in

> Entity reference that includes entity ID and entity type

`service`

* is required
* Type: `object` \([Details](../../Types/Common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [Pipeline entity](../../Types/Common/common-definitions-entityreference.md)

#### service Type

`object` \([Details](../../Types/Common/common-definitions-entityreference.md)\)

