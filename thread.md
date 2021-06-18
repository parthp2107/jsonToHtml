# Feed entity Schema

```txt
https://streaminlinedata.ai/entity/thread.json
```

Entity that represents a feed

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | Yes        | Unknown status | No           | Forbidden         | Allowed               | none                | [thread.json](thread.md "open original schema") |

## Feed entity Type

`object` ([Feed entity](thread.md))

# Feed entity Properties

| Property              | Type          | Required | Nullable       | Defined by                                                                                                         |
| :-------------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------- |
| [id](#id)             | Not specified | Required | cannot be null | [Feed entity](thread-properties-id.md "https://streaminlinedata.ai/entity/thread.json#/properties/id")             |
| [href](#href)         | Not specified | Optional | cannot be null | [Feed entity](thread-properties-href.md "https://streaminlinedata.ai/entity/thread.json#/properties/href")         |
| [threadTs](#threadts) | Not specified | Optional | cannot be null | [Feed entity](thread-properties-threadts.md "https://streaminlinedata.ai/entity/thread.json#/properties/threadTs") |
| [toEntity](#toentity) | Not specified | Required | cannot be null | [Feed entity](thread-properties-toentity.md "https://streaminlinedata.ai/entity/thread.json#/properties/toEntity") |
| [posts](#posts)       | `array`       | Required | cannot be null | [Feed entity](thread-properties-posts.md "https://streaminlinedata.ai/entity/thread.json#/properties/posts")       |

## id

Unique identifier that identifies an entity instance

`id`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Feed entity](thread-properties-id.md "https://streaminlinedata.ai/entity/thread.json#/properties/id")

### id Type

unknown

## href

Link to the resource corresponding to this entity

`href`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Feed entity](thread-properties-href.md "https://streaminlinedata.ai/entity/thread.json#/properties/href")

### href Type

unknown

## threadTs

Timestamp of the when the first post created the thread

`threadTs`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Feed entity](thread-properties-threadts.md "https://streaminlinedata.ai/entity/thread.json#/properties/threadTs")

### threadTs Type

unknown

### threadTs Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## toEntity

Entity for which this thread is created

`toEntity`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Feed entity](thread-properties-toentity.md "https://streaminlinedata.ai/entity/thread.json#/properties/toEntity")

### toEntity Type

unknown

## posts



`posts`

*   is required

*   Type: `object[]` ([Details](thread-definitions-post.md))

*   cannot be null

*   defined in: [Feed entity](thread-properties-posts.md "https://streaminlinedata.ai/entity/thread.json#/properties/posts")

### posts Type

`object[]` ([Details](thread-definitions-post.md))

# Feed entity Definitions

## Definitions group post

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/entity/thread.json#/definitions/post"}
```

| Property            | Type          | Required | Nullable       | Defined by                                                                                                                                         |
| :------------------ | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| [message](#message) | `string`      | Required | cannot be null | [Feed entity](thread-definitions-post-properties-message.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/message") |
| [postTs](#postts)   | `string`      | Optional | cannot be null | [Feed entity](thread-definitions-post-properties-postts.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/postTs")   |
| [from](#from)       | Not specified | Required | cannot be null | [Feed entity](thread-definitions-post-properties-from.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/from")       |

### message

Message in the post

`message`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Feed entity](thread-definitions-post-properties-message.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/message")

#### message Type

`string`

### postTs

Timestamp of the post

`postTs`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Feed entity](thread-definitions-post-properties-postts.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/postTs")

#### postTs Type

`string`

#### postTs Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

### from

ID of User (regular user or bot) posting the message

`from`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Feed entity](thread-definitions-post-properties-from.md "https://streaminlinedata.ai/entity/thread.json#/definitions/post/properties/from")

#### from Type

unknown
