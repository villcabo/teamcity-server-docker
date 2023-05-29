# Teamcity Server

Deploy team city server using docker compose

#### Run:

```
docker compose up -d
```

#### Stop:

```
docker compose down
```

## Environments

```
TEAMCITY_VERSION=latest
TEAMCITY_PORT=0.0.0.0:8111

POSTGRES_PORT=0.0.0.0:5432
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
```

# Agents

It is better to install the agents manually https://www.jetbrains.com/help/teamcity/2023.05/install-teamcity-agent.html