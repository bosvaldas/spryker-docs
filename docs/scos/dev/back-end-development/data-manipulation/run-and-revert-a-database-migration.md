---
title: Run and revert a database migration
description: Database migration lets you update your database with the latest changes.
last_updated: Jun 16, 2021
template: howto-guide-template
originalLink: https://documentation.spryker.com/2021080/docs/running-reverting-db-migration
originalArticleId: c4756a6e-9b72-400b-b5f3-a252da857af1
redirect_from:
  - /2021080/docs/running-reverting-db-migration
  - /2021080/docs/en/running-reverting-db-migration
  - /docs/running-reverting-db-migration
  - /docs/en/running-reverting-db-migration
  - /v6/docs/running-reverting-db-migration
  - /v6/docs/en/running-reverting-db-migration
  - /v5/docs/running-reverting-db-migration
  - /v5/docs/en/running-reverting-db-migration
  - /v4/docs/running-reverting-db-migration
  - /v4/docs/en/running-reverting-db-migration
  - /v3/docs/running-reverting-db-migration
  - /v3/docs/en/running-reverting-db-migration
  - /v2/docs/running-reverting-db-migration
  - /v2/docs/en/running-reverting-db-migration
  - /v1/docs/running-reverting-db-migration
  - /v1/docs/en/running-reverting-db-migration
  - /docs/scos/dev/back-end-development/data-manipulation/running-and-reverting-a-database-migration.html
---

Database migration lets you update your database with the latest changes.

View the list of all the commands related to the migration process:

```bash
vendor/bin/propel list
```

Revert the database migration:

```bash
vendor/bin/propel migration:down --config-dir=src/Orm/Propel/STORE/Config/development
```