---
layout: default
---

# Untitled string in Create Database service entity request Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/api/services/createDatabaseService.json#/properties/serviceType
```

Type of database service such as MySQL, BigQuery, Snowflake, Redshift...

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | Unknown identifiability | Forbidden | Allowed | none | [createDatabaseService.json\*](https://github.com/parthp2107/JsonMd/tree/7c007d55cf8a594dae64d75ff2874e8f1bc91e95/services/createDatabaseService.json) |

## serviceType Type

`string`

## serviceType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"BIGQUERY"` |  |
| `"MYSQL"` |  |
| `"REDSHIFT"` |  |
| `"SNOWFLAKE"` |  |

