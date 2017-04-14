# Docker recipes

## Entrypoints

Docker entrypoints allow for a powerfull grouping of commands to run on your service.


## Aliases

Using docker compose can contain a lot of boilerplate. That's why I added the following aliases to my shell.

```bash
dc=docker-compose
dcb='docker-compose build'
dcdn='docker-compose down'
dce='docker-compose exec'
dcl='docker-compose logs'
dclf='docker-compose logs -f'
dco=docker-compose
dcps='docker-compose ps'
dcr='docker-compose run'
dcrestart='docker-compose restart'
dcrm='docker-compose rm'
dcstop='docker-compose stop'
dcup='docker-compose up'
```
