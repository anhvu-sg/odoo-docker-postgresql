# Start docker

```
docker-compose up -d
```

# Install latest posgreql-client: _(Fixing pg_dump Error while running backup)_

```
echo "deb http://apt.postgresql.org/pub/repos/apt/ $(lsb_release -cs)-pgdg main 11" | sudo tee /etc/apt/sources.list.d/pgsql.list

wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -

sudo apt update && sudo apt install postgresql-11
```