# Automate smoke tests for a Go app on Heroku 

[![Heroku](https://heroku-badge.herokuapp.com/?app=go-heroku-assertible-example)](https://go-heroku-assertible-example.herokuapp.com/) [![Test status](https://assertible.com/apis/1ffc0c9d-d1e7-47c2-b4d1-62bae28791fb/status?api_token=4f7732214e77f3bcde)](https://assertible.com/dashboard#/services/1ffc0c9d-d1e7-47c2-b4d1-62bae28791fb/results)

Automatically run smoke tests for a Go application every time it's
deployed to Heroku using [Assertible](https://assertible.com).

[**Example pull request**](https://github.com/assertible/go-heroku-example/pull/1)

[**Try it by opening a Pull Request**](https://github.com/assertible/go-heroku-example/compare)


## Quick start

The following step are high-level overview for how to get review apps
working with Assertible.

For a more detailed set of steps, check out the
post
[**Tutorial: Automate smoke tests for a Go API on Heroku**](https://github.com/assertible/go-heroku-example/compare)

### 1. Setup a Heroku app w/ Review Apps enabled

<img
  src="https://s3-us-west-2.amazonaws.com/assertible/blog/go-heroku-dash-pipeline.png"
  alt="Heroku pipeline with Review Apps Enabled" />

### 2. Configure Assertible web service

<img
  src="https://s3-us-west-2.amazonaws.com/assertible/blog/assertible-new-service-go-heroku-example.png"
  alt="Configuring a web service in Assertible" />

### 3. Connect Assertible web service to GitHub

<img
  src="https://s3-us-west-2.amazonaws.com/assertible/blog/go-heroku-example-assertible-deployments-configuration.png"
  alt="Connect Assertible to GitHub" />

### 4. Push code to a pull request

<img
  src="https://s3-us-west-2.amazonaws.com/assertible/blog/go-heroku-assertible-successful-deployment.png"
  alt="Automated API tests run by Assertible reported to GitHub pull request" />


## Documentation and resources

- [Automate smoke tests for a Go API on Heroku](https://assertible.com/blog/automate-smoke-tests-for-a-go-api-on-heroku)
- [Create a new heroku app](https://medium.com/@freeformz/hello-world-with-go-heroku-38295332f07b)
- [Setup Heroku Review Apps](https://devcenter.heroku.com/articles/github-integration-review-apps)
- [Automating QA pipelines for Heroku Review Apps](https://assertible.com/blog/automating-qa-pipelines-for-heroku-review-apps)


## Testing production

When changes are merged to `master`, Assertible will automatically run
checks against your production application.

You may need to configure a new environment in Assertible which
matches the name of your Heroku application. For this app I have
created an environment named `go-heroku-assertible-example`:

<img
  src="https://s3-us-west-2.amazonaws.com/assertible/blog/assertible-go-heroku-assertible-example-environment.png"
  alt="Heroku pipeline with Review Apps Enabled" />


## License

The code in this repository is licensed under
MIT. [View the license](https://github.com/assertible/deployments/blob/master/LICENSE)
