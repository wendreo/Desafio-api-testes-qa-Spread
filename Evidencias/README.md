## 📸 Evidências de Testes

Abaixo estão as capturas de tela que comprovam a execução e o sucesso dos testes automatizados no Postman.

### CT - 01 Cadastrar um usuário com sucesso ''Caminho feliz"
    {
    "nome": "Wendreo as 2",
    "email": "testeQA@qa.com.br",
    "password": "teste123",
    "administrador": "true"
    }
### CT - 02 Realizar login com o usuario valido "Alternativo"
    {
    "email": "testeQA@qa.com.br",
    "password": "teste123"
    }    
### CT - 03 Não permite cadastrar usuário com e-mail ja cadastrado "Exceção"
    {
    "nome": "Wendreo as email duplicado",
    "email": "testeQA@qa.com.br",
    "password": "teste123",
    "administrador": "true"
    }

