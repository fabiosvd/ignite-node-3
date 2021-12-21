#  Desafio do curso de Node da Rocketseat - Database Queries

## :dart: Objetivo

Realizar consultas no banco de dados com o TypeORM de três formas:

- ORM
- Query Builder
- Raw Query

## :white_check_mark: Requisitos

### Repositórios da aplicação

#### UsersRepository
- [x] findUserWithGamesById
- [x] findAllUsersOrderedByFirstName
- [x] findUserByFullName

#### GamesRepository
- [x] findByTitleContaining
- [x] countAllGames
- [x] findUsersByGameId

### Específicação dos testes

#### UsersRepository
- [x] Should be able to find user with games list by user's ID
- [x] Should be able to list users ordered by first name
- [x] Should be able to find user by full name

#### GamesRepository
- [x] Should be able find a game by entire or partial given title
- [x] Should be able to get the total count of games
- [x] Should be able to list users who have given game id
