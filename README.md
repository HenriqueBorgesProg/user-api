# Minha Primeira API Simples

Esta é uma API básica que permite gerenciar usuários. Com ela, você pode:

- Criar usuários
- Editar usuários
- Deletar usuários
- Listar usuários em ordem crescente
- Listar usuários em ordem decrescente

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/HenriqueBorgesProg/user-api
   ```

2. Instale as dependências:
   ```bash
   [Comando para instalar dependências, ex.: npm install ou pip install -r requirements.txt]
   ```

3. Inicie o servidor:
   ```bash
   [Comando para rodar a aplicação, ex.: npm start ou python app.py]
   ```

4. Acesse a API em `http://localhost:3333` ou na porta configurada.

## Endpoints Principais

- **Criar Usuário:** `POST /users`
- **Editar Usuário:** `PUT /users/:id`
- **Deletar Usuário:** `DELETE /users/:id`
- **Listar em Ordem Crescente:** `GET /users?order=desc`
- **Listar em Ordem Decrescente:** `GET /users?order=asc`

---

Feito com afinco por [Henrique Borges ](https://github.com/HenriqueBorgesProg).
