# microservice-notification-service

Projeto de estudos de um microsserviço de notificações construído com NestJS, aplicando conceitos de Clean Code e Clean Architecture (entidades, casos de uso e repositórios separados da infraestrutura), com persistência via Prisma e testes com Jest.

Funcionalidades: enviar, cancelar, marcar como lida/não lida, contar e listar notificações de um destinatário.

## Tecnologias

- NestJS
- Prisma (SQLite)
- Jest (testes unitários e e2e)
- TypeScript

## Como rodar

```bash
npm install

# aplica as migrations no banco (SQLite)
npx prisma migrate dev

# sobe a aplicação em modo desenvolvimento
npm run start:dev

# roda os testes
npm run test
npm run test:e2e
```
