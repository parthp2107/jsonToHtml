# common-definitions-profile

### layout: default

## Untitled object in Request to create User entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/api/teams/createUser.json#/properties/profile
```

> Profile of a user, team, or an organization

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [createUser.json\*](https://github.com/parthp2107/JsonMd/tree/7c007d55cf8a594dae64d75ff2874e8f1bc91e95/teams/createUser.json) |

### profile Type

`object` \([Details](common-definitions-profile.md)\)

## profile Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [email](common-definitions-profile.md#email) | `string` | Optional | cannot be null | [Common types](common-definitions-profile-properties-email.md) |
| [images](common-definitions-profile.md#images) | `object` | Optional | cannot be null | [Common types](common-definitions-imagelist.md) |

### email

`email`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-profile-properties-email.md)

#### email Type

`string`

#### email Constraints

**email**: the string must be an email address, according to [RFC 5322, section 3.4.1](https://tools.ietf.org/html/rfc5322)

### images

> Links to list of images of varying resolutions/sizes

`images`

* is optional
* Type: `object` \([Details](common-definitions-imagelist.md)\)
* cannot be null
* defined in: [Common types](common-definitions-imagelist.md)

#### images Type

`object` \([Details](common-definitions-imagelist.md)\)

