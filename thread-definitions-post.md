# Untitled object in Feed entity Schema

```txt
https://streaminlinedata.ai/entity/thread.json#/properties/posts/items
```

Post within a feed

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                              |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [thread.json*](../out/schema/entity/thread.json "open original schema") |

## items Type

`object` ([Details](thread-definitions-post.md))

# items Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                         |
| :------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| [message](#message) | `string` | Required | cannot be null | [Feed entity](thread-definitions-post-properties-message.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/message") |
| [postTs](#postts)   | `string` | Optional | cannot be null | [Feed entity](thread-definitions-post-properties-postts.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/postTs")   |
| [from](#from)       | `string` | Required | cannot be null | [Feed entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/from")                       |

## message

Message in the post

`message`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Feed entity](thread-definitions-post-properties-message.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/message")

### message Type

`string`

## postTs

Timestamp of the post

`postTs`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Feed entity](thread-definitions-post-properties-postts.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/postTs")

### postTs Type

`string`

### postTs Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## from

Unique id used to identify an entity

`from`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Feed entity](common-definitions-uuid.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/from")

### from Type

`string`

### from Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122 "check the specification")
