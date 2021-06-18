# Table entity Schema

```txt
https://streaminlinedata.ai/entity/data/table.json
```

Schema corresponding to a table that belongs to a database

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [createTable.json](../out/schema/api/data/createTable.json "open original schema") |

## Table entity Type

`object` ([Table entity](createtable.md))

# Table entity Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                   |
| :------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)                         | `string` | Required | cannot be null | [Table entity](createtable-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/properties/name")                         |
| [description](#description)           | `string` | Optional | cannot be null | [Table entity](createtable-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/properties/description")           |
| [tableType](#tabletype)               | `string` | Optional | cannot be null | [Table entity](table-definitions-tabletype.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableType")                    |
| [tier](#tier)                         | `string` | Optional | cannot be null | [Table entity](common-definitions-tier.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tier")                             |
| [columns](#columns)                   | `array`  | Required | cannot be null | [Table entity](createtable-properties-columns.md "https://streaminlinedata.ai/entity/data/table.json#/properties/columns")                   |
| [tableConstraints](#tableconstraints) | `array`  | Optional | cannot be null | [Table entity](createtable-properties-tableconstraints.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableConstraints") |
| [owner](#owner)                       | `object` | Optional | cannot be null | [Table entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/table.json#/properties/owner")                 |
| [database](#database)                 | `string` | Required | cannot be null | [Table entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/data/table.json#/properties/database")                         |

## name

Name that identifies the this entity instance uniquely. Same as id if when name is not unique

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](createtable-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## description

Description of entity instance.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](createtable-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/properties/description")

### description Type

`string`

## tableType

Type for capturing a column in a table

`tableType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-tabletype.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableType")

### tableType Type

`string`

### tableType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                 | Explanation |
| :-------------------- | :---------- |
| `"REGULAR"`           |             |
| `"EXTERNAL"`          |             |
| `"VIEW"`              |             |
| `"SECURE_VIEW"`       |             |
| `"MATERIALIZED_VIEW"` |             |

## tier



> Tier that an entity belongs to based on business importance

`tier`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](common-definitions-tier.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tier")

### tier Type

`string`

### tier Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"tier-1"`  |             |
| `"tier-2"`  |             |
| `"tier-3"`  |             |
| `"tier-4"`  |             |
| `"tier-5"`  |             |
| `"unknown"` |             |

## columns

Name of the tables in the database

`columns`

*   is required

*   Type: `object[]` ([Details](table-definitions-column.md))

*   cannot be null

*   defined in: [Table entity](createtable-properties-columns.md "https://streaminlinedata.ai/entity/data/table.json#/properties/columns")

### columns Type

`object[]` ([Details](table-definitions-column.md))

## tableConstraints



`tableConstraints`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Table entity](createtable-properties-tableconstraints.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableConstraints")

### tableConstraints Type

unknown\[]

## owner

Owner of this entity

> Entity reference that includes entity ID and entity type

`owner`

*   is optional

*   Type: `object` ([Details](common-definitions-entityreference.md))

*   cannot be null

*   defined in: [Table entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/table.json#/properties/owner")

### owner Type

`object` ([Details](common-definitions-entityreference.md))

## database

Unique id used to identify an entity

`database`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/data/table.json#/properties/database")

### database Type

`string`

### database Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122 "check the specification")
