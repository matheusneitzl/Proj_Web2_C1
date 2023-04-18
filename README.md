## Instalações

### Instale o Typescript:

- Use o npm install typescript --save-dev ;
- Rode o comando npm-audit fix;

### npm-audit fix:

O comando audit envia uma descrição das dependências configuradas em seu projeto para seu registro padrão e solicita um relatório de vulnerabilidades conhecidas.

## Outros casos:

- Caso você opte por não instalar o ts-node globalmente, você pode instalá-lo localmente em seu projeto usando o comando npm install --save-dev ts-node.

- Em seguida, você precisará modificar o comando npm run dev em seu package.json usando:

"dev": "set NODE_ENV=dev&&nodemon ./src/server.ts",

## Executar o projeto:

- Para rodar o projeto como TS, basta executar o comando: npm run dev
