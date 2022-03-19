# Fullstack TypeScript Reddit clone, using Node, Apollo GraphQL, MongoDB, PostgreSQL and NextJS

## Technologies

- TypeScript
- Node and Express
- Apollo GraphQL with TypeGraphQL, Pagination, DataLoader, Client GraphQL Cache and GraphQL Client Code Generation
- React and NextJS with Formik and ChakraUI

## Server Init

```bash
cd server

yarn init

yarn add -D @types/node typescript

yarn add -D ts-node

yarn add -D nodemon

mkdir src && touch src/index.ts && echo "console.log('Hello, World')" >> src/index.ts

# add "scripts" section to package.json
# add "start": "node dist/index.js"
# add "server": "nodemon dist/index.js"
# add "start-ts": "ts-node src/index.ts" to "scripts"
# add "server-ts": "nodemon --exec ts-node src/index.ts" to "scripts"
# add "watch": "tsc -w" to "scripts"

npx tsconfig.json

# Working flow
yarn watch
yarn server
# Making changes

# Prettier support
yarn add --dev --exact prettier
```
