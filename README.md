# Heroku Buildpack New Relic Deployments

Track Heroku deployments with New Relic

## Requirements

Add the following environnement variables to Heroku:

- `NEW_RELIC_APP_ID`: You can find it New Relic's app url.
- `NEW_RELIC_API_KEY`: You can find it in New Relic's account settings.

Add buildpack to Heroku:

`heroku buildpacks:add https://github.com/laissonsilveira/heroku-buildpack-newrelic-deployments.git`
