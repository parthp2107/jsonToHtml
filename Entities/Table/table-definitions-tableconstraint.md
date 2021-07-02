---
layout: default
---

# table-definitions-tableconstraint

## Untitled object in Table entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/api/data/createTable.json#/properties/tableConstraints/items
```

Table constraint

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [createTable.json\*](https://github.com/parthp2107/JsonMd/tree/7c007d55cf8a594dae64d75ff2874e8f1bc91e95/createTable.json) |

### items Type

`object` \([Details](table-definitions-tableconstraint.md)\)

## items Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [constraintType](table-definitions-tableconstraint.md#constrainttype) | `string` | Optional | cannot be null | [Table entity](table-definitions-tableconstraint-properties-constrainttype.md) |
| [columns](table-definitions-tableconstraint.md#columns) | `array` | Optional | cannot be null | [Table entity](table-definitions-tableconstraint-properties-columns.md) |

### constraintType

`constraintType`

* is optional
* Type: `string`
* cannot be null
* defined in: [Table entity](table-definitions-tableconstraint-properties-constrainttype.md)

#### constraintType Type

`string`

#### constraintType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"UNIQUE"` |  |
| `"PRIMARY_KEY"` |  |
| `"FOREIGN_KEY"` |  |

### columns

List of column names corresponding to the constraint

`columns`

* is optional
* Type: `string[]`
* cannot be null
* defined in: [Table entity](table-definitions-tableconstraint-properties-columns.md)

#### columns Type

`string[]`

