# sparkpost-api-postman-collection

This repository contains the Postman Collection demonstrating how to use the [SparkPost](https://www.sparkpost.com/) REST API. More information about the API can be found on [developers.sparkpost.com/api](https://developers.sparkpost.com/api/).

## Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).
- *SparkPost API key* To use our API, you must have an API key with permissions enabled for which resource you want to use. (For instance, for the Metrics endpoints, your API key must have the "Metrics: Read-only" permission.)

## Installation

To use the latest published version, you can click the following button to import the SparkPost API as a collection:

[![Run in Postman](https://s3.amazonaws.com/postman-static/run-button.png)](https://www.getpostman.com/run-collection/81ee1dd2790d7952b76a)

## Using Postman variables

Almost all requests require a valid SparkPost API key. Once you have one, you need to create a Postman variable called `API_KEY` and set the value as your API key.

The Postman collection is set up to point to the `https://api.sparkpost.com`. If you are a SparkPost enterprise customer or a SparkPost EU customer, you can override the `BASE_URL` Postman variable to point to the appropriate host using Postman environments. For instance, if you are a SparkPost EU customer, you can create a Postman environment and set the environment variable `BASE_URL` to https://api.eu.sparkpost.com . More information on managing Postman environments and variables can be found [https://www.getpostman.com/docs/v6/postman/environments_and_globals/variables](here).

## The Collection

The SparkPost Postman collection demonstrates the SparkPost REST API and is arranged in folders according to the API endpoints:

- A/B testing (Sparkpost Labs feature)
- Account
- Inbound Domains
- IP Pools
- Message Events
- Metrics
- Recipient Lists
- Relay Webhooks
- Sending Domains
- Sending IPs
- Subaccounts
- Suppression List
- Templates
- Tracking Domains
- Transmissions
- Webhooks

## See Also
[SparkPost API documentation](https://developers.sparkpost.com/api/)

[Postman API development tool](https://www.getpostman.com/)