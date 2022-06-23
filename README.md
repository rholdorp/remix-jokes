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

in connecting to the dbase take care not to start up new connect each time.

.server file name convension tells compiler not to bundle for browser part

load data into route module via load >> async function call

like loader, the action function is a server only function to handle data mutations and other actions. (post, put, patch and delete)

install

```sh
npm install bcryptjs
```

install:

```sh
npm install --save-dev @types/bcryptjs
```
