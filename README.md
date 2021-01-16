# Welcome to AceBook

[![forthebadge](https://forthebadge.com/images/badges/made-with-ruby.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)

**Acebook** is an imitation social media app, built as a practice project (forgive us our mistakes!)

Acebook offers users the opportunity to post messages to each other.  Each user has a wall, available at the path `/userid` and also as their homepage when they are logged in. A user can post on any wall, and update and delete their messages after posting.

## Get Started

```sh
git clone && cd acebook-The_Part_Time_Peeps
bundle install
bin/rails db:create
bin/rails db:migrate
```

To run locally in development:
```sh
rails s
open localhost:3000
```


## Testing and code quality

To run tests:
```sh
bundle exec rspec
```

Additionally, when rspec is run, simplecov will calculate test coverage, which you can view with:

```sh
open coverage/index.html
```

For code quality:
```sh
bundle exec rubocop
```

## In Production

View our beautiful app at https://acebook-peeps2020.herokuapp.com


## Project Management

View our Kanban to see what we're working on at https://trello.com/b/HS4R2TtY


## Tech used
- Ruby on Rails with Devise
- DB: PostgresSQL
- CI/CD: CircleCI
- Hosting: Heroku
- Testing and Code Quality: RSpec, SimpleCov, Rubocop

[![forthebadge](https://forthebadge.com/images/badges/it-works-why.svg)](https://forthebadge.com)
