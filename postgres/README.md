This is a sample postgres docker compose file.

to start it as a daemon:

`docker-compose up -d`

Here is the command to connect to the database:

`psql postgres://postgres:postgres@localhost:54320`

Note it is `\q` to quit

Notice that the port definition is host:container
