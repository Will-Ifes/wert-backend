# WERT — backend

API REST do projeto WERT, construída em Node.js, Express, TypeScript, Prisma e PostgreSQL. Esta versão de portfólio foi formada a partir do código revisado, com histórico novo para não expor o dump de banco presente no repositório privado original.

## Escopo presente no código

- Rotas e regras para usuários, empresas, produtos, inventário, fornecedores e permissões.
- Autenticação com JWT e senha com hash.
- Modelos e migrações Prisma, além de testes.

## Executar

Instale as dependências com `pnpm install`, configure `DATABASE_URL`, `JWT_SECRET` e as demais variáveis necessárias, execute as migrações e inicie com `pnpm dev`. Use um banco de desenvolvimento próprio. Não reutilize dados ou credenciais do projeto original.

## Contexto

Trabalho desenvolvido por Will Oliveira no projeto WERT, com colaboração registrada no projeto original. [Interface relacionada](https://github.com/Will-Ifes/wert-frontend).
