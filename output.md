# Database entity

*Entity that represents a database*

## Properties

- **`id`**: Unique identifier that identifies this database instance. Refer to *../../type/common.json#/definitions/uuid*.
- **`name`** *(string)*: Name that identifies the database.
- **`fullyQualifiedName`** *(string)*: Name that uniquely identifees a database in the format 'ServiceName.DatabaseName'.
- **`description`** *(string)*: Description of the database instance. What it has and how to use it.
- **`href`**: Link to the resource corresponding to this entity. Refer to *../../type/common.json#/definitions/href*.
- **`owner`**: Owner of this database. Refer to *../../type/common.json#/definitions/entityReference*.
- **`service`**: Link to the database cluster/service where this database is hosted in. Refer to *../../type/common.json#/definitions/entityReference*.
- **`usageSummary`**: Latest usage information for this database. Refer to *../../type/common.json#/definitions/usageDetails*. Default: `None`.
- **`tables`** *(array)*: References to tables in the database. Default: `None`.
  - **Items**: Refer to *../../type/common.json#/definitions/entityReference*.
