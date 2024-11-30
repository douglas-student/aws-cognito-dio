# Desafio Bootcamp Cloud AWS

Este arquivo faz parte de um dos desafios do Bootcamp Cloud AWS, onde o objetivo era construir uma solução de autenticação, autorização e gerenciamento de usuários utilizando serviços da AWS. Durante o desafio, aprendemos a integrar várias ferramentas da AWS, como Amazon Cognito, DynamoDB, API Gateway e AWS Lambda, para criar uma API RESTful segura, com a capacidade de inserir e gerenciar dados em um banco de dados DynamoDB.

## Solução

Nossa solução consiste em uma API RESTful criada com o Amazon API Gateway, integrada ao serviço AWS Lambda para processar e armazenar dados no DynamoDB. Utilizando o Amazon Cognito, implementamos autenticação e autorização de usuários para garantir que apenas usuários autenticados possam interagir com a API. O fluxo de inserção de dados permite que os usuários insiram novos itens no banco de dados com segurança, utilizando um token de autenticação no cabeçalho da requisição.
