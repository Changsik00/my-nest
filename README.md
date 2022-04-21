<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>
## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

### PlanetScale

https://docs.nestjs.com/recipes/prisma   
https://shadcn.com/next-prisma-planetscale-vercel   
https://docs.planetscale.com/tutorials/automatic-prisma-migrations   
https://docs.planetscale.com/reference/planetscale-cli   
https://github.com/prisma/prisma/issues/7292   

1. planetscale 계정 세팅, github에 my-nest 리파지토리 생성
2. prisma project 설정 및 github, planetscale 연동
3. planetscale init, shadow 브랜치 생성
4. planetscale-cli 설정 및 로그인
5. pscale로 local to server connect
