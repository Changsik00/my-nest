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
https://docs.planetscale.com/tutorials/prisma-quickstart
https://docs.planetscale.com/tutorials/automatic-prisma-migrations
https://docs.planetscale.com/reference/planetscale-cli
https://shadcn.com/next-prisma-planetscale-vercel
https://github.com/prisma/prisma/issues/7292

1. planetscale 계정 세팅, github에 my-nest 리파지토리 생성
2. prisma project 설정 및 github, planetscale 연동
3. planetscale init, shadow 브랜치 생성
4. planetscale-cli 설정 및 로그인
5. pscale로 local to server connect

PlanetScale 계정 설정 및 설치가 되었다면 예시로 `my-nest` 접속한 결과

```bash
❯ pscale auth login

Confirmation Code: PB4Z7O0P

If something goes wrong, copy and paste this URL into your browser: https://auth.planetscale.com/oauth/device?user_code=PB4Z7O0P

Successfully logged in.
❯ pscale connect my-nest init --port 3309
Secure connection to database my-nest and branch init is established!.

Local address to connect your application: 127.0.0.1:3309 (press ctrl-c to quit)

```
