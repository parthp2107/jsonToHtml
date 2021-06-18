# Untitled object in Common types Schema

```txt
https://streaminlinedata.ai/type/common.json#/definitions/profile
```



> Profile of a user, team, or an organization

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [common.json*](common.md "open original schema") |

## profile Type

`object` ([Details](common-definitions-profile.md))

# profile Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                          |
| :---------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| [email](#email)   | `string` | Optional | cannot be null | [Common types](common-definitions-profile-properties-email.md "https://streaminlinedata.ai/type/common.json#/definitions/profile/properties/email") |
| [images](#images) | `object` | Optional | cannot be null | [Common types](common-definitions-imagelist.md "https://streaminlinedata.ai/type/common.json#/definitions/profile/properties/images")               |

## email



`email`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Common types](common-definitions-profile-properties-email.md "https://streaminlinedata.ai/type/common.json#/definitions/profile/properties/email")

### email Type

`string`

### email Constraints

**email**: the string must be an email address, according to [RFC 5322, section 3.4.1](https://tools.ietf.org/html/rfc5322 "check the specification")

## images



> Links to list of images of varying resolutions/sizes

`images`

*   is optional

*   Type: `object` ([Details](common-definitions-imagelist.md))

*   cannot be null

*   defined in: [Common types](common-definitions-imagelist.md "https://streaminlinedata.ai/type/common.json#/definitions/profile/properties/images")

### images Type

`object` ([Details](common-definitions-imagelist.md))
