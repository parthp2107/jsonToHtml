# User entity Schema

```txt
https://streaminlinedata.ai/entity/team/user.json
```

User entity that is part of an organization

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [user.json](../out/schema/entity/teams/user.json "open original schema") |

## User entity Type

`object` ([User entity](user.md))

# User entity Properties

| Property                    | Type      | Required | Nullable       | Defined by                                                                                                                |
| :-------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                   | `string`  | Required | cannot be null | [User entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/team/user.json#/properties/id")              |
| [name](#name)               | `string`  | Required | cannot be null | [User entity](user-properties-name.md "https://streaminlinedata.ai/entity/team/user.json#/properties/name")               |
| [displayName](#displayname) | `string`  | Optional | cannot be null | [User entity](user-properties-displayname.md "https://streaminlinedata.ai/entity/team/user.json#/properties/displayName") |
| [href](#href)               | `string`  | Required | cannot be null | [User entity](common-definitions-href.md "https://streaminlinedata.ai/entity/team/user.json#/properties/href")            |
| [timezone](#timezone)       | `string`  | Optional | cannot be null | [User entity](user-properties-timezone.md "https://streaminlinedata.ai/entity/team/user.json#/properties/timezone")       |
| [deleted](#deleted)         | `boolean` | Optional | cannot be null | [User entity](user-properties-deleted.md "https://streaminlinedata.ai/entity/team/user.json#/properties/deleted")         |
| [isBot](#isbot)             | `boolean` | Optional | cannot be null | [User entity](user-properties-isbot.md "https://streaminlinedata.ai/entity/team/user.json#/properties/isBot")             |
| [profile](#profile)         | `object`  | Optional | cannot be null | [User entity](common-definitions-profile.md "https://streaminlinedata.ai/entity/team/user.json#/properties/profile")      |
| [teams](#teams)             | `array`   | Optional | cannot be null | [User entity](user-properties-teams.md "https://streaminlinedata.ai/entity/team/user.json#/properties/teams")             |

## id

Unique id used to identify an entity

`id`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [User entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/team/user.json#/properties/id")

### id Type

`string`

### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122 "check the specification")

## name

Name that identifies the this entity instance uniquely. Same as id if when name is not unique

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [User entity](user-properties-name.md "https://streaminlinedata.ai/entity/team/user.json#/properties/name")

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

*   defined in: [User entity](user-properties-displayname.md "https://streaminlinedata.ai/entity/team/user.json#/properties/displayName")

### displayName Type

`string`

## href

Link to the resource corresponding to this entity

> Link to the resource

`href`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [User entity](common-definitions-href.md "https://streaminlinedata.ai/entity/team/user.json#/properties/href")

### href Type

`string`

### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

## timezone

Timezone of the user

`timezone`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [User entity](user-properties-timezone.md "https://streaminlinedata.ai/entity/team/user.json#/properties/timezone")

### timezone Type

`string`

### timezone Constraints

**unknown format**: the value of this string must follow the format: `timezone`

## deleted



`deleted`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [User entity](user-properties-deleted.md "https://streaminlinedata.ai/entity/team/user.json#/properties/deleted")

### deleted Type

`boolean`

## isBot



`isBot`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [User entity](user-properties-isbot.md "https://streaminlinedata.ai/entity/team/user.json#/properties/isBot")

### isBot Type

`boolean`

## profile



> Profile of a user, team, or an organization

`profile`

*   is optional

*   Type: `object` ([Details](common-definitions-profile.md))

*   cannot be null

*   defined in: [User entity](common-definitions-profile.md "https://streaminlinedata.ai/entity/team/user.json#/properties/profile")

### profile Type

`object` ([Details](common-definitions-profile.md))

## teams

Teams that the user belongs to

`teams`

*   is optional

*   Type: `object[]` ([Team entity](team.md))

*   cannot be null

*   defined in: [User entity](user-properties-teams.md "https://streaminlinedata.ai/entity/team/user.json#/properties/teams")

### teams Type

`object[]` ([Team entity](team.md))
