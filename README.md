# 🥘 Food Explorer
> Rocket Seat

## 📁 Projeto
O projeto Food Explorer consiste no desafio final do programa Explorer da Rocketseat. Trata-se de uma aplicação de cardápio digital para um restaurante fictício.

O back-end do projeto, que lida com a lógica e o armazenamento dos dados, está disponível neste repositório. Já o front-end, responsável pela interface do usuário, está disponível [aqui](https://food-explorer-backend-api-y9p1.onrender.com).

## 📌 Estrutura
O projeto conta com as seguintes tabelas:

- Usuários
- Pratos
- Ingredientes dos pratos
- Favoritos
- Carrinhos
- Itens dos carrinhos
- Pedidos
- Itens dos pedidos

## 💻 Tecnologias
Este projeto foi desenvolvido com as seguintes tecnologias:

- Bcrypt.js
- CORS
- Dotenv
- Express.js
- express-async-errors
- JSON Web Token
- Knex.js
- Node.js
- Multer
- PM2
- SQLite
- SQLite3

## 💡 Utilização
O back-end do projeto está hospedado no endereço https://food-explorer-backend-api-y9p1.onrender.com. A aplicação Food Explorer está disponível para uso aqui.

⚠️ Importante: Este projeto utiliza uma hospedagem gratuita para o back-end, portanto, pode haver atrasos no tempo de resposta do servidor.

Você também pode executá-lo em sua máquina localmente. Certifique-se de ter o Node.js e o npm instalados antes de prosseguir com as etapas abaixo:

Clone o projeto:

```
$ git clone https://github.com/Podolsk1DV/food-explorer-backend
```
Acesse a pasta do projeto:
```
$ cd food-explorer-backend
```
Instale as dependências:
```
$ npm install
```
Execute as migrações:
```
$ npm run migrate
```
Inicie o servidor:
```
$ npm start
```

⚠️ Importante: Crie um arquivo .env de acordo com o arquivo .env.example e preencha os campos AUTH_SECRET e PORT com suas respectivas informações.

Para gerar o valor para o campo AUTH_SECRET, você pode utilizar o MD5 Hash Generator para gerar uma sequência de caracteres segura

Preencha o campo PORT com o número da porta desejada para executar o servidor da aplicação


## Criado por
Podolsk1DV
