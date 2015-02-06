Day 24 - Heroku
==============

Quiz: No quiz today

Today
--

1. Deploy to Heroku
1. Before Filters
1. Flash
1. Define REST
1. Helpers
1. Scope
1. Select in Forms and Collection Select

Homework: No Homework Today


Notes for Deploying to Heroku
-----

1. Make sure you are using Postgres
1. Make sure you include `rails_12factor` gem
1. Run `heroku auth:login` once
1. Run `heroku create $optional-name` to create a heroku app
1. Run `git push heroku master` to deploy via git to heroku
1. Make sure you run `heroku run rake db:migrate` to get your heroku database up
   to date
1. Make sure you run `heroku run rake db:seed` to seed your data (once)
