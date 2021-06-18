# JDBC connection Schema

```txt
https://streaminlinedata.ai/type/jdbcConnection.json
```

JDBC connection information used for connecting to a database system

> JDBC connection information

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------- |
| Can be instantiated | Yes        | Unknown status | No           | Forbidden         | Allowed               | none                | [jdbcConnection.json](../out/schema/type/jdbcConnection.json "open original schema") |

## JDBC connection Type

`object` ([JDBC connection](jdbcconnection.md))

# JDBC connection Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                     |
| :------------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------- |
| [driverClass](#driverclass)     | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-properties-driverclass.md "https://streaminlinedata.ai/type/jdbcConnection.json#/properties/driverClass")     |
| [connectionUrl](#connectionurl) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-properties-connectionurl.md "https://streaminlinedata.ai/type/jdbcConnection.json#/properties/connectionUrl") |
| [userName](#username)           | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-properties-username.md "https://streaminlinedata.ai/type/jdbcConnection.json#/properties/userName")           |
| [password](#password)           | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-properties-password.md "https://streaminlinedata.ai/type/jdbcConnection.json#/properties/password")           |

## driverClass



> Type used for JDBC driver class

`driverClass`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JDBC connection](jdbcconnection-properties-driverclass.md "https://streaminlinedata.ai/type/jdbcConnection.json#/properties/driverClass")

### driverClass Type

`string`

## connectionUrl



> Type used for JDBC connection URL

`connectionUrl`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JDBC connection](jdbcconnection-properties-connectionurl.md "https://streaminlinedata.ai/type/jdbcConnection.json#/properties/connectionUrl")

### connectionUrl Type

`string`

### connectionUrl Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

## userName

Login user name

`userName`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JDBC connection](jdbcconnection-properties-username.md "https://streaminlinedata.ai/type/jdbcConnection.json#/properties/userName")

### userName Type

`string`

## password

Login password

`password`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JDBC connection](jdbcconnection-properties-password.md "https://streaminlinedata.ai/type/jdbcConnection.json#/properties/password")

### password Type

`string`

# JDBC connection Definitions

## Definitions group driverClass

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/driverClass"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group connectionUrl

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/connectionUrl"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group jdbcInfo

Reference this group by using

```json
{"$ref":"https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                               |
| :-------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [driverClass](#driverclass-1)     | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-definitions-jdbcinfo-properties-driverclass.md "https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo/properties/driverClass")     |
| [connectionUrl](#connectionurl-1) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-definitions-jdbcinfo-properties-connectionurl.md "https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo/properties/connectionUrl") |

### driverClass



> Type used for JDBC driver class

`driverClass`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JDBC connection](jdbcconnection-definitions-jdbcinfo-properties-driverclass.md "https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo/properties/driverClass")

#### driverClass Type

`string`

#### driverClass Default Value

The default value is:

```json
"com.amazon.redshift.jdbc42.Driver"
```

### connectionUrl



> Type used for JDBC connection URL

`connectionUrl`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JDBC connection](jdbcconnection-definitions-jdbcinfo-properties-connectionurl.md "https://streaminlinedata.ai/type/jdbcConnection.json#/definitions/jdbcInfo/properties/connectionUrl")

#### connectionUrl Type

`string`

#### connectionUrl Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")
