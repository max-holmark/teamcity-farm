# TeamCity - Farm

## Description
Deploys TeamCity Server (Ubuntu 20.21) and Agent (Ubuntu 20.21) for the `.Net 5`, `NodeJS 14`, and `Inno Setup` builds.

## How to start
1. Create root folders for the TeamCity
```
sudo mkdir -p /apps/teamcity/data /apps/teamcity/logs /apps/teamcity/agent
```

2. Run command
```
docker-compose -d up
```