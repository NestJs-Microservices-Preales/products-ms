<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

# Product Microservice

## Dev

1. Clonar el repositorio
2. Instalar dependencias
```bash
$ npm install
```
3. Crear un archivo `.env` basado en el `env.template`
4. Ejecutar migración de prisma 

```bash
$ npx prisma migrate dev
```

5. Ejecutar 

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

<!-- ## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
``` -->
