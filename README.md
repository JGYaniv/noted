# README

## Tech Stack

- API
  - Ruby v2.6.6
  - Ruby on Rails v6.0.3
  - Auth:
    - [ruby-jwt v2.2.2](https://github.com/jwt/ruby-jwt)
    - [BCrypt v3.1.7](https://github.com/codahale/bcrypt-ruby)
  - Testing:
    - [pry-rails v0.3.9](https://github.com/rweng/pry-rails)
    - [rspec-rails v3.9.0](https://github.com/rspec/rspec-rails)
- Client
  - Node.js
  - React.js

## Use Cases

1.  Enters address, without valid JWT
    - Redirected to session form
    - Enters email and password
    - Password is invalid, form validation alerts
    - Receives welcome email and redirect to index
    - Open settings and change to dark mode
    - Create a new note
    - Share note via email
2.

## Assumptions

- User can only be signed in with one device at a time
- Notes are only updated/created on the backend on save

## Data Model

## Sample Data
