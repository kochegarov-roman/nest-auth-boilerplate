## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript auth (with session, cookie, swagger support) boilerplate
repository.

## Installation

```bash
npm install
```

## Running prisma with docker

```bash
docker-compose up
```

## Apply DB changes with prisma

```bash
npx prisma db push
```

## Running the app

```bash
# development
npm run start

# watch mode
npm run start:dev

# production mode
npm run start:prod
```

### swagger support

go by url: **/api**

### nest commands

for create service - **s**, controller - **co**, module - **mo**, guard - **gu**:

```bash
npx nest g s servicename
```