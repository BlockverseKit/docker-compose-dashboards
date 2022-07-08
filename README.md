# Docker compose of questdb, metabase and n8n.
Docker compose of the  back-end: questdb, metabase and n8n. To spin up the dev environment steadily across core team and contributors.

 * docker-compose up -d


## Resources:

QUESTDB. Time series data db based on postgresql

[Docs](https://questdb.io/docs)


METABASE. Dashboard platform.

[Docs](https://www.metabase.com/docs/latest/)


N8N. Automation node platform.

[Docs](https://docs.n8n.io/)


### Hard testing for full workflows.


In a nutshell:

Example 1. Create a db, with tables, inject data with n8n to questdb, connect questdb to metabase for dashboard display, add iframe to webpage.


### Tips:

1. Adapt the env files to your use case.
2. Never upload your env files with final values.
3. Create config folder for your environment and env files.

#### Deployments:
At Digital Ocean with droplets.


*Blockversekit developers.*