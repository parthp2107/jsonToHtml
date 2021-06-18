# Team entity Schema

```txt
https://streaminlinedata.ai/entity/team/team.json
```

Team entity

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [team.json](team.md "open original schema") |

## Team entity Type

`object` ([Team entity](team.md))

# Team entity Properties

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                |
| :-------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                   | Not specified | Required | cannot be null | [Team entity](team-properties-id.md "https://streaminlinedata.ai/entity/team/team.json#/properties/id")                   |
| [name](#name)               | `string`      | Required | cannot be null | [Team entity](team-properties-name.md "https://streaminlinedata.ai/entity/team/team.json#/properties/name")               |
| [displayName](#displayname) | `string`      | Optional | cannot be null | [Team entity](team-properties-displayname.md "https://streaminlinedata.ai/entity/team/team.json#/properties/displayName") |
| [description](#description) | `string`      | Optional | cannot be null | [Team entity](team-properties-description.md "https://streaminlinedata.ai/entity/team/team.json#/properties/description") |
| [href](#href)               | Not specified | Required | cannot be null | [Team entity](team-properties-href.md "https://streaminlinedata.ai/entity/team/team.json#/properties/href")               |
| [profile](#profile)         | Not specified | Optional | cannot be null | [Team entity](team-properties-profile.md "https://streaminlinedata.ai/entity/team/team.json#/properties/profile")         |
| [deleted](#deleted)         | `boolean`     | Optional | cannot be null | [Team entity](team-properties-deleted.md "https://streaminlinedata.ai/entity/team/team.json#/properties/deleted")         |
| [users](#users)             | `array`       | Optional | cannot be null | [Team entity](team-properties-users.md "https://streaminlinedata.ai/entity/team/team.json#/properties/users")             |

## id



`id`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Team entity](team-properties-id.md "https://streaminlinedata.ai/entity/team/team.json#/properties/id")

### id Type

unknown

## name

Unique name that identifies the team

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Team entity](team-properties-name.md "https://streaminlinedata.ai/entity/team/team.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## displayName

Name used for display purposes. Example 'Data Science team'

`displayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Team entity](team-properties-displayname.md "https://streaminlinedata.ai/entity/team/team.json#/properties/displayName")

### displayName Type

`string`

## description

Description of the team

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Team entity](team-properties-description.md "https://streaminlinedata.ai/entity/team/team.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

`href`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Team entity](team-properties-href.md "https://streaminlinedata.ai/entity/team/team.json#/properties/href")

### href Type

unknown

## profile

Team profile information

`profile`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Team entity](team-properties-profile.md "https://streaminlinedata.ai/entity/team/team.json#/properties/profile")

### profile Type

unknown

## deleted



`deleted`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Team entity](team-properties-deleted.md "https://streaminlinedata.ai/entity/team/team.json#/properties/deleted")

### deleted Type

`boolean`

## users

Users that are part of the team

`users`

*   is optional

*   Type: `object[]` ([User entity](user.md))

*   cannot be null

*   defined in: [Team entity](team-properties-users.md "https://streaminlinedata.ai/entity/team/team.json#/properties/users")

### users Type

`object[]` ([User entity](user.md))
