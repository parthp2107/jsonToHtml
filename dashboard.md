# Dashboard entity Schema

```txt
https://streaminlinedata.ai/entity/data/dashboard.json
```

Entity that represents a Dashboard

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                          |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [dashboard.json](dashboard.md "open original schema") |

## Dashboard entity Type

`object` ([Dashboard entity](dashboard.md))

# Dashboard entity Properties

| Property                                  | Type          | Required | Nullable       | Defined by                                                                                                                                             |
| :---------------------------------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                 | Not specified | Required | cannot be null | [Dashboard entity](dashboard-properties-id.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/id")                                 |
| [name](#name)                             | `string`      | Required | cannot be null | [Dashboard entity](dashboard-properties-name.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/name")                             |
| [fullyQualifiedName](#fullyqualifiedname) | `string`      | Optional | cannot be null | [Dashboard entity](dashboard-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/fullyQualifiedName") |
| [description](#description)               | `string`      | Optional | cannot be null | [Dashboard entity](dashboard-properties-description.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/description")               |
| [href](#href)                             | Not specified | Optional | cannot be null | [Dashboard entity](dashboard-properties-href.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/href")                             |
| [owner](#owner)                           | Not specified | Optional | cannot be null | [Dashboard entity](dashboard-properties-owner.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/owner")                           |
| [service](#service)                       | Not specified | Required | cannot be null | [Dashboard entity](dashboard-properties-service.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/service")                       |
| [usageSummary](#usagesummary)             | Not specified | Optional | cannot be null | [Dashboard entity](dashboard-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/usageSummary")             |

## id

Unique identifier that identifies a dashboard instance

`id`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Dashboard entity](dashboard-properties-id.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/id")

### id Type

unknown

## name

Name that identifies the this dashboard.

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Dashboard entity](dashboard-properties-name.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## fullyQualifiedName

Unique name that identifies a dashboard in the format 'ServiceName.DashboardName'

`fullyQualifiedName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Dashboard entity](dashboard-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/fullyQualifiedName")

### fullyQualifiedName Type

`string`

### fullyQualifiedName Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## description

Description of dashboard, what it is and how to use it.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Dashboard entity](dashboard-properties-description.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this entity

`href`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Dashboard entity](dashboard-properties-href.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/href")

### href Type

unknown

## owner

Owner of this dashboard

`owner`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Dashboard entity](dashboard-properties-owner.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/owner")

### owner Type

unknown

## service

Link to service where this dashboard is hosted in

`service`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Dashboard entity](dashboard-properties-service.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/service")

### service Type

unknown

## usageSummary

Latest usage information for this database

`usageSummary`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Dashboard entity](dashboard-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/dashboard.json#/properties/usageSummary")

### usageSummary Type

unknown
