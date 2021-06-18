# Untitled object in Table entity Schema

```txt
https://streaminlinedata.ai/entity/data/table.json#/properties/columns/items
```

Type for capturing a column in a table

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [table.json*](table.md "open original schema") |

## items Type

`object` ([Details](table-definitions-column.md))

# items Properties

| Property                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                 |
| :------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)                         | `string`  | Required | cannot be null | [Table entity](table-definitions-column-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/name")                       |
| [columnDataType](#columndatatype)     | `string`  | Required | cannot be null | [Table entity](table-definitions-columndatatype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnDataType")                     |
| [description](#description)           | `string`  | Optional | cannot be null | [Table entity](table-definitions-column-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/description")         |
| [piiTags](#piitags)                   | `array`   | Optional | cannot be null | [Table entity](table-definitions-column-properties-piitags.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/piiTags")                 |
| [columnConstraint](#columnconstraint) | `string`  | Optional | cannot be null | [Table entity](table-definitions-columnconstraint.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint")                 |
| [ordinalPosition](#ordinalposition)   | `integer` | Optional | cannot be null | [Table entity](table-definitions-column-properties-ordinalposition.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/ordinalPosition") |

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

Type for capturing a column in a table

`columnDataType`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-columndatatype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnDataType")

### columnDataType Type

`string`

### columnDataType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"NUMBER"`     |             |
| `"TINYINT"`    |             |
| `"SMALLINT"`   |             |
| `"INT"`        |             |
| `"BIGINT"`     |             |
| `"FLOAT"`      |             |
| `"DOUBLE"`     |             |
| `"DECIMAL"`    |             |
| `"NUMERIC"`    |             |
| `"TIMESTAMP"`  |             |
| `"TIME"`       |             |
| `"DATE"`       |             |
| `"DATETIME"`   |             |
| `"INTERVAL"`   |             |
| `"STRING"`     |             |
| `"MEDIUMTEXT"` |             |
| `"TEXT"`       |             |
| `"CHAR"`       |             |
| `"VARCHAR"`    |             |
| `"BOOLEAN"`    |             |
| `"BINARY"`     |             |
| `"VARBINARY"`  |             |
| `"ARRAY"`      |             |
| `"BLOB"`       |             |
| `"LONGBLOB"`   |             |
| `"MEDIUMBLOB"` |             |
| `"MAP"`        |             |
| `"STRUCT"`     |             |
| `"UNION"`      |             |
| `"SET"`        |             |
| `"GEOGRAPHY"`  |             |
| `"ENUM"`       |             |

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

Column constraint

`columnConstraint`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-columnconstraint.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint")

### columnConstraint Type

`string`

### columnConstraint Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"NULL"`        |             |
| `"NOT_NULL"`    |             |
| `"UNIQUE"`      |             |
| `"PRIMARY_KEY"` |             |

### columnConstraint Default Value

The default value is:

```json
"NULL"
```

## ordinalPosition

Ordinal position of the column

`ordinalPosition`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-ordinalposition.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/ordinalPosition")

### ordinalPosition Type

`integer`
