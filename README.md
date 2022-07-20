`docker-compose up -d --build`

### make sure to replace the ip in the hba.conf file
`docker cp pg_hba.conf postgres-db:/var/lib/postgresql/data/pg_hba.conf docker restart postgres-db`
