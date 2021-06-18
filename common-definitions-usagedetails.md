# Untitled object in Table entity Schema

```txt
https://streaminlinedata.ai/entity/data/table.json#/properties/usageSummary
```

Latest usage information for this table

> Type used to return usage details

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [table.json*](../out/schema/entity/data/table.json "open original schema") |

## usageSummary Type

`object` ([Details](common-definitions-usagedetails.md))

# usageSummary Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                        |
| :---------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| [dailyStats](#dailystats)     | `object` | Required | cannot be null | [Common types](common-definitions-usagestats.md "https://streaminlinedata.ai/type/common.json#/definitions/usageDetails/properties/dailyStats")   |
| [weeklyStats](#weeklystats)   | `object` | Optional | cannot be null | [Common types](common-definitions-usagestats.md "https://streaminlinedata.ai/type/common.json#/definitions/usageDetails/properties/weeklyStats")  |
| [monthlyStats](#monthlystats) | `object` | Optional | cannot be null | [Common types](common-definitions-usagestats.md "https://streaminlinedata.ai/type/common.json#/definitions/usageDetails/properties/monthlyStats") |
| [date](#date)                 | `string` | Required | cannot be null | [Common types](common-definitions-date.md "https://streaminlinedata.ai/type/common.json#/definitions/usageDetails/properties/date")               |

## dailyStats



> Type used to return usage statistics

`dailyStats`

*   is required

*   Type: `object` ([Details](common-definitions-usagestats.md))

*   cannot be null

*   defined in: [Common types](common-definitions-usagestats.md "https://streaminlinedata.ai/type/common.json#/definitions/usageDetails/properties/dailyStats")

### dailyStats Type

`object` ([Details](common-definitions-usagestats.md))

## weeklyStats



> Type used to return usage statistics

`weeklyStats`

*   is optional

*   Type: `object` ([Details](common-definitions-usagestats.md))

*   cannot be null

*   defined in: [Common types](common-definitions-usagestats.md "https://streaminlinedata.ai/type/common.json#/definitions/usageDetails/properties/weeklyStats")

### weeklyStats Type

`object` ([Details](common-definitions-usagestats.md))

## monthlyStats



> Type used to return usage statistics

`monthlyStats`

*   is optional

*   Type: `object` ([Details](common-definitions-usagestats.md))

*   cannot be null

*   defined in: [Common types](common-definitions-usagestats.md "https://streaminlinedata.ai/type/common.json#/definitions/usageDetails/properties/monthlyStats")

### monthlyStats Type

`object` ([Details](common-definitions-usagestats.md))

## date

Date in ISO 8601 format in UTC time

`date`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Common types](common-definitions-date.md "https://streaminlinedata.ai/type/common.json#/definitions/usageDetails/properties/date")

### date Type

`string`

### date Constraints

**date**: the string must be a date string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
