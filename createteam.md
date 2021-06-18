# Team entity Schema

```txt
https://streaminlinedata.ai/api/teams/team.json
```

Team entity

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [createTeam.json](../out/schema/api/teams/createTeam.json "open original schema") |

## Team entity Type

`object` ([Team entity](createteam.md))

# Team entity Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                    |
| :-------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)               | `string` | Required | cannot be null | [Team entity](createteam-properties-name.md "https://streaminlinedata.ai/api/teams/team.json#/properties/name")               |
| [displayName](#displayname) | `string` | Optional | cannot be null | [Team entity](createteam-properties-displayname.md "https://streaminlinedata.ai/api/teams/team.json#/properties/displayName") |
| [description](#description) | `string` | Optional | cannot be null | [Team entity](createteam-properties-description.md "https://streaminlinedata.ai/api/teams/team.json#/properties/description") |
| [profile](#profile)         | `object` | Optional | cannot be null | [Team entity](common-definitions-profile.md "https://streaminlinedata.ai/api/teams/team.json#/properties/profile")            |
| [users](#users)             | `array`  | Optional | cannot be null | [Team entity](createteam-properties-users.md "https://streaminlinedata.ai/api/teams/team.json#/properties/users")             |

## name

Unique name that identifies the team

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Team entity](createteam-properties-name.md "https://streaminlinedata.ai/api/teams/team.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## displayName

Optional name used for display purposes. Example 'Marketing Team'

`displayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Team entity](createteam-properties-displayname.md "https://streaminlinedata.ai/api/teams/team.json#/properties/displayName")

### displayName Type

`string`

## description

Optional description of the team

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Team entity](createteam-properties-description.md "https://streaminlinedata.ai/api/teams/team.json#/properties/description")

### description Type

`string`

## profile

Optional team profile information

> Profile of a user, team, or an organization

`profile`

*   is optional

*   Type: `object` ([Details](common-definitions-profile.md))

*   cannot be null

*   defined in: [Team entity](common-definitions-profile.md "https://streaminlinedata.ai/api/teams/team.json#/properties/profile")

### profile Type

`object` ([Details](common-definitions-profile.md))

## users

Optional IDs of users that are part of the team

`users`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Team entity](createteam-properties-users.md "https://streaminlinedata.ai/api/teams/team.json#/properties/users")

### users Type

`string[]`
