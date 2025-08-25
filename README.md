# 📣 Projeto Institucional de Organização de Eventos

Este é um projeto institucional desenvolvido com o objetivo de divulgar e fortalecer a marca por meio da organização de eventos. A aplicação oferece uma interface moderna e responsiva, além de funcionalidades que facilitam o contato com o público.

## 🚀 Tecnologias Utilizadas

- **Node.js** – Ambiente de execução JavaScript no servidor
- **Express** – Framework para criação de APIs e rotas
- **JavaScript (JS)** – Lógica de interação e funcionalidades
- **HTML & CSS** – Estrutura e estilo da aplicação
- **TailwindCSS** – Framework utilitário para estilização rápida e responsiva
- **Knex.js** – Query builder para integração com banco de dados
- **SQLite & PostgreSQL** – Bancos de dados utilizados
- **MVC (Model-View-Controller)** – Arquitetura para organização do código

## 📂 Estrutura do Projeto

O projeto segue o padrão MVC:

- `models/` – Definições e interações com o banco de dados
- `views/` – Páginas HTML estilizadas com TailwindCSS
- `controllers/` – Lógica de negócio e manipulação de dados
- `routes/` – Definição das rotas da aplicação

## 📬 Funcionalidade de Contato

A aplicação conta com um formulário de contato onde os usuários podem enviar mensagens. Os dados são armazenados no banco de dados para posterior análise e retorno.

Campos do formulário:
- Nome
- E-mail
- Assunto
- Mensagem

## 🛠️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
    ```

2. Instale as dependências:
    ```bash
    npm install
    Configure o banco de dados no arquivo .env:
    ```

3. Configure o banco de dados no arquivo .env:
    ```env
    DB_CLIENT=pg
    DB_HOST=localhost
    DB_USER=seu_usuario
    DB_PASSWORD=sua_senha
    DB_NAME=nome_do_banco
    ```

4. Execute as migrations:
    ```bash
    npx knex migrate:latest
    Inicie o servidor:
    ```

5. Inicie o servidor
    ```bash
    npm start
    ```
## 📈 Objetivo Institucional
### Este projeto foi desenvolvido para:

- Promover a marca por meio de eventos organizados
- Facilitar o contato com o público
- Criar uma presença digital moderna e funcional
- Armazenar informações de contato para ações futuras

Desenvolvido com 💙 por Wagner Leodoro