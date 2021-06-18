# Untitled object in Create Snowflake service entity request Schema

```txt
https://streaminlinedata.ai/entity/services/createSnowflake.json#/properties/jdbc
```



> Type for capturing JDBC connector information

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                      |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [createSnowflake.json*](../out/schema/api/services/createSnowflake.json "open original schema") |

## jdbc Type

`object` ([Details](jdbcconnection-definitions-jdbcinfo.md))

# jdbc Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                           |
| :------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [driverClass](#driverclass)     | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-definitions-driverclass.md "https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo/properties/driverClass")     |
| [connectionUrl](#connectionurl) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-definitions-connectionurl.md "https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo/properties/connectionUrl") |

## driverClass



> Type used for JDBC driver class

`driverClass`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JDBC connection](jdbcconnection-definitions-driverclass.md "https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo/properties/driverClass")

### driverClass Type

`string`

### driverClass Default Value

The default value is:

```json
"com.amazon.redshift.jdbc42.Driver"
```

## connectionUrl



> Type used for JDBC connection URL

`connectionUrl`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JDBC connection](jdbcconnection-definitions-connectionurl.md "https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo/properties/connectionUrl")

### connectionUrl Type

`string`

### connectionUrl Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")
