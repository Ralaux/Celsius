# CELSIUS 📡

[![pipeline status](https://gitlab.com/jovici_a/celsius/badges/main/pipeline.svg)](https://gitlab.com/jovici_a/celsius/-/commits/main)

## Getting started

Yo bg !
Voici le git pour le développement de CELSIUS

~~Lien de la production de celsius : www.celsius.ovh~~

~~Logins de connexion pour naviguer sur l'outil~~
~~login : doudon_t@etna-alternance.net~~
~~pwd : test12345~~

## Init le projet

Même si je pense que tout le monde sait

```
cd existing_repo
git remote add origin https://gitlab.com/gpe-etna/celsius.git
git branch -M main
git push -uf origin main
```

## Documentation

La documentation est disponible dans le directory "Documentation"

## Launch

### First time ?

`docker-compose up --build` to build and up containers.

Once up, you should be able to **access Express IHM** [here](http://localhost:3000)

Once up, you should be able to **access Dotnet Agregator** [here](http://localhost:5001)

### Troubleshooting

`docker exec -it dotnet-api sh` to get a **shell** inside the dotnet container

`docker exec -it express-api sh` to get a **shell** inside the express container

Sinon soyez pas timides, vous m'appelez.

#### Manage Docker containers and volumes

`docker ps` to **show** containers (running or not).

`docker stop $(docker ps -a -q) && docker rm $(docker ps -a -q)` to **stop** ALL docker containers or `drm` if you have aliases (ask me about it)

`docker volume rm $(docker volume ls -q)` to **remove ALL volumes** (most often used to drop the database & restart from a fresh DB) or `drmv` if you have aliases (ask me about it)


## Membres

Aleksandar JOVICIC

Maxence VACHERON

Raphael ALAUX

Yannis TUDEAU

Timothée DOUDON

Paul LEQUEUX

Julien TOSTI

Adrien PLATEVOET
