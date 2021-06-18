# Usage details for an entity class Schema

```txt
https://streaminlinedata.ai/type/categoryUsage.json
```

Type used for capturing usage details of an entity class

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [categoryUsage.json](../out/schema/type/categoryUsage.json "open original schema") |

## Usage details for an entity class Type

unknown ([Usage details for an entity class](categoryusage.md))

# Usage details for an entity class Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                       |
| :---------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| [entity](#entity) | `string` | Optional | cannot be null | [Usage details for an entity class](categoryusage-properties-entity.md "https://streaminlinedata.ai/type/categoryUsage.json#/properties/entity") |
| [usage](#usage)   | `array`  | Required | cannot be null | [Usage details for an entity class](categoryusage-properties-usage.md "https://streaminlinedata.ai/type/categoryUsage.json#/properties/usage")   |

## entity

Name of the entity class for which usage is returned

`entity`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Usage details for an entity class](categoryusage-properties-entity.md "https://streaminlinedata.ai/type/categoryUsage.json#/properties/entity")

### entity Type

`string`

## usage

List usage details per day

`usage`

*   is required

*   Type: `object[]` ([Details](common-definitions-usagedetails.md))

*   cannot be null

*   defined in: [Usage details for an entity class](categoryusage-properties-usage.md "https://streaminlinedata.ai/type/categoryUsage.json#/properties/usage")

### usage Type

`object[]` ([Details](common-definitions-usagedetails.md))
