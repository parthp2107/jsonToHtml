# Untitled string in Table entity Schema

```txt
https://streaminlinedata.ai/entity/data/table.json#/properties/tableType
```

Type for capturing a column in a table

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                          |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [createTable.json*](../out/schema/api/data/createTable.json "open original schema") |

## tableType Type

`string`

## tableType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                 | Explanation |
| :-------------------- | :---------- |
| `"REGULAR"`           |             |
| `"EXTERNAL"`          |             |
| `"VIEW"`              |             |
| `"SECURE_VIEW"`       |             |
| `"MATERIALIZED_VIEW"` |             |
