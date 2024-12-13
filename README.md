Sistema de Gerenciamento de Tarefas (TasksApi)
Uma API RESTful para gerenciar tarefas, permitindo controle de usuários, tarefas e categorias de tarefas.

Índice
Descrição do Projeto
Como Baixar o Repositório
Pré-requisitos
Fluxo de Trabalho
Ferramentas e Bibliotecas
Comandos de Instalação
Como Rodar o Projeto
Descrição do Projeto
O sistema permite:

CRUD para Tarefas: título, descrição, data de vencimento e status.
CRUD para Categorias: categorias personalizadas por cada usuário.
CRUD para Usuários: nome, e-mail e senha.
Filtros e Busca: tarefas concluídas, atrasadas ou por categoria.
Como Baixar o Repositório
Clone o repositório:

bash
Copiar código
git clone https://github.com/itswall/TasksApi.git
Navegue até a pasta do projeto:

bash
Copiar código
cd TasksApi
Pré-requisitos
Node.js (versão 16 ou superior)
MySQL
VSCode ou outra IDE compatível
Fluxo de Trabalho
Criação da Branch
bash
Copiar código
git checkout -b feature/nome-da-feature
Commit e Push
bash
Copiar código
git add .
git commit -m "descrição do commit"
git push origin feature/nome-da-feature
Merge
bash
Copiar código
git checkout main
git merge feature/nome-da-feature
Ferramentas e Bibliotecas
Frameworks
Express (para criação da API RESTful)
Banco de Dados
MySQL
Bibliotecas
Sequelize (ORM para MySQL)
dotenv (gerenciamento de variáveis de ambiente)
bcrypt (criptografia de senhas)
jsonwebtoken (autenticação JWT)
IDEs
Visual Studio Code
Comandos de Instalação
Instalar as Dependências
bash
Copiar código
npm install express mysql2 sequelize dotenv bcrypt jsonwebtoken
JDK (JavaScript não requer JDK, remova se for específico do Java)
Configuração do Banco de Dados
Inicie o servidor MySQL:
bash
Copiar código
net start mysql
Crie o banco de dados:
sql
Copiar código
CREATE DATABASE tasksapi;
Configure o arquivo .env com as credenciais do banco de dados:
makefile
Copiar código
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=sua_senha
DB_NAME=tasksapi
Como Rodar o Projeto
Certifique-se de estar no diretório do projeto:
bash
Copiar código
cd TasksApi
Execute a API:
bash
Copiar código
npm run dev
Acesse o endpoint padrão em:
arduino
Copiar código
http://localhost:3000
Testar as Rotas
Utilize o Postman ou outra ferramenta de sua escolha para testar os endpoints da API.
