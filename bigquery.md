# BigQuery service entity Schema

```txt
https://streaminlinedata.ai/entity/services/bigQuery.json
```

Schema corresponding to BigQuery service entity

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                            |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [bigQuery.json](bigquery.md "open original schema") |

## BigQuery service entity Type

`object` ([BigQuery service entity](bigquery.md))

# BigQuery service entity Properties

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                                        |
| :-------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                   | Not specified | Optional | cannot be null | [BigQuery service entity](bigquery-properties-id.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/id")                   |
| [name](#name)               | `string`      | Required | cannot be null | [BigQuery service entity](bigquery-properties-name.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/name")               |
| [description](#description) | `string`      | Optional | cannot be null | [BigQuery service entity](bigquery-properties-description.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/description") |
| [href](#href)               | Not specified | Required | cannot be null | [BigQuery service entity](bigquery-properties-href.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/href")               |
| [jdbc](#jdbc)               | Not specified | Optional | cannot be null | [BigQuery service entity](bigquery-properties-jdbc.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/jdbc")               |

## id

Unique identifier that identifies an entity instance

`id`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [BigQuery service entity](bigquery-properties-id.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/id")

### id Type

unknown

## name

Name that identifies the this entity instance uniquely. Same as id if when name is not unique

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [BigQuery service entity](bigquery-properties-name.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/name")

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

*   defined in: [BigQuery service entity](bigquery-properties-description.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

`href`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [BigQuery service entity](bigquery-properties-href.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/href")

### href Type

unknown

## jdbc



`jdbc`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [BigQuery service entity](bigquery-properties-jdbc.md "https://streaminlinedata.ai/entity/services/bigQuery.json#/properties/jdbc")

### jdbc Type

unknown
