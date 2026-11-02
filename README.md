# GoodFood Catalogue Service

Catalogue microservice of the GoodFood platform: it owns restaurants, menus and products and exposes them to the other services.

## Features

- Restaurants, menus and products CRUD
- Prisma data layer
- Dockerfile and CI workflow for the microservice

## Tech Stack

- NestJS (TypeScript)
- Prisma ORM
- Docker, GitHub Actions
- Jest for unit and e2e tests

## Getting Started

```bash
git clone https://github.com/ghostland-dev/service-catalogue.git
cd service-catalogue
npm install
cp .env.example .env   # then fill in your own values
npm run start:dev
```

Run the tests with `npm run test` and `npm run test:e2e`.

## Author

**Ismail.M**, Software Engineer & DevOps

- GitHub: [@ghostland-dev](https://github.com/ghostland-dev)
- Website: [ismail-mouyahada.com](https://www.ismail-mouyahada.com)
