---
layout: default
---

# common-definitions-schedule

## Untitled object in Update Database service entity request Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/api/services/updateDatabaseService.json#/properties/ingestionSchedule
```

Schedule for running metadata ingestion jobs

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [updateDatabaseService.json\*](https://github.com/parthp2107/JsonMd/tree/7c007d55cf8a594dae64d75ff2874e8f1bc91e95/services/updateDatabaseService.json) |

### ingestionSchedule Type

`object` \([Details](common-definitions-schedule.md)\)

## ingestionSchedule Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [startDate](common-definitions-schedule.md#startdate) | `string` | Optional | cannot be null | [Common types](common-definitions-datetime.md) |
| [repeatFrequency](common-definitions-schedule.md#repeatfrequency) | `string` | Optional | cannot be null | [Common types](common-definitions-duration.md) |

### startDate

Date and time in ISO 8601 format. Example - '2018-11-13T20:20:39+00:00'

`startDate`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-datetime.md)

#### startDate Type

`string`

#### startDate Constraints

**unknown format**: the value of this string must follow the format: `date-Time`

### repeatFrequency

Duration in ISO 8601 format in UTC time. Example - 'P23DT23H'

> Jsonschema does not handle ISO 8601 duration yet and hence no format for this type

`repeatFrequency`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-duration.md)

#### repeatFrequency Type

`string`

