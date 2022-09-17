# Backend

```
npm i prisma -D
npx prisma init --datasource-provider SQLite
npx prisma migrate dev
```

abre uma visualização do branco no browser

```
npx prisma studio
```

para abrir conexão com o banco

```
npm i @prisma/client
```

- Route

  - Ex: /ads/2
  - Usados geralmente em: identificação de um recurso da API
  - Não necessita de nomeação

- Query

  - Ex: /ads?id=2
  - Usados geralmente em: ordenações, filtros, paginação
  - Necessita de nomeação

- Body
  - Usados geralmente em: envio de formulários
