[![example-apollo-grapqhl-server-with-mongodb-atlas](https://github.com/koyeb/example-apollo-grapqhl-server-with-mongodb-atlas/actions/workflows/deploy.yaml/badge.svg)](https://github.com/koyeb/example-apollo-grapqhl-server-with-mongodb-atlas/actions)

<div align="center">
  <a href="https://koyeb.com">
    <img src="https://www.koyeb.com/static/images/icons/koyeb.svg" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Koyeb Serverless Platform</h3>
  <p align="center">
    Deploy an Apollo GraphQL Server with MongoDB Atlas on Koyeb
    <br />
    <a href="https://koyeb.com">Learn more about Koyeb</a>
    ·
    <a href="https://koyeb.com/docs">Explore the documentation</a>
    ·
    <a href="https://koyeb.com/tutorials">Discover our tutorials</a>
  </p>
</div>


## About Koyeb and the Apollo GraphQL Server with MongoDB Atlas example application

Koyeb is a developer-friendly serverless platform to deploy apps globally. No-ops, servers, or infrastructure management.
This repository contains an Apollo GraphQL server you can deploy on the Koyeb serverless platform for testing.

This example application is designed to show how a GraphQL API using Apollo Server and MongoDB can be deployed on Koyeb.

## Getting Started

Follow the steps below to deploy and run the Apollo GraphQL server with MongoDB Atlas on your Koyeb account.

### Requirements

You need a Koyeb account to successfully deploy and run this application. If you don't already have an account, you can sign-up for free [here](https://app.koyeb.com/auth/signup).

### Deploy using the Koyeb button

The fastest way to deploy the Apollo GraphQL server with MongoDB Atlas is to click the **Deploy to Koyeb** button below.

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/apps/deploy?type=git&repository=github.com%2Fkoyeb%2Fexample-apollo-grapqhl-server-with-mongodb-atlas&branch=main&env%5BMONGODB_URI%5D=&name=apollo-graphql-on-koyeb)

Clicking on this button brings you to the Koyeb App creation page with everything pre-set to launch this application.

_To modify this application example, you will need to fork this repository. Checkout the [fork and deploy](#fork-and-deploy-to-koyeb) instructions._

### Fork and deploy to Koyeb

If you want to customize and enhance this application, you need to fork this repository.

If you used the **Deploy to Koyeb** button, you can simply link your service to your forked repository to be able to push changes.
Alternatively, you can manually create the application as described below.

On the [Koyeb Control Panel](//app.koyeb.com/apps), click the **Create App** button to go to the App creation page.

1. Select `GitHub` as the deployment method to use
2. In the repositories list, select the repository you just forked
3. Specify the branch to deploy, in this case `main`
4. In the environment variables section, click the add environment variable button. Select the Secret type, enter MONGODB_URI as the key and for the value, select `Create Secret`. Put MONGODB_URI as the name and then put the value to your MongoDB connection string. Read [this tutorial](//www.koyeb.com/tutorials/deploy-a-graphql-api-with-mongodb-atlas-and-apollo-server-on-koyeb) for more information.
5. Add a plaintext environment variable with the key PORT and value 8080.
6. Then, give your App a name, i.e `graphql-api-on-koyeb`, and click **Create App**.

You land on the deployment page where you can follow the build of your application. Once the build is completed, your application is being deployed and you will be able to access it via `<YOUR_APP_NAME>-<YOUR_ORG_NAME>.koyeb.app`.

## Contributing

If you have any questions, ideas or suggestions regarding this application sample, feel free to open an [issue](//github.com/koyeb/example-apollo-grapqhl-server-with-mongodb-atlas/issues) or fork this repository and open a [pull request](//github.com/koyeb/example-apollo-grapqhl-server-with-mongodb-atlas/pulls).

## Contact

[Koyeb](https://www.koyeb.com) - [@gokoyeb](https://twitter.com/gokoyeb) - [Slack](http://slack.koyeb.com/)
