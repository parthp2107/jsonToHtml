# Bot entity Schema

```txt
https://streaminlinedata.ai/entity/bots.json
```

Bot entity to capture the details of a bot

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [bots.json](../out/schema/entity/bots.json "open original schema") |

## Bot entity Type

`object` ([Bot entity](bots.md))

# Bot entity Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                          |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                   | `string` | Optional | cannot be null | [Bot entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/bots.json#/properties/id")              |
| [name](#name)               | `string` | Optional | cannot be null | [Bot entity](bots-properties-name.md "https://streaminlinedata.ai/entity/bots.json#/properties/name")               |
| [displayName](#displayname) | `string` | Optional | cannot be null | [Bot entity](bots-properties-displayname.md "https://streaminlinedata.ai/entity/bots.json#/properties/displayName") |
| [description](#description) | `string` | Optional | cannot be null | [Bot entity](bots-properties-description.md "https://streaminlinedata.ai/entity/bots.json#/properties/description") |
| [href](#href)               | `string` | Optional | cannot be null | [Bot entity](common-definitions-href.md "https://streaminlinedata.ai/entity/bots.json#/properties/href")            |

## id

Unique id used to identify an entity

`id`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bot entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/bots.json#/properties/id")

### id Type

`string`

### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122 "check the specification")

## name

Optional name that identifies this entity. Same as id if name is not available

`name`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bot entity](bots-properties-name.md "https://streaminlinedata.ai/entity/bots.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## displayName

Name used for display purposes. Example 'FirstName LastName'

`displayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bot entity](bots-properties-displayname.md "https://streaminlinedata.ai/entity/bots.json#/properties/displayName")

### displayName Type

`string`

## description

Description of entity instance.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bot entity](bots-properties-description.md "https://streaminlinedata.ai/entity/bots.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

> Link to the resource

`href`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bot entity](common-definitions-href.md "https://streaminlinedata.ai/entity/bots.json#/properties/href")

### href Type

`string`

### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")
