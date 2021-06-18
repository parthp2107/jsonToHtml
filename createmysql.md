# Create MySQL service entity request Schema

```txt
https://streaminlinedata.ai/entity/services/createMySQL.json
```

Create MySQL service entity request

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [createMySQL.json](../out/schema/api/services/createMySQL.json "open original schema") |

## Create MySQL service entity request Type

`object` ([Create MySQL service entity request](createmysql.md))

# Create MySQL service entity request Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                          |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [name](#name)               | `string` | Required | cannot be null | [Create MySQL service entity request](createmysql-properties-name.md "https://streaminlinedata.ai/entity/services/createMySQL.json#/properties/name")               |
| [description](#description) | `string` | Optional | cannot be null | [Create MySQL service entity request](createmysql-properties-description.md "https://streaminlinedata.ai/entity/services/createMySQL.json#/properties/description") |
| [jdbc](#jdbc)               | `object` | Required | cannot be null | [Create MySQL service entity request](jdbcconnection-definitions-jdbcinfo.md "https://streaminlinedata.ai/entity/services/createMySQL.json#/properties/jdbc")       |

## name

Name that identifies the this entity instance uniquely

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Create MySQL service entity request](createmysql-properties-name.md "https://streaminlinedata.ai/entity/services/createMySQL.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## description

Description of MySQL instance.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Create MySQL service entity request](createmysql-properties-description.md "https://streaminlinedata.ai/entity/services/createMySQL.json#/properties/description")

### description Type

`string`

## jdbc



> Type for capturing JDBC connector information

`jdbc`

*   is required

*   Type: `object` ([Details](jdbcconnection-definitions-jdbcinfo.md))

*   cannot be null

*   defined in: [Create MySQL service entity request](jdbcconnection-definitions-jdbcinfo.md "https://streaminlinedata.ai/entity/services/createMySQL.json#/properties/jdbc")

### jdbc Type

`object` ([Details](jdbcconnection-definitions-jdbcinfo.md))
