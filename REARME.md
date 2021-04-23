# Ignite - Desafio 05 - Database Queries
Nesse desafio, você realizará consultas no banco de dados com o TypeORM de três maneiras:

- Usando o ORM
- Usando Query Builder
- Usando Raw Query

No template, você irá encontrar uma aplicação já estruturada (apenas as entidades e repositórios) onde você deverá completar o que falta nas consultas dos dois repositórios.

A aplicação possui dois módulos: `users` e `games`. Um **usuário** pode ter vários jogos e um mesmo **jogo** pode estar associado a vários usuários.

O template está disponível na seguinte URL: 

[rocketseat-education/ignite-template-database-queries](https://github.com/rocketseat-education/ignite-template-database-queries)

## Especificação dos Testes de Middlewares

- [x] **[UsersRepository] should be able to find user with games list by user's ID**

- [x] **[UsersRepository] should be able to list users ordered by first name**

- [x] **[UsersRepository] should be able to find user by full name**

- [x] **[GamesRepository] should be able find a game by entire or partial given title**

- [x] **[GamesRepository] should be able to get the total count of games**

- [x] **[GamesRepository] should be able to list users who have given game id**


## Executando a aplicação

- Após clonar o repositório, navegue até o diretório pelo terminal e execute o comando `yarn` para instalar todas as dependências.

- Execute o comando `yarn test` para rodar os testes.