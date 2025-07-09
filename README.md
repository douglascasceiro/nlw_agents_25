# NLW Agents

Projeto desenvolvido durante o evento NLW da Rocketseat.
Este é o repositorio responsavel pela configuração do Docker do projeto

---

## Sobre

O **NLW Agents** é um projeto fullstack composto por uma API Node.js (Fastify) e um front-end React, ambos escritos em TypeScript. O ambiente é orquestrado via Docker Compose, incluindo um banco de dados PostgreSQL com extensão pgvector.

---

## Tecnologias Utilizadas

- **Backend:** Node.js, Fastify, TypeScript
- **Frontend:** React, TypeScript, Vite
- **Banco de Dados:** PostgreSQL (imagem pgvector/pgvector:pg17)
- **Orquestração:** Docker Compose

---

## Padrões de Projeto

- Separação clara entre API (`server/`) e front-end (`web/`)
- Uso de containers para isolar ambientes
- Variáveis de ambiente via arquivos `.env`
- Persistência de dados via volume Docker

---

## Setup do Projeto

### Pré-requisitos

- [Docker](https://www.docker.com/) e [Docker Compose](https://docs.docker.com/compose/)

### Passos

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/seu-usuario/nlw-agents.git
   cd nlw-agents
   ```
