# Nest Pokedex

```md
[![Nest](https://nestjs.com/img/logo_text.svg)](https://nestjs.com/)
[![Docker](https://img.shields.io/badge/docker-%2396ed?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![MongoDB](https://img.shields.io/badge/mongodb-%234ea44f?style=flat-square&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![TypeScript](https://img.shields.io/badge/typescript-%2320232a?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![GitHub](https://img.shields.io/badge/github-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nestjs/nest)  
       
```

## Ejecutar en desarrollo

```bash
yarn install
```

```bash
npm i -g @nestjs/cli
```

```bash
docker-compose up -d
```

## Reconstruir la base de datos con la semilla

```bash
http://localhost:3000/api/v2/seed
```

## Stack usado

* MongoDB
* Nest
* TypeScript
[![Nest](https://nestjs.com/img/logo_text.svg)](https://nestjs.com/)
[![Docker](https://img.shields.io/badge/docker-%2396ed?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![MongoDB](https://img.shields.io/badge/mongodb-%234ea44f?style=flat-square&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![TypeScript](https://img.shields.io/badge/typescript-%2320232a?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![GitHub](https://img.shields.io/badge/github-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nestjs/nest)
[![GitHub](https://img.shields.io/badge/github-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nestjs/nest)

```bash

yarn start:dev
```

## Production Build

1. Crear el archivo ```.env.prod```
2. Llenar las variables de entorno de prod
3. Crear la nueva imagen

```bash
docker-compose -f docker-compose.prod.yaml --env-file .env.prod up --build
```

```bash
docker-compose -f docker-compose.prod.yaml --env-file .env.prod up -d
```

## Notas

Heroku redeploy sin cambios:

```bash
git commit --allow-empty -m "Tigger Heroku deploy"
git push heroku <master|main>
```
