# GYMPOINT
Desafio final do bootcamp gostack da rocketseat.

## Backend

Este projeto se refere ao backend da aplicação Gympoint que foi desenvolvida durante o Bootcamp GoStack da [RocketSeat](https://https://rocketseat.com.br/) e é a primeira parte do desafio final.
O repositório original do projeto pode ser encontrado na pasta backend.

## :computer: Instalação e execução do backend.

1. Faça um clone desse repositório;
2. Entre na pasta do backend `cd GYMPOINT` `cd backend`;
3. Rode `yarn` para instalar as dependências;
4. Crie um banco de dados no `postgres` com o nome de `gympoint`;
5. Renomeie o arquivo `.env.example` para `.env`;
6. Coloque as suas credenciais dentro do `.env`;
7. Rode `yarn sequelize db:migrate` para executar as migrations;
8. Rode `yarn sequelize db:seed:all` para executar a seed;
9. Rode `yarn dev` para iniciar o servidor.
10. Rode `yarn queue` para iniciar as filas. (opcional).

#########################################################


## Frontend

Este projeto se refere ao backend da aplicação Gympoint que foi desenvolvida durante o Bootcamp GoStack da [RocketSeat](https://https://rocketseat.com.br/) e é a segunda parte do desafio final.
O repositório original do projeto pode ser encontrado na pasta frontend.

## :computer: Instalação e execução frontend
Antes de executar este projeto, inicie o backend gympoint, que pode ser encontrado na pasta backend e siga as instrucoes acima . 

1. Faça um clone desse repositório;
2. Entre na pasta rodando `cd GYMPOINT` `cd frontend`;
3. Rode `yarn` para instalar as dependências;
4. Rode `yarn start` para iniciar o client.
5. Logue na aplicação usando as credenciais usadas para a criação do usuário admin(Caso não tenha alterado no backend da aplicação, o usuário é `admin@gympoint.com` e a senha `123456`)

#########################################################


## Mobile

Este projeto se refere ao backend da aplicação Gympoint que foi desenvolvida durante o Bootcamp GoStack da [RocketSeat](https://https://rocketseat.com.br/) e é a terceira parte do desafio final.
O repositório original do projeto pode ser encontrado na pasta frontend.

## :computer: Instalação e execução mobile
Antes de executar este projeto, inicie o backend gympoint, que pode ser encontrado na pasta backend e siga as instrucoes acima . 

Faça um clone desse repositório;
Entre na pasta rodando `cd GYMPOINT` `cd frontend`;
Rode yarn para instalar as dependências;
Rode yarn react-native run-ios ou yarn react-native run-android dependendo do SO para iniciar o client.
Logue na aplicação usando o ID de usuário desejado (por exemplo, 1)
PS: este projeto somente foi testado em emulador iPhone. Não foi testado no Android
