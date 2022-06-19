# Remix tutorial from Remix.run

- [Remix Docs](https://remix.run/docs)

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

project structure:

|         |             |
| ------- | ----------- |
| build/  | server side |
| public/ | client side |

using Prisma as ORM:

```sh
npm install --save-dev prisma
npm install @prisma/client
```

using SQLite:

```sh
npx prisma init --datasource-provider sqlite
```

setup schema

push schema:

```sh
npx prisma db push
```
