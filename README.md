# Oracle and PostgreSQL DB schema for PanDA and Container image for PandaDB

## Oracle and PostgreSQL DB schema
You can find the database schema within the `schema` folder. Whenever there is a new version of the PanDA DB schema, the version number needs to increase in order to reflect the change. For PostgreSQL you can find the version number in `schema/postgres/version` and for Oracle in `schema/oracle/ATLAS_PANDA.sql`.

Whenever there is a schema change that increases the version number, a diff file needs to be provided for all the schema changes between the previous and current version. At the end of the diff file, we need to also increase the DB schema version number in the `pandadb_version` table.
