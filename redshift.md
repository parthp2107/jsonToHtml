# Redshift service entity Schema

```txt
https://streaminlinedata.ai/entity/services/redshift.json
```

Schema corresponding to Redshift service entity

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                          |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [redshift.json](../out/schema/entity/services/redshift.json "open original schema") |

## Redshift service entity Type

`object` ([Redshift service entity](redshift.md))

# Redshift service entity Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                        |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                   | `string` | Optional | cannot be null | [Redshift service entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/id")                  |
| [name](#name)               | `string` | Required | cannot be null | [Redshift service entity](redshift-properties-name.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/name")               |
| [description](#description) | `string` | Optional | cannot be null | [Redshift service entity](redshift-properties-description.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/description") |
| [href](#href)               | `string` | Required | cannot be null | [Redshift service entity](common-definitions-href.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/href")                |
| [jdbc](#jdbc)               | `object` | Optional | cannot be null | [Redshift service entity](jdbcconnection-definitions-jdbcinfo.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/jdbc")    |

## id

Unique id used to identify an entity

`id`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Redshift service entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/id")

### id Type

`string`

### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122 "check the specification")

## name

Unique name for a redshift cluster. Example: westcoast-prod1

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Redshift service entity](redshift-properties-name.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/name")

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

*   defined in: [Redshift service entity](redshift-properties-description.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

> Link to the resource

`href`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Redshift service entity](common-definitions-href.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/href")

### href Type

`string`

### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

## jdbc



> Type for capturing JDBC connector information

`jdbc`

*   is optional

*   Type: `object` ([Details](jdbcconnection-definitions-jdbcinfo.md))

*   cannot be null

*   defined in: [Redshift service entity](jdbcconnection-definitions-jdbcinfo.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/jdbc")

### jdbc Type

`object` ([Details](jdbcconnection-definitions-jdbcinfo.md))
