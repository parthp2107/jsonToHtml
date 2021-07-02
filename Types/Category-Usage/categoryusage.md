---
layout: default
title: Category Usage
---

# categoryusage

## Usage details for an entity class Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/categoryUsage.json
```

Type used for capturing usage details of an entity class

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [categoryUsage.json](categoryusage.md) |

### Usage details for an entity class Type

`object` \([Usage details for an entity class](categoryusage.md)\)

## Usage details for an entity class Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [entity](categoryusage.md#entity) | `string` | Optional | cannot be null | [Usage details for an entity class](categoryusage-properties-entity.md) |
| [usage](categoryusage.md#usage) | `array` | Required | cannot be null | [Usage details for an entity class](categoryusage-properties-usage.md) |

### entity

Name of the entity class for which usage is returned

`entity`

* is optional
* Type: `string`
* cannot be null
* defined in: [Usage details for an entity class](categoryusage-properties-entity.md)

#### entity Type

`string`

### usage

List usage details per day

`usage`

* is required
* Type: `object[]` \([Details](../Common/common-definitions-usagedetails.md)\)
* cannot be null
* defined in: [Usage details for an entity class](categoryusage-properties-usage.md)

#### usage Type

`object[]` \([Details](../Common/common-definitions-usagedetails.md)\)

