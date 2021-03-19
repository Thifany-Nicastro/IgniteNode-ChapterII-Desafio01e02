#  Chapter II - Desafio 01: Introdução ao SOLID :rocket: :purple_heart:

## :dart: Objetivo

Criar uma aplicação de listagem e cadastro de usuários utilizando os conceitos de SOLID aprendidos.

## :white_check_mark: Requisitos

### Rotas da aplicação
- [ ] POST /users
- [ ] PATCH /users/:user_id/admin
- [ ] GET /users/:user_id
- [ ] GET /users/:user_id

### Específicação dos testes

#### Teste do model
- [ ] Should be able to create an user with all props

#### Testes do repositório
- [ ] Should be able to create new users
- [ ] Should be able to list all users
- [ ] Should be able to find user by ID
- [ ] Should be able to find user by e-mail address
- [ ] Should be able to turn an user as admin

##### Testes de useCases
- [ ] Should be able to create new users
- [ ] Should not be able to create new users when email is already taken
- [ ] Should be able to turn an user as admin
- [ ] Should not be able to turn a non existing user as admin
- [ ] Should be able to get user profile by ID
- [ ] Should not be able to show profile of a non existing user
- [ ] Should be able to list all users
- [ ] Should not be able to a non admin user get list of all users
- [ ] Should not be able to a non existing user get list of all users

## :computer: Instalação ##

```bash
# Clone este repositório
$ git clone https://github.com/Thifany-Nicastro/IgniteNode-ChapterII-Desafio01.git

# Entre na pasta
$ cd IgniteNode-ChapterII-Desafio01

# Instale as dependências
$ yarn ou yarn install

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# O servidor inciará na porta:3333
acesse <http://localhost:3333>
```
