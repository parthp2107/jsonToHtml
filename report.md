# Report entity Schema

```txt
https://streaminlinedata.ai/entity/data/report.json
```

Entity that represents a Report

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                    |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [report.json](../out/data/report.json "open original schema") |

## Report entity Type

`object` ([Report entity](report.md))

# Report entity Properties

| Property                                  | Type          | Required | Nullable       | Defined by                                                                                                                                    |
| :---------------------------------------- | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                 | Not specified | Required | cannot be null | [Report entity](report-properties-id.md "https://streaminlinedata.ai/entity/data/report.json#/properties/id")                                 |
| [name](#name)                             | `string`      | Required | cannot be null | [Report entity](report-properties-name.md "https://streaminlinedata.ai/entity/data/report.json#/properties/name")                             |
| [fullyQualifiedName](#fullyqualifiedname) | `string`      | Optional | cannot be null | [Report entity](report-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/report.json#/properties/fullyQualifiedName") |
| [description](#description)               | `string`      | Optional | cannot be null | [Report entity](report-properties-description.md "https://streaminlinedata.ai/entity/data/report.json#/properties/description")               |
| [href](#href)                             | Not specified | Optional | cannot be null | [Report entity](report-properties-href.md "https://streaminlinedata.ai/entity/data/report.json#/properties/href")                             |
| [owner](#owner)                           | Not specified | Optional | cannot be null | [Report entity](report-properties-owner.md "https://streaminlinedata.ai/entity/data/report.json#/properties/owner")                           |
| [service](#service)                       | Not specified | Required | cannot be null | [Report entity](report-properties-service.md "https://streaminlinedata.ai/entity/data/report.json#/properties/service")                       |
| [usageSummary](#usagesummary)             | Not specified | Optional | cannot be null | [Report entity](report-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/report.json#/properties/usageSummary")             |

## id

Unique identifier that identifies this report

`id`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Report entity](report-properties-id.md "https://streaminlinedata.ai/entity/data/report.json#/properties/id")

### id Type

unknown

## name

Name that identifies the this report instance uniquely.

`name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Report entity](report-properties-name.md "https://streaminlinedata.ai/entity/data/report.json#/properties/name")

### name Type

`string`

### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## fullyQualifiedName

Unique name that identifies a report in the format 'ServiceName.ReportName'

`fullyQualifiedName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Report entity](report-properties-fullyqualifiedname.md "https://streaminlinedata.ai/entity/data/report.json#/properties/fullyQualifiedName")

### fullyQualifiedName Type

`string`

### fullyQualifiedName Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

## description

Description of this report instance.

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Report entity](report-properties-description.md "https://streaminlinedata.ai/entity/data/report.json#/properties/description")

### description Type

`string`

## href

Link to the resource corresponding to this report

`href`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Report entity](report-properties-href.md "https://streaminlinedata.ai/entity/data/report.json#/properties/href")

### href Type

unknown

## owner

Owner of this pipeline

`owner`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Report entity](report-properties-owner.md "https://streaminlinedata.ai/entity/data/report.json#/properties/owner")

### owner Type

unknown

## service

Link to service where this report is hosted in

`service`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Report entity](report-properties-service.md "https://streaminlinedata.ai/entity/data/report.json#/properties/service")

### service Type

unknown

## usageSummary

Latest usage information for this database

`usageSummary`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Report entity](report-properties-usagesummary.md "https://streaminlinedata.ai/entity/data/report.json#/properties/usageSummary")

### usageSummary Type

unknown
