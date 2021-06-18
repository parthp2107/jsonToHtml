# Redshift service entity Schema

```txt
https://streaminlinedata.ai/entity/services/redshift.json
```

Schema corresponding to Redshift service entity

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                            |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [redshift.json](redshift.md "open original schema") |

## Redshift service entity Type

`object` ([Redshift service entity](redshift.md))

# Redshift service entity Properties

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                                        |
| :-------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                   | Not specified | Optional | cannot be null | [Redshift service entity](redshift-properties-id.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/id")                   |
| [name](#name)               | `string`      | Required | cannot be null | [Redshift service entity](redshift-properties-name.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/name")               |
| [description](#description) | `string`      | Optional | cannot be null | [Redshift service entity](redshift-properties-description.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/description") |
| [href](#href)               | Not specified | Required | cannot be null | [Redshift service entity](redshift-properties-href.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/href")               |
| [jdbc](#jdbc)               | Not specified | Optional | cannot be null | [Redshift service entity](redshift-properties-jdbc.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/jdbc")               |

## id

Unique identifier that identifies an entity instance

`id`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Redshift service entity](redshift-properties-id.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/id")

### id Type

unknown

## name

Unique name for a redshift cluster. Example: westcoast-prod1

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Redshift service entity](redshift-properties-name.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## description

Description of entity instance.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Redshift service entity](redshift-properties-description.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

`href`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Redshift service entity](redshift-properties-href.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/href")

### href Type

unknown

## jdbc



`jdbc`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Redshift service entity](redshift-properties-jdbc.md "https://streaminlinedata.ai/entity/services/redshift.json#/properties/jdbc")

### jdbc Type

unknown
