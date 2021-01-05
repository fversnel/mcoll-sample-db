# mcoll DB

This repository will be used by the mcoll application server to store
all your database transactions. Since it's just a GitHub repository
you can also access this data yourself.

## The schema

The schema [com.leftfetch.mcoll.schema.edn](com.leftfetch.mcoll.schema.edn) defines the structure of the database, hwich can be used to construct
the datascript database.

## The database transaction log

The [com.leftfetch.mcoll.tx.edn](com.leftfetch.mcoll.tx.edn) contains all the transactions that were applied to the database.
If you want to reconstruct the database apply all the transactions in order
to get to the current database state.

