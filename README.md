# Continuous Integration and Deployment with GitHub, Travis and Heroku

## Deploy to Heroku

1. Create app on Heroku and set up Git remote: `heroku create`
1. Push to Heroku: `git push heroku master`
1. Add any necessary environment variables
1. Create db on Heroku: `heroku addons:create heroku-postgresql:hobby-dev`
1. Update *knexfile.js* with production config
1. Push to Heroku, after you commit
1. Create migrations (if necessary)
1. Apply Migrations: `heroku run knex migrate:latest --env=production`
1. Create Seeds (if necessary)
1. Apply Seeds: `heroku run knex seed:run --env=production`
1. Restart Heroku app: `heroku restart`

## Push to GitHub

1. Set up remote on GitHub
1. Push

## Set up Travis

1. Sign up (if necessary)
1. Add project repo
1. Do a quick sanity check - add a new test, push to Github, ensure tests run on Travis
1.
