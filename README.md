# srv-template

Template de backend Desenrolai — criado pelo forge.

Stack: NestJS 11 + Fastify + TypeScript strict + Node 22.

## Desenvolvimento

```bash
cp .env.example .env.local
npm install
npm run start:dev
```

Health check: `GET /api/v1/health` → `{ "status": "ok" }`

## Scripts

| Comando | Descrição |
|---------|-----------|
| `npm run build` | Compila TypeScript |
| `npm run start` | Inicia em produção |
| `npm run start:dev` | Inicia com hot-reload |
| `npm run lint` | ESLint |
| `npm test` | Jest |
| `npm run test:cov` | Jest + coverage |
