# Tela

<a href="https://codeclimate.com/github/emmaalbury/Team-Tela/maintainability"><img src="https://api.codeclimate.com/v1/badges/23c27119758c8d0e5ffb/maintainability" /></a>

A social media platform allowing users to sign up, sign in, post, like and comment on user content.

Link to the app in production: https://team-tela.herokuapp.com/

You can find the engineering project outline here: https://github.com/makersacademy/course/tree/master/engineering_projects/rails

## Development ##

This project was created in two weeks with a team of four members using an agile development process.

The card wall is here: https://trello.com/b/bwJN79eJ/team-tela

Shared learning documentation: https://github.com/emmaalbury/Team-Tela/wiki/A-record-of-progress

## Build status: ##
Build status of continuous integration using Travis CI passing.

[![Build Status](https://travis-ci.org/emmaalbury/Team-Tela.svg?branch=master)](https://travis-ci.org/emmaalbury/Team-Tela)

https://travis-ci.org/emmaalbury/Team-Tela/builds/447909112

## Instructions for running the program: ##

  Clone this repository https://github.com/emmaalbury/Team-Tela
  
  Then enter in the command line:

```bash
> brew install postgres
> bundle install
> brew services start postgresql
> bin/rails db:create
> bin/rails db:migrate

Tests:
Run the tests to ensure it works
> bundle exec rspec

Server:
Start the server at localhost:3000
> bin/rails server
```

## Tech and frameworks used: ##

Rails,
Devise,
Travis CI,
Heroku,
AWS,
Rubocop,
Simplecov.

## How to contribute to this project ##
See [CONTRIBUTING.md](CONTRIBUTING.md)

## User Stories: ##

As a user,
I can sign up securely,
So that I can create a account.

As a user,
I can log in,
So that I can make and view posts.

As a user,
I can view my posts,
So that I can edit and delete them.

As a user,
I can see other users posts,
So that I can like and comment on them.

As a user,
I have the time and date labeled on each post,
So that I can see when I have posted.

As a user,
I can view posts with the newest post first,
So that I can see what order I posted in.

As a user,
I can see comments on my posts,
So that I can interact with other users.

As a user,
I can see how many people have "liked" my posts,
So that I can see how popular each post is.
