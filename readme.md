# Teamcity Server

Deploy team city server using docker compose

## Previous step

```
sudo chown -R 1000:1000 teamcity-server-logs
```

### Run:

```
docker compose up -d
```

### Stop:

```
docker compose down
```

## Environments

```
TEAMCITY_VERSION=2023.05
TEAMCITY_CONTEXT=/teamcity/
TEAMCITY_PORT=0.0.0.0:8111

POSTGRES_PORT=0.0.0.0:5432
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
POSTGRES_DB=teamcity_db
```
