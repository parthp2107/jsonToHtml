# Database entity Schema

```txt
https://streaminlinedata.ai/entity/data/database.json
```

Entity that represents a database

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [database.json](database.md "open original schema") |

## Database entity Type

`object` ([Database entity](database.md))

# Database entity Properties

| Property                                  | Type          | Required | Nullable       | Defined by                                                                                                                                          |
| :---------------------------------------- | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                 | Not specified | Optional | cannot be null | [Database entity](database-properties-id.md "https://streaminlinedata.ai/entity/data/database.json#/properties/id")                                 |
| [name](#name)                             | `string`      | Required | cannot be null | [Database entity](database-properties-name.md "https://streaminlinedata.ai/entity/data/database.json#/properties/name")                             |
| [fullyQualifiedName](#fullyqualifiedname) | `string`      | Optional | cannot be null | [Database entity](database-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/database.json#/properties/fullyQualifiedName") |
| [description](#description)               | `string`      | Optional | cannot be null | [Database entity](database-properties-description.md "https://streaminlinedata.ai/entity/data/database.json#/properties/description")               |
| [href](#href)                             | Not specified | Optional | cannot be null | [Database entity](database-properties-href.md "https://streaminlinedata.ai/entity/data/database.json#/properties/href")                             |
| [owner](#owner)                           | Not specified | Optional | cannot be null | [Database entity](database-properties-owner.md "https://streaminlinedata.ai/entity/data/database.json#/properties/owner")                           |
| [service](#service)                       | Not specified | Required | cannot be null | [Database entity](database-properties-service.md "https://streaminlinedata.ai/entity/data/database.json#/properties/service")                       |
| [usageSummary](#usagesummary)             | Not specified | Optional | cannot be null | [Database entity](database-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/database.json#/properties/usageSummary")             |
| [tables](#tables)                         | `array`       | Optional | cannot be null | [Database entity](database-properties-tables.md "https://streaminlinedata.ai/entity/data/database.json#/properties/tables")                         |

## id

Unique identifier that identifies this database instance

`id`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Database entity](database-properties-id.md "https://streaminlinedata.ai/entity/data/database.json#/properties/id")

### id Type

unknown

## name

Name that identifies the database

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Database entity](database-properties-name.md "https://streaminlinedata.ai/entity/data/database.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## fullyQualifiedName

Name that uniquely identifees a database in the format 'ServiceName.DatabaseName'

`fullyQualifiedName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Database entity](database-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/database.json#/properties/fullyQualifiedName")

### fullyQualifiedName Type

`string`

## description

Description of the database instance. What it has and how to use it.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Database entity](database-properties-description.md "https://streaminlinedata.ai/entity/data/database.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

`href`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Database entity](database-properties-href.md "https://streaminlinedata.ai/entity/data/database.json#/properties/href")

### href Type

unknown

## owner

Owner of this database

`owner`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Database entity](database-properties-owner.md "https://streaminlinedata.ai/entity/data/database.json#/properties/owner")

### owner Type

unknown

## service

Link to the database cluster/service where this database is hosted in

`service`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Database entity](database-properties-service.md "https://streaminlinedata.ai/entity/data/database.json#/properties/service")

### service Type

unknown

## usageSummary

Latest usage information for this database

`usageSummary`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Database entity](database-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/database.json#/properties/usageSummary")

### usageSummary Type

unknown

## tables

References to tables in the database

`tables`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Database entity](database-properties-tables.md "https://streaminlinedata.ai/entity/data/database.json#/properties/tables")

### tables Type

unknown\[]
