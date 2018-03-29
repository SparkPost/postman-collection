# Contributing to this project

Transparency is one of our core values, and we encourage developers to contribute and become part of the SparkPost developer community.

The following is a set of guidelines for contributing,
which is hosted in the [SparkPost Organization](https://github.com/sparkpost) on GitHub.
These are just guidelines, not rules, use your best judgment and feel free to
propose changes to this document in a pull request.

## Submitting Issues

* Before logging an issue, please [search existing issues](https://github.com/SparkPost/sparkpost-api-postman-collection/issues?q=is%3Aissue+is%3Aopen) first.

* You can create an issue [here](https://github.com/SparkPost/sparkpost-api-postman-collection/issues/new).  Please include the version number (as per [the changeLog](CHANGELOG.md) and as much detail as possible in your report.

## Local Development and Testing

1. Fork this repo
1. Clone your fork
1. Import the JSON file into Postman, choosing to "replace" any existing collection of the same name
1. Make and test your changes
1. When you are ready, export your changes from Postman back to a new JSON file
1. Compare the differences using a file-compare utility, to ensure no unexpected changes and no private API key info present
1. Copy your new version to the repo file
1. Please follow the pull request submission steps in the next section

## Contribution Steps

To contribute to sparkpost-api-postman-collection:

1. Create a new branch named after the issue you’ll be fixing (include the issue number as the branch name, example: Issue in GH is #8 then the branch name should be ISSUE-8))
1. Submit a new Pull Request applying your feature/fix branch to the `master` branch

### Releasing

To publish a new release:

1. Update the [ChangeLog](CHANGELOG.md)
1. Internal SparkPost team follows [these steps](https://confluence.int.messagesystems.com/display/ENG/SparkPost+Public+Postman+Collection)
1. Ensure SparkPost [documentation](https://github.com/SparkPost/sparkpost-api-documentation) refers to URL of updated version