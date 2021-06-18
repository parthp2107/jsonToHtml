# Database entity Schema

```txt
https://streaminlinedata.ai/entity/data/database.json
```

Entity that represents a database

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                      |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [database.json](../out/schema/entity/data/database.json "open original schema") |

## Database entity Type

`object` ([Database entity](database.md))

# Database entity Properties

| Property                                  | Type     | Required | Nullable       | Defined by                                                                                                                                          |
| :---------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                 | `string` | Optional | cannot be null | [Database entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/data/database.json#/properties/id")                                |
| [name](#name)                             | `string` | Required | cannot be null | [Database entity](database-properties-name.md "https://streaminlinedata.ai/entity/data/database.json#/properties/name")                             |
| [fullyQualifiedName](#fullyqualifiedname) | `string` | Optional | cannot be null | [Database entity](database-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/database.json#/properties/fullyQualifiedName") |
| [description](#description)               | `string` | Optional | cannot be null | [Database entity](database-properties-description.md "https://streaminlinedata.ai/entity/data/database.json#/properties/description")               |
| [href](#href)                             | `string` | Optional | cannot be null | [Database entity](common-definitions-href.md "https://streaminlinedata.ai/entity/data/database.json#/properties/href")                              |
| [owner](#owner)                           | `object` | Optional | cannot be null | [Database entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/database.json#/properties/owner")                  |
| [service](#service)                       | `object` | Required | cannot be null | [Database entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/database.json#/properties/service")                |
| [usageSummary](#usagesummary)             | `object` | Optional | cannot be null | [Database entity](common-definitions-usagedetails.md "https://streaminlinedata.ai/entity/data/database.json#/properties/usageSummary")              |
| [tables](#tables)                         | `array`  | Optional | cannot be null | [Database entity](database-properties-tables.md "https://streaminlinedata.ai/entity/data/database.json#/properties/tables")                         |

## id

Unique id used to identify an entity

`id`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Database entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/data/database.json#/properties/id")

### id Type

`string`

### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122 "check the specification")

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

> Link to the resource

`href`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Database entity](common-definitions-href.md "https://streaminlinedata.ai/entity/data/database.json#/properties/href")

### href Type

`string`

### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

## owner

Owner of this database

> Entity reference that includes entity ID and entity type

`owner`

*   is optional

*   Type: `object` ([Details](common-definitions-entityreference.md))

*   cannot be null

*   defined in: [Database entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/database.json#/properties/owner")

### owner Type

`object` ([Details](common-definitions-entityreference.md))

## service

Link to the database cluster/service where this database is hosted in

> Entity reference that includes entity ID and entity type

`service`

*   is required

*   Type: `object` ([Details](common-definitions-entityreference.md))

*   cannot be null

*   defined in: [Database entity](common-definitions-entityreference.md "https://streaminlinedata.ai/entity/data/database.json#/properties/service")

### service Type

`object` ([Details](common-definitions-entityreference.md))

## usageSummary

Latest usage information for this database

> Type used to return usage details

`usageSummary`

*   is optional

*   Type: `object` ([Details](common-definitions-usagedetails.md))

*   cannot be null

*   defined in: [Database entity](common-definitions-usagedetails.md "https://streaminlinedata.ai/entity/data/database.json#/properties/usageSummary")

### usageSummary Type

`object` ([Details](common-definitions-usagedetails.md))

## tables

References to tables in the database

`tables`

*   is optional

*   Type: `object[]` ([Details](common-definitions-entityreference.md))

*   cannot be null

*   defined in: [Database entity](database-properties-tables.md "https://streaminlinedata.ai/entity/data/database.json#/properties/tables")

### tables Type

`object[]` ([Details](common-definitions-entityreference.md))
