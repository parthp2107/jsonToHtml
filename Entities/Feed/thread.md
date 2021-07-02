---
layout: default
title: Thread
---

# thread

## Feed entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/feed/thread.json
```

Entity that represents a feed

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | Yes | Unknown status | No | Forbidden | Allowed | none | [thread.json](thread.md) |

### Feed entity Type

`object` \([Feed entity](thread.md)\)

## Feed entity Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [id](thread.md#id) | `string` | Required | cannot be null | [Feed entity](../../Types/Common/common-definitions-uuid.md) |
| [href](thread.md#href) | `string` | Optional | cannot be null | [Feed entity](../../Types/Common/common-definitions-href.md) |
| [threadTs](thread.md#threadts) | Not specified | Optional | cannot be null | [Feed entity](thread-properties-threadts.md) |
| [toEntity](thread.md#toentity) | `object` | Required | cannot be null | [Feed entity](../../Types/Common/common-definitions-entityreference.md) |
| [posts](thread.md#posts) | `array` | Required | cannot be null | [Feed entity](thread-properties-posts.md) |

### id

Unique id used to identify an entity

`id`

* is required
* Type: `string`
* cannot be null
* defined in: [Feed entity](../../Types/Common/common-definitions-uuid.md)

#### id Type

`string`

#### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

### href

Link to the resource corresponding to this entity

> Link to the resource

`href`

* is optional
* Type: `string`
* cannot be null
* defined in: [Feed entity](../../Types/Common/common-definitions-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

### threadTs

Timestamp of the when the first post created the thread

`threadTs`

* is optional
* Type: unknown
* cannot be null
* defined in: [Feed entity](thread-properties-threadts.md)

#### threadTs Type

unknown

#### threadTs Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

### toEntity

Entity for which this thread is created

> Entity reference that includes entity ID and entity type

`toEntity`

* is required
* Type: `object` \([Details](../../Types/Common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [Feed entity](../../Types/Common/common-definitions-entityreference.md)

#### toEntity Type

`object` \([Details](../../Types/Common/common-definitions-entityreference.md)\)

### posts

`posts`

* is required
* Type: `object[]` \([Details](thread-definitions-post.md)\)
* cannot be null
* defined in: [Feed entity](thread-properties-posts.md)

#### posts Type

`object[]` \([Details](thread-definitions-post.md)\)

## Feed entity Definitions

### Definitions group post

Reference this group by using

```javascript
{"$ref":"https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/feed/thread.json#/definitions/post"}
```

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [message](thread.md#message) | `string` | Required | cannot be null | [Feed entity](thread-definitions-post-properties-message.md) |
| [postTs](thread.md#postts) | `string` | Optional | cannot be null | [Feed entity](thread-definitions-post-properties-postts.md) |
| [from](thread.md#from) | `string` | Required | cannot be null | [Feed entity](../../Types/Common/common-definitions-uuid.md) |

#### message

Message in the post

`message`

* is required
* Type: `string`
* cannot be null
* defined in: [Feed entity](thread-definitions-post-properties-message.md)

**message Type**

`string`

#### postTs

Timestamp of the post

`postTs`

* is optional
* Type: `string`
* cannot be null
* defined in: [Feed entity](thread-definitions-post-properties-postts.md)

**postTs Type**

`string`

**postTs Constraints**

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

#### from

Unique id used to identify an entity

`from`

* is required
* Type: `string`
* cannot be null
* defined in: [Feed entity](../../Types/Common/common-definitions-uuid.md)

**from Type**

`string`

**from Constraints**

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

