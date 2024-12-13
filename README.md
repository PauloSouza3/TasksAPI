# Sistema de Gerenciamento de Tarefas (TasksApi)

Uma API RESTful para gerenciar tarefas, permitindo controle de usuários, tarefas e categorias de tarefas.

---

## Índice

1. [Descrição do Projeto](#descrição-do-projeto)
2. [Como Baixar o Repositório](#como-baixar-o-repositório)
3. [Pré-requisitos](#pré-requisitos)
4. [Fluxo de Trabalho](#fluxo-de-trabalho)
5. [Ferramentas e Bibliotecas](#ferramentas-e-bibliotecas)
6. [Comandos de Instalação](#comandos-de-instalação)
7. [Como Rodar o Projeto](#como-rodar-o-projeto)

---

## Descrição do Projeto

O sistema permite:

- **CRUD para Tarefas**: título, descrição, data de vencimento e status.
- **CRUD para Categorias**: categorias personalizadas por cada usuário.
- **CRUD para Usuários**: nome, e-mail e senha.
- **Filtros e Busca**: tarefas concluídas, atrasadas ou por categoria.

---

## Como Baixar o Repositório

1. **Clone o repositório**:

    ```bash
    git clone https://github.com/itswall/TasksApi.git
    ```

2. **Navegue até a pasta do projeto**:

    ```bash
    cd TasksApi
    ```

---

## Pré-requisitos

- **Node.js** (versão 16 ou superior)  
- **MySQL**  
- **Visual Studio Code** (ou outra IDE de sua preferência)  

---

## Fluxo de Trabalho

### 1. Criação da Branch

```bash
git checkout -b feature/nome-da-feature


git add .
git commit -m "descrição do commit"
git push origin feature/nome-da-feature


git checkout main
git merge feature/nome-da-feature


#Ferramentas e Bibliotecas

Frameworks e Bibliotecas
Express (framework para API RESTful)
Sequelize (ORM para MySQL)
dotenv (gerenciamento de variáveis de ambiente)
bcrypt (criptografia de senhas)
jsonwebtoken (autenticação JWT)
Banco de Dados
MySQL
IDE
Visual Studio Code


npm install express mysql2 sequelize dotenv bcrypt jsonwebtoken

net start mysql

CREATE DATABASE tasksapi;

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=sua_senha
DB_NAME=tasksapi

cd TasksApi

npm run dev

http://localhost:3000

