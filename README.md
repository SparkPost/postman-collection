<a href="https://www.sparkpost.com"><img src="https://www.sparkpost.com/sites/default/files/attachments/SparkPost_Logo_2-Color_Gray-Orange_RGB.svg" width="200px"/></a>

[Sign up](https://app.sparkpost.com/join?plan=free-0817?src=Social%20Media&sfdcid=70160000000pqBb&pc=GitHubSignUp&utm_source=github&utm_medium=social-media&utm_campaign=github&utm_content=sign-up) for a SparkPost account and visit our [Developer Hub](https://developers.sparkpost.com) for even more content.

# SparkPost API Postman collection

Postman Collection demonstrating how to use the [SparkPost](https://www.sparkpost.com/) REST API.
More information about the API can be found on [developers.sparkpost.com/api](https://developers.sparkpost.com/api/).

## Installation

To use the latest published version, click the following button to import the SparkPost API as a collection:

[![Run in Postman](https://s3.amazonaws.com/postman-static/run-button.png)](https://app.getpostman.com/run-collection/5d9ae743a661a15d64bb)

You can also download the collection file from this repo, then import directly into Postman.

### Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).
- *SparkPost API key* To use our API, you must have an API key with permissions enabled for which resource you want to use. For instance, for the Metrics endpoints, your API key must have the "Metrics: Read-only" permission.

## Usage

The collection is arranged in folders according to the API endpoints.

Almost all requests require a valid SparkPost API key.  The collection requests have a placeholder variable called `API_KEY` for this.
This should be set in your [Postman environment](https://www.getpostman.com/docs/v6/postman/environments_and_globals/manage_environments) i.e. outside the collection itself. This should help avoid accidental commits of API keys to repos.

A collection-scope variable `BASE_URL` points to the usual host `https://api.sparkpost.com`.

SparkPost Enterprise customers and SparkPost EU customers can override this in your Postman environment to point to the [appropriate host](https://developers.sparkpost.com/api/index.html#header-api-endpoints).
For instance, if you are a SparkPost EU customer, you set the Postman environment variable `BASE_URL` to `https://api.eu.sparkpost.com`.

More information on managing Postman environments and variables can be found [here](https://www.getpostman.com/docs/v6/postman/environments_and_globals/variables).

|Variable  |Default value               |Set in         |May override in  |Example|
|----------|----------------------------|---------------|-----------------|-------|
|`API_KEY` |-                           |Environment    |-                |-      |
|`BASE_URL`|`https://api.sparkpost.com` |Collection     |Environment      |`https://api.eu.sparkpost.com`|

### Contribute

We welcome your contributions!  See [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to help out.

### Change Log

[See ChangeLog here](CHANGELOG.md)

## See Also

[SparkPost API documentation](https://developers.sparkpost.com/api/)

[Postman API development tool](https://www.getpostman.com/)