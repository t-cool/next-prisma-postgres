
## setup

- mv .env-sample .env
- npm install
- npm run build
- docker compose up -d
- npm run migrate:init
- npm run postinstall
- npm run seed
- npm run dev

## prisma studio 立ち上げ

- npm run studio

## DB のリセット

- npm run db:reset

## credit

https://github.com/takumi0616/template-next-prisma-docker

