# API RESTful de Gerenciamento de Usuários

Este é um exemplo de aplicação em Node.js com o framework Express, que utiliza uma API RESTful para gerenciar usuários. O código define rotas HTTP para buscar, criar, atualizar e deletar usuários em uma lista de objetos no formato JSON.

Dependências

. Node.js

. Express

. Cors

# Instruções de uso

1. Clone o repositório para o seu computador:
git clone https://github.com/seu-usuario/app-rest-users.git

2. Navegue até a pasta do projeto:
cd app-rest-users

3. Instale as dependências do projeto:
yarn install

4. Inicie o servidor:
yarn start

5. Verifique se o servidor está funcionando corretamente acessando a URL http://localhost:3000/users no seu navegador. A lista de usuários deve ser exibida em formato JSON.

# Endpoints

A aplicação define os seguintes endpoints HTTP:

. GET /users: busca todos os usuários na lista de objetos JSON. Retorna a lista de usuários em formato JSON.

. POST /users: cria um novo usuário na lista de objetos JSON. Recebe um objeto JSON no corpo da requisição contendo o nome do novo usuário. Retorna o objeto JSON criado.

. PUT /users/:id: atualiza o nome de um usuário específico na lista de objetos JSON. Recebe um objeto JSON no corpo da requisição contendo o novo nome. O ID do usuário é especificado na URL. Retorna o objeto JSON atualizado.

. DELETE /users/:id: remove um usuário específico da lista de objetos JSON. O ID do usuário é especificado na URL. Retorna a lista atualizada de usuários em formato JSON.
