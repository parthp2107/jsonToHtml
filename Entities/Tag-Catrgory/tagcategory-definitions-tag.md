---
layout: default
---

# tagcategory-definitions-tag

## Untitled undefined type in Types related to tag category Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/tags/tagCategory.md#/properties/children/items
```

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Forbidden | none | [tagCategory.json\*](tagcategory.md) |

### items Type

unknown

## items Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [name](tagcategory-definitions-tag.md#name) | `string` | Required | cannot be null | [Types related to tag category](tagcategory-definitions-tagname.md) |
| [fullyQualifiedName](tagcategory-definitions-tag.md#fullyqualifiedname) | `string` | Optional | cannot be null | [Types related to tag category](tagcategory-definitions-tag-properties-fullyqualifiedname.md) |
| [description](tagcategory-definitions-tag.md#description) | `string` | Required | cannot be null | [Types related to tag category](tagcategory-definitions-tag-properties-description.md) |
| [href](tagcategory-definitions-tag.md#href) | `string` | Optional | cannot be null | [Types related to tag category](../../Types/Common/common-definitions-href.md) |
| [deprecated](tagcategory-definitions-tag.md#deprecated) | `boolean` | Optional | cannot be null | [Types related to tag category](tagcategory-definitions-tag-properties-deprecated.md) |
| [tags](tagcategory-definitions-tag.md#tags) | `array` | Optional | cannot be null | [Types related to tag category](tagcategory-definitions-tag-properties-tags.md) |
| [children](tagcategory-definitions-tag.md#children) | `array` | Optional | cannot be null | [Types related to tag category](tagcategory-definitions-tag-properties-children.md) |

### name

Name of the tag

`name`

* is required
* Type: `string`
* cannot be null
* defined in: [Types related to tag category](tagcategory-definitions-tagname.md)

#### name Type

`string`

#### name Constraints

**maximum length**: the maximum number of characters for this string is: `25`

**minimum length**: the minimum number of characters for this string is: `2`

### fullyQualifiedName

Unique name of the tag of format Category.PrimaryTag.SecondaryTag

`fullyQualifiedName`

* is optional
* Type: `string`
* cannot be null
* defined in: [Types related to tag category](tagcategory-definitions-tag-properties-fullyqualifiedname.md)

#### fullyQualifiedName Type

`string`

### description

Unique name of the tag category

`description`

* is required
* Type: `string`
* cannot be null
* defined in: [Types related to tag category](tagcategory-definitions-tag-properties-description.md)

#### description Type

`string`

### href

Link to the resource corresponding to the tag

> Link to the resource

`href`

* is optional
* Type: `string`
* cannot be null
* defined in: [Types related to tag category](../../Types/Common/common-definitions-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

### deprecated

If the tag is deprecated

`deprecated`

* is optional
* Type: `boolean`
* cannot be null
* defined in: [Types related to tag category](tagcategory-definitions-tag-properties-deprecated.md)

#### deprecated Type

`boolean`

### tags

Fully qualified names of tags associated with this tag

`tags`

* is optional
* Type: `string[]`
* cannot be null
* defined in: [Types related to tag category](tagcategory-definitions-tag-properties-tags.md)

#### tags Type

`string[]`

### children

Tags under this tag group or empty for tags at leaf level

`children`

* is optional
* Type: unknown\[\]
* cannot be null
* defined in: [Types related to tag category](tagcategory-definitions-tag-properties-children.md)

#### children Type

unknown\[\]

