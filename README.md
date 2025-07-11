==============================
🛠️ SETUP DO PROJETO - BACKEND
==============================

Este guia cobre as instalações e comandos essenciais para um projeto com:
TypeScript, Fastify, Drizzle ORM e PostgreSQL.

---

## 📦 INSTALAÇÃO DE DEPENDÊNCIAS

# Dependências de Desenvolvimento

npm i typescript @types/node -D -> TypeScript e tipos do Node
npm i drizzle-kit drizzle-seed -D -> CLI do Drizzle + Seeder

# Dependências de Produção

npm i fastify @fastify/cors -> Framework Fastify + CORS
npm i fastify-type-provider-zod zod -> Integração do Fastify com Zod
npm i drizzle-orm -> ORM Drizzle
npm i postgres -> Cliente PostgreSQL

---

## ⚙️ INICIALIZAÇÃO DO PROJETO

npm init -y -> Cria o package.json
npx tsc --init -> Gera o tsconfig.json

---

## 🐳 COMANDOS DO DOCKER

docker compose up -d -> Sobe os containers em segundo plano
docker compose ps -> Lista os containers em execução

---

## 🧬 COMANDOS DO DRIZZLE ORM

npx drizzle-kit generate -> Gera as migrações com base nos schemas
npx drizzle-kit migrate -> Executa as migrações no banco
npx drizzle-kit studio -> Abre o painel web do banco

## RODAR PROJETO

abrir docker e start container ou docker compose up -d
npm run dev -> Roda o server
