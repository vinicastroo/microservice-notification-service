# microservice-notification-service

Study project of a notifications microservice built with NestJS, applying Clean Code and Clean Architecture concepts (entities, use cases and repositories decoupled from infrastructure), with persistence via Prisma and tests with Jest.

Features: send, cancel, mark as read/unread, count and list a recipient's notifications.

## Tech stack

- NestJS
- Prisma (SQLite)
- Jest (unit and e2e tests)
- TypeScript

## How to run

```bash
npm install

# applies migrations to the database (SQLite)
npx prisma migrate dev

# starts the application in development mode
npm run start:dev

# runs the tests
npm run test
npm run test:e2e
```
