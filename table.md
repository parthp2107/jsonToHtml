# Table entity Schema

```txt
https://streaminlinedata.ai/entity/data/table.json
```

Schema corresponding to a table that belongs to a database

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                  |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------- |
| Can be instantiated | Yes        | Unknown status | No           | Forbidden         | Allowed               | none                | [table.json](table.md "open original schema") |

## Table entity Type

`object` ([Table entity](table.md))

# Table entity Properties

| Property                                  | Type          | Required | Nullable       | Defined by                                                                                                                                 |
| :---------------------------------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                 | Not specified | Optional | cannot be null | [Table entity](table-properties-id.md "https://streaminlinedata.ai/entity/data/table.json#/properties/id")                                 |
| [name](#name)                             | `string`      | Required | cannot be null | [Table entity](table-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/properties/name")                             |
| [description](#description)               | `string`      | Optional | cannot be null | [Table entity](table-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/properties/description")               |
| [href](#href)                             | Not specified | Optional | cannot be null | [Table entity](table-properties-href.md "https://streaminlinedata.ai/entity/data/table.json#/properties/href")                             |
| [tableType](#tabletype)                   | `string`      | Optional | cannot be null | [Table entity](table-properties-tabletype.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableType")                   |
| [fullyQualifiedName](#fullyqualifiedname) | `string`      | Optional | cannot be null | [Table entity](table-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/table.json#/properties/fullyQualifiedName") |
| [tier](#tier)                             | Not specified | Optional | cannot be null | [Table entity](table-properties-tier.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tier")                             |
| [columns](#columns)                       | `array`       | Required | cannot be null | [Table entity](table-properties-columns.md "https://streaminlinedata.ai/entity/data/table.json#/properties/columns")                       |
| [tableConstraints](#tableconstraints)     | `array`       | Optional | cannot be null | [Table entity](table-properties-tableconstraints.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableConstraints")     |
| [usageSummary](#usagesummary)             | Not specified | Optional | cannot be null | [Table entity](table-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/table.json#/properties/usageSummary")             |
| [owner](#owner)                           | Not specified | Optional | cannot be null | [Table entity](table-properties-owner.md "https://streaminlinedata.ai/entity/data/table.json#/properties/owner")                           |
| [database](#database)                     | Not specified | Optional | cannot be null | [Table entity](table-properties-database.md "https://streaminlinedata.ai/entity/data/table.json#/properties/database")                     |

## id

Unique identifier that identifies this table instance

`id`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-properties-id.md "https://streaminlinedata.ai/entity/data/table.json#/properties/id")

### id Type

unknown

## name

Name of the table. Expected to be unique with in a database

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/properties/name")

### name Type

`string`

## description

Description of the table

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/properties/description")

### description Type

`string`

### description Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## href

Link to this table resource

`href`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-properties-href.md "https://streaminlinedata.ai/entity/data/table.json#/properties/href")

### href Type

unknown

## tableType

Type for capturing a column in a table

`tableType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-properties-tabletype.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableType")

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

## fullyQualifiedName

Fully qualified name of the table in the form serviceName.databaseName.tableName

`fullyQualifiedName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/table.json#/properties/fullyQualifiedName")

### fullyQualifiedName Type

`string`

## tier



`tier`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-properties-tier.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tier")

### tier Type

unknown

## columns

Columns in the table

`columns`

*   is required

*   Type: `object[]` ([Details](table-definitions-column.md))

*   cannot be null

*   defined in: [Table entity](table-properties-columns.md "https://streaminlinedata.ai/entity/data/table.json#/properties/columns")

### columns Type

`object[]` ([Details](table-definitions-column.md))

## tableConstraints



`tableConstraints`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Table entity](table-properties-tableconstraints.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableConstraints")

### tableConstraints Type

unknown\[]

## usageSummary

Latest usage information for this table

`usageSummary`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/table.json#/properties/usageSummary")

### usageSummary Type

unknown

## owner

Owner of this table

`owner`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-properties-owner.md "https://streaminlinedata.ai/entity/data/table.json#/properties/owner")

### owner Type

unknown

## database

Reference to Database that contains this table

`database`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-properties-database.md "https://streaminlinedata.ai/entity/data/table.json#/properties/database")

### database Type

unknown

# Table entity Definitions

## Definitions group tableType

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/entity/data/table.json#/definitions/tableType"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group columnDataType

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/entity/data/table.json#/definitions/columnDataType"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group columnConstraint

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/entity/data/table.json#/definitions/columnConstraint"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group tableConstraint

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/entity/data/table.json#/definitions/tableConstraint"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                 |
| :-------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [constraintType](#constrainttype) | `string` | Optional | cannot be null | [Table entity](table-definitions-tableconstraint-properties-constrainttype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/tableConstraint/properties/constraintType") |
| [columns](#columns-1)             | `array`  | Optional | cannot be null | [Table entity](table-definitions-tableconstraint-properties-columns.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/tableConstraint/properties/columns")               |

### constraintType



`constraintType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-tableconstraint-properties-constrainttype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/tableConstraint/properties/constraintType")

#### constraintType Type

`string`

#### constraintType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"UNIQUE"`      |             |
| `"PRIMARY_KEY"` |             |
| `"FOREIGN_KEY"` |             |

### columns

List of column names corresponding to the constraint

`columns`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Table entity](table-definitions-tableconstraint-properties-columns.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/tableConstraint/properties/columns")

#### columns Type

`string[]`

## Definitions group column

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/entity/data/table.json#/definitions/column"}
```

| Property                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                   |
| :------------------------------------ | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name-1)                       | `string`  | Required | cannot be null | [Table entity](table-definitions-column-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/name")                         |
| [columnDataType](#columndatatype)     | `string`  | Required | cannot be null | [Table entity](table-definitions-column-properties-columndatatype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnDataType")     |
| [description](#description-1)         | `string`  | Optional | cannot be null | [Table entity](table-definitions-column-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/description")           |
| [piiTags](#piitags)                   | `array`   | Optional | cannot be null | [Table entity](table-definitions-column-properties-piitags.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/piiTags")                   |
| [columnConstraint](#columnconstraint) | `string`  | Optional | cannot be null | [Table entity](table-definitions-column-properties-columnconstraint.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint") |
| [ordinalPosition](#ordinalposition)   | `integer` | Optional | cannot be null | [Table entity](table-definitions-column-properties-ordinalposition.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/ordinalPosition")   |

### name

Name of the column

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/name")

#### name Type

`string`

#### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

### columnDataType

Type for capturing a column in a table

`columnDataType`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-columndatatype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnDataType")

#### columnDataType Type

`string`

#### columnDataType Constraints

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

### description

Description of the column

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/description")

#### description Type

`string`

### piiTags

Entities that are added as part of this resource

`piiTags`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-piitags.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/piiTags")

#### piiTags Type

`string[]`

### columnConstraint

Column constraint

`columnConstraint`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-columnconstraint.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint")

#### columnConstraint Type

`string`

#### columnConstraint Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"NULL"`        |             |
| `"NOT_NULL"`    |             |
| `"UNIQUE"`      |             |
| `"PRIMARY_KEY"` |             |

#### columnConstraint Default Value

The default value is:

```json
"NULL"
```

### ordinalPosition

Ordinal position of the column

`ordinalPosition`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-ordinalposition.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/ordinalPosition")

#### ordinalPosition Type

`integer`
