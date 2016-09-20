# Continuous Integration and Deployment with GitHub, Travis and Heroku

## Deploy to Heroku

1. Create app on Heroku and set up Git remote: `heroku create`
1. Push to Heroku: `git push heroku master`
1. Create db on Heroku: `heroku addons:create heroku-postgresql:hobby-dev`
1. Update *knexfile.js*
1. Push to heroku
1. migrations
1. seeds
1. heroku restart
