# Alembic

To apply migrations:

```
$ alembic upgrade <ID>
$ alembic upgrade head
$ alembic upgrade +1
```

To revert migrations:

```
$ alembic downgrade <ID>
$ alembic downgrade base
$ alembic downgrade -1
```

To show history:

```
$ alembic history
$ alembic history -i
```

# SQLite3

To create new SQLite3 database:

```
sqlite3 db.db
.databases
.exit
```

To show tables and schema:

```
sqlite3 db.db
.tables
.schema
.exit
```
