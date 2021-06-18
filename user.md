# User entity Schema

```txt
https://streaminlinedata.ai/entity/team/user.json
```

User entity that is part of an organization

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [user.json](user.md "open original schema") |

## User entity Type

`object` ([User entity](user.md))

# User entity Properties

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                |
| :-------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                   | Not specified | Required | cannot be null | [User entity](user-properties-id.md "https://streaminlinedata.ai/entity/team/user.json#/properties/id")                   |
| [name](#name)               | `string`      | Required | cannot be null | [User entity](user-properties-name.md "https://streaminlinedata.ai/entity/team/user.json#/properties/name")               |
| [displayName](#displayname) | `string`      | Optional | cannot be null | [User entity](user-properties-displayname.md "https://streaminlinedata.ai/entity/team/user.json#/properties/displayName") |
| [href](#href)               | Not specified | Required | cannot be null | [User entity](user-properties-href.md "https://streaminlinedata.ai/entity/team/user.json#/properties/href")               |
| [timezone](#timezone)       | `string`      | Optional | cannot be null | [User entity](user-properties-timezone.md "https://streaminlinedata.ai/entity/team/user.json#/properties/timezone")       |
| [deleted](#deleted)         | `boolean`     | Optional | cannot be null | [User entity](user-properties-deleted.md "https://streaminlinedata.ai/entity/team/user.json#/properties/deleted")         |
| [isBot](#isbot)             | `boolean`     | Optional | cannot be null | [User entity](user-properties-isbot.md "https://streaminlinedata.ai/entity/team/user.json#/properties/isBot")             |
| [profile](#profile)         | Not specified | Optional | cannot be null | [User entity](user-properties-profile.md "https://streaminlinedata.ai/entity/team/user.json#/properties/profile")         |
| [teams](#teams)             | `array`       | Optional | cannot be null | [User entity](user-properties-teams.md "https://streaminlinedata.ai/entity/team/user.json#/properties/teams")             |

## id

Unique identifier that identifies an entity instance

`id`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [User entity](user-properties-id.md "https://streaminlinedata.ai/entity/team/user.json#/properties/id")

### id Type

unknown

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

`href`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [User entity](user-properties-href.md "https://streaminlinedata.ai/entity/team/user.json#/properties/href")

### href Type

unknown

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



`profile`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [User entity](user-properties-profile.md "https://streaminlinedata.ai/entity/team/user.json#/properties/profile")

### profile Type

unknown

## teams

Teams that the user belongs to

`teams`

*   is optional

*   Type: `object[]` ([Team entity](team.md))

*   cannot be null

*   defined in: [User entity](user-properties-teams.md "https://streaminlinedata.ai/entity/team/user.json#/properties/teams")

### teams Type

`object[]` ([Team entity](team.md))
