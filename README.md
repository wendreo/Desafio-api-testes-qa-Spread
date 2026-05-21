# Desafio-api-testes-qa-Spread

Este repositório contém a resolução do desafio técnico de testes funcionais, utilizando a API pública **ServeRest**.

Como: gestor
Quero: utilizar uma api pública,
Para: que eu possa realizar testes de "Cadastro de usuarios".


CT - 01 Cadastrar um usuário com sucesso "Caminho feliz"
- Dado que o gestor possui os dados de um novo usuario para cadastro
- Quando enviar uma requisição POST para o https://serverest.dev/usuarios
- Então a API deve retornar o status code 201
- E deve exibir a mensagem "Cadastro realizado com sucesso"
- E deve exibir o ID do usuário criado

CT - 02 Realizar login com o usuario valido "Alternativo"
- Dado que o usuário possui um cadastro ativo no sistema
- Quando enviar uma requisição POST para o https://serverest.dev /login com os dados corretos
- Então a API deve retornar o status code 200
- E deve exibir a mensagem "Login realizado com sucesso"
- E deve retornar um token de autorização válido

CT - 03 Não permite cadastrar usuário com email ja cadastrado "Exceção"
- Dado que o gestor tenta cadastrar um usuário informando um e-mail já
- existente na base
- Quando enviar uma requisição POST para o https://serverest.dev/usuarios
- Então a API deve retornar o status code 400
- E deve exibir a mensagem de erro "Este email já está sendo usado"

## 🛠️ Tecnologias Utilizadas
* **Postman** - Para execução das requisições.
* **Gherkin / BDD** - Para especificação dos cenários.

## 🏃‍♂️ Como executar os testes
1. Baixe o arquivo `(https://wendreoas-4796967.postman.co/workspace/Wendreo-Araujo's-Workspace~c65b628e-ff93-4659-86b6-7bca87d91cff/collection/54307068-459e8e45-9bba-4189-90a9-956a20c2f6df?action=share&source=copy-link&creator=54307068)` deste repositório.
2. Abra o **Postman** e clique em **Import**.
3. Selecione o arquivo baixado.
4. Clique com o botão direito na coleção importada.[Uploading ServeRest.postman_collection.json…]()
rl}}"
                 
