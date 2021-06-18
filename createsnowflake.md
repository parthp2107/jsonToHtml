# Create Snowflake service entity request Schema

```txt
https://streaminlinedata.ai/entity/services/createSnowflake.json
```

Create Snowflake service entity request

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [createSnowflake.json](../out/schema/api/services/createSnowflake.json "open original schema") |

## Create Snowflake service entity request Type

`object` ([Create Snowflake service entity request](createsnowflake.md))

# Create Snowflake service entity request Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                      |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [name](#name)               | `string` | Required | cannot be null | [Create Snowflake service entity request](createsnowflake-properties-name.md "https://streaminlinedata.ai/entity/services/createSnowflake.json#/properties/name")               |
| [description](#description) | `string` | Optional | cannot be null | [Create Snowflake service entity request](createsnowflake-properties-description.md "https://streaminlinedata.ai/entity/services/createSnowflake.json#/properties/description") |
| [jdbc](#jdbc)               | `object` | Required | cannot be null | [Create Snowflake service entity request](jdbcconnection-definitions-jdbcinfo.md "https://streaminlinedata.ai/entity/services/createSnowflake.json#/properties/jdbc")           |

## name

Name that identifies the this entity instance uniquely

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Create Snowflake service entity request](createsnowflake-properties-name.md "https://streaminlinedata.ai/entity/services/createSnowflake.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## description

Description of Snowflake instance.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Create Snowflake service entity request](createsnowflake-properties-description.md "https://streaminlinedata.ai/entity/services/createSnowflake.json#/properties/description")

### description Type

`string`

## jdbc



> Type for capturing JDBC connector information

`jdbc`

*   is required

*   Type: `object` ([Details](jdbcconnection-definitions-jdbcinfo.md))

*   cannot be null

*   defined in: [Create Snowflake service entity request](jdbcconnection-definitions-jdbcinfo.md "https://streaminlinedata.ai/entity/services/createSnowflake.json#/properties/jdbc")

### jdbc Type

`object` ([Details](jdbcconnection-definitions-jdbcinfo.md))
