Punku
=====

A plugable and configurable authentication and authorization system.

*Do you need to start up a new project and you need an auth layer?* \
Use Punku, connect it to your database and it will handle your `users` (or `account`, event the entity name is configurable) entities.
<br>
<br>
###  Getting started
Update the `template.env` file in `packages/core`. Then execute the following command that will set up everything in docker exposing the graphql engine in `http://localhost:4444/graphql`.

```
yarn workspace core docker:start:dev
```