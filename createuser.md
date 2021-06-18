# Request to create User entity Schema

```txt
https://streaminlinedata.ai/api/team/createUser.json
```

Request to create User entity

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [createUser.json](../out/schema/api/teams/createUser.json "open original schema") |

## Request to create User entity Type

`object` ([Request to create User entity](createuser.md))

# Request to create User entity Properties

| Property                    | Type      | Required | Nullable       | Defined by                                                                                                                                           |
| :-------------------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)               | `string`  | Required | cannot be null | [Request to create User entity](createuser-properties-name.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/name")               |
| [displayName](#displayname) | `string`  | Optional | cannot be null | [Request to create User entity](createuser-properties-displayname.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/displayName") |
| [timezone](#timezone)       | `string`  | Optional | cannot be null | [Request to create User entity](createuser-properties-timezone.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/timezone")       |
| [isBot](#isbot)             | `boolean` | Optional | cannot be null | [Request to create User entity](createuser-properties-isbot.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/isBot")             |
| [profile](#profile)         | `object`  | Optional | cannot be null | [Request to create User entity](common-definitions-profile.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/profile")            |
| [teams](#teams)             | `array`   | Optional | cannot be null | [Request to create User entity](createuser-properties-teams.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/teams")             |

## name

Unique name of the user

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Request to create User entity](createuser-properties-name.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/name")

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

*   defined in: [Request to create User entity](createuser-properties-displayname.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/displayName")

### displayName Type

`string`

## timezone

Timezone of the user

`timezone`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Request to create User entity](createuser-properties-timezone.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/timezone")

### timezone Type

`string`

### timezone Constraints

**unknown format**: the value of this string must follow the format: `timezone`

## isBot



`isBot`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Request to create User entity](createuser-properties-isbot.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/isBot")

### isBot Type

`boolean`

## profile



> Profile of a user, team, or an organization

`profile`

*   is optional

*   Type: `object` ([Details](common-definitions-profile.md))

*   cannot be null

*   defined in: [Request to create User entity](common-definitions-profile.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/profile")

### profile Type

`object` ([Details](common-definitions-profile.md))

## teams

Teams that the user belongs to

`teams`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Request to create User entity](createuser-properties-teams.md "https://streaminlinedata.ai/api/team/createUser.json#/properties/teams")

### teams Type

`string[]`
