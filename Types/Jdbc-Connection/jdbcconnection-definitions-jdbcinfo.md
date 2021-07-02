---
layout: default
---

# jdbcconnection-definitions-jdbcinfo

## Untitled object in Update Database service entity request Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/api/services/updateDatabaseService.json#/properties/jdbc
```

> Type for capturing JDBC connector information

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [updateDatabaseService.json\*](https://github.com/parthp2107/JsonMd/tree/7c007d55cf8a594dae64d75ff2874e8f1bc91e95/services/updateDatabaseService.json) |

### jdbc Type

`object` \([Details](jdbcconnection-definitions-jdbcinfo.md)\)

## jdbc Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [driverClass](jdbcconnection-definitions-jdbcinfo.md#driverclass) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-definitions-driverclass.md) |
| [connectionUrl](jdbcconnection-definitions-jdbcinfo.md#connectionurl) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-definitions-connectionurl.md) |

### driverClass

> Type used for JDBC driver class

`driverClass`

* is required
* Type: `string`
* cannot be null
* defined in: [JDBC connection](jdbcconnection-definitions-driverclass.md)

#### driverClass Type

`string`

#### driverClass Default Value

The default value is:

```javascript
"com.amazon.redshift.jdbc42.Driver"
```

### connectionUrl

> Type used for JDBC connection URL

`connectionUrl`

* is required
* Type: `string`
* cannot be null
* defined in: [JDBC connection](jdbcconnection-definitions-connectionurl.md)

#### connectionUrl Type

`string`

#### connectionUrl Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

