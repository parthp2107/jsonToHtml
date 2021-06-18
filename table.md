# Table entity Schema

```txt
https://streaminlinedata.ai/entity/data/table.json
```

Schema corresponding to a table that belongs to a database

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------ |
| Can be instantiated | Yes        | Unknown status | No           | Forbidden         | Allowed               | none                | [table.json](../out/schema/entity/data/table.json "open original schema") |

## Table entity Type

`object` ([Table entity](table.md))

# Table entity Properties

| Property                                  | Type          | Required | Nullable       | Defined by                                                                                                                                 |
| :---------------------------------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                 | `string`      | Optional | cannot be null | [Table entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/data/table.json#/properties/id")                             |
| [name](#name)                             | `string`      | Required | cannot be null | [Table entity](table-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/properties/name")                             |
| [description](#description)               | `string`      | Optional | cannot be null | [Table entity](table-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/properties/description")               |
| [href](#href)                             | `string`      | Optional | cannot be null | [Table entity](common-definitions-href.md "https://streaminlinedata.ai/entity/data/table.json#/properties/href")                           |
| [tableType](#tabletype)                   | Not specified | Optional | cannot be null | [Table entity](table-properties-tabletype.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableType")                   |
| [fullyQualifiedName](#fullyqualifiedname) | `string`      | Optional | cannot be null | [Table entity](table-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/table.json#/properties/fullyQualifiedName") |
| [tier](#tier)                             | `string`      | Optional | cannot be null | [Table entity](common-definitions-tier.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tier")                           |
| [columns](#columns)                       | `array`       | Required | cannot be null | [Table entity](table-properties-columns.md "https://streaminlinedata.ai/entity/data/table.json#/properties/columns")                       |
| [tableConstraints](#tableconstraints)     | `array`       | Optional | cannot be null | [Table entity](table-properties-tableconstraints.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableConstraints")     |
| [usageSummary](#usagesummary)             | `object`      | Optional | cannot be null | [Table entity](common-definitions-usagedetails.md "https://streaminlinedata.ai/entity/data/table.json#/properties/usageSummary")           |
| [owner](#owner)                           | `object`      | Optional | cannot be null | [Table entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/table.json#/properties/owner")               |
| [database](#database)                     | `object`      | Optional | cannot be null | [Table entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/table.json#/properties/database")            |

## id

Unique id used to identify an entity

`id`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/data/table.json#/properties/id")

### id Type

`string`

### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122 "check the specification")

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

> Link to the resource

`href`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Table entity](common-definitions-href.md "https://streaminlinedata.ai/entity/data/table.json#/properties/href")

### href Type

`string`

### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

## tableType



`tableType`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-properties-tabletype.md "https://streaminlinedata.ai/entity/data/table.json#/properties/tableType")

### tableType Type

unknown

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

Columns in the table

`columns`

*   is required

*   Type: unknown\[]

*   cannot be null

*   defined in: [Table entity](table-properties-columns.md "https://streaminlinedata.ai/entity/data/table.json#/properties/columns")

### columns Type

unknown\[]

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

> Type used to return usage details

`usageSummary`

*   is optional

*   Type: `object` ([Details](common-definitions-usagedetails.md))

*   cannot be null

*   defined in: [Table entity](common-definitions-usagedetails.md "https://streaminlinedata.ai/entity/data/table.json#/properties/usageSummary")

### usageSummary Type

`object` ([Details](common-definitions-usagedetails.md))

## owner

Owner of this table

> Entity reference that includes entity ID and entity type

`owner`

*   is optional

*   Type: `object` ([Details](common-definitions-entityreference.md))

*   cannot be null

*   defined in: [Table entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/table.json#/properties/owner")

### owner Type

`object` ([Details](common-definitions-entityreference.md))

## database

Reference to Database that contains this table

> Entity reference that includes entity ID and entity type

`database`

*   is optional

*   Type: `object` ([Details](common-definitions-entityreference.md))

*   cannot be null

*   defined in: [Table entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/table.json#/properties/database")

### database Type

`object` ([Details](common-definitions-entityreference.md))

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

| Property                              | Type          | Required | Nullable       | Defined by                                                                                                                                                                   |
| :------------------------------------ | :------------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name-1)                       | `string`      | Required | cannot be null | [Table entity](table-definitions-column-properties-name.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/name")                         |
| [columnDataType](#columndatatype)     | Not specified | Required | cannot be null | [Table entity](table-definitions-column-properties-columndatatype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnDataType")     |
| [description](#description-1)         | `string`      | Optional | cannot be null | [Table entity](table-definitions-column-properties-description.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/description")           |
| [piiTags](#piitags)                   | `array`       | Optional | cannot be null | [Table entity](table-definitions-column-properties-piitags.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/piiTags")                   |
| [columnConstraint](#columnconstraint) | Not specified | Optional | cannot be null | [Table entity](table-definitions-column-properties-columnconstraint.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint") |
| [ordinalPosition](#ordinalposition)   | `integer`     | Optional | cannot be null | [Table entity](table-definitions-column-properties-ordinalposition.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/ordinalPosition")   |

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

Data type of the column (int, date etc.)

`columnDataType`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-columndatatype.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnDataType")

#### columnDataType Type

unknown

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

Column level constraint

`columnConstraint`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-columnconstraint.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint")

#### columnConstraint Type

unknown

### ordinalPosition

Ordinal position of the column

`ordinalPosition`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Table entity](table-definitions-column-properties-ordinalposition.md "https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/ordinalPosition")

#### ordinalPosition Type

`integer`
