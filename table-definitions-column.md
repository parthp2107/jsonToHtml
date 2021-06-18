# Untitled object in Table entity Schema

```txt
https://streaminlinedata.ai/entity/data/table.json#/properties/columns/items
```

Type for capturing a column in a table

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                          |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [createTable.json*](../out/schema/api/data/createTable.json "open original schema") |

## items Type

`object` ([Details](table-definitions-column.md))

# items Properties

| Property                              | Type          | Required | Nullable       | Defined by                                                                                                                                                                   |
| :------------------------------------ | :------------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)                         | `string`      | Required | cannot be null | [Table entity](table-definitions-column-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/name")                         |
| [columnDataType](#columndatatype)     | Not specified | Required | cannot be null | [Table entity](table-definitions-column-properties-columndatatype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnDataType")     |
| [description](#description)           | `string`      | Optional | cannot be null | [Table entity](table-definitions-column-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/description")           |
| [piiTags](#piitags)                   | `array`       | Optional | cannot be null | [Table entity](table-definitions-column-properties-piitags.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/piiTags")                   |
| [columnConstraint](#columnconstraint) | Not specified | Optional | cannot be null | [Table entity](table-definitions-column-properties-columnconstraint.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint") |
| [ordinalPosition](#ordinalposition)   | `integer`     | Optional | cannot be null | [Table entity](table-definitions-column-properties-ordinalposition.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/ordinalPosition")   |

## name

Name of the column

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## columnDataType

Data type of the column (int, date etc.)

`columnDataType`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-columndatatype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnDataType")

### columnDataType Type

unknown

## description

Description of the column

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/description")

### description Type

`string`

## piiTags

Entities that are added as part of this resource

`piiTags`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-piitags.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/piiTags")

### piiTags Type

`string[]`

## columnConstraint

Column level constraint

`columnConstraint`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-columnconstraint.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint")

### columnConstraint Type

unknown

## ordinalPosition

Ordinal position of the column

`ordinalPosition`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-ordinalposition.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/ordinalPosition")

### ordinalPosition Type

`integer`
