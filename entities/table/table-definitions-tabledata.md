---
layout: default
---

# table-definitions-tabledata

## Untitled object in Table entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/table.json#/properties/sampleData
```

Information on other tables that this table column is frequently joined with

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Forbidden | none | [table.json\*](table.md) |

### sampleData Type

`object` \([Details](table-definitions-tabledata.md)\)

## sampleData Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [columns](table-definitions-tabledata.md#columns) | `array` | Optional | cannot be null | [Table entity](table-definitions-tabledata-properties-columns.md) |
| [rows](table-definitions-tabledata.md#rows) | `array` | Optional | cannot be null | [Table entity](table-definitions-tabledata-properties-rows.md) |

### columns

`columns`

* is optional
* Type: `string[]`
* cannot be null
* defined in: [Table entity](table-definitions-tabledata-properties-columns.md)

#### columns Type

`string[]`

### rows

Data for a multiple rows of the table

`rows`

* is optional
* Type: `array[]`
* cannot be null
* defined in: [Table entity](table-definitions-tabledata-properties-rows.md)

#### rows Type

`array[]`

