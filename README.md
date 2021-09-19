#  Chapter II - Challenge 01 : Introduction to SOLID :rocket: 

## :dart: Objective

01: Create a user listing and registration application using SOLID´s concepts.


## :white_check_mark: Requirements

### Application routes
- [x] POST /users
- [x] PATCH /users/:user_id/admin
- [x] GET /users/:user_id
- [x] GET /users/:user_id

### Tests spacifications

#### Model Test
- [x] Should be able to create an user with all props

#### Repository Tests
- [x] Should be able to create new users
- [x] Should be able to list all users
- [x] Should be able to find user by ID
- [x] Should be able to find user by e-mail address
- [x] Should be able to turn an user as admin

##### useCases Tests
- [x] Should be able to create new users
- [x] Should not be able to create new users when email is already taken
- [x] Should be able to turn an user as admin
- [x] Should not be able to turn a non existing user as admin
- [x] Should be able to get user profile by ID
- [x] Should not be able to show profile of a non existing user
- [x] Should be able to list all users
- [x] Should not be able to a non admin user get list of all users
- [x] Should not be able to a non existing user get list of all users

## :computer: Instalation ##

```bash
# Install dependencies
$ yarn ou yarn install

# Run in development mode 
$ yarn dev

# port : 3333
<http://localhost:3333>

```
