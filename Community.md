---
layout: pages
title: Community
---

[![Build Status](https://travis-ci.org/radicalbit/NSDb.svg)](https://travis-ci.org/radicalbit/NSDb){:class="img-licence"}
[![codecov](https://codecov.io/github/radicalbit/NSDb/coverage.svg?branch=master)](https://codecov.io/github/radicalbit/NSDb?branch=master){:class="img-licence"}
[![License](https://img.shields.io/github/license/radicalbit/NSDb.svg)](https://github.com/radicalbit/NSDb/blob/master/LICENSE){:target="_blank"}{:class="img-licence"}

## Reporting Issues

In the [GitHub issue Page](https://github.com/radicalbit/nsdb/issues){:target="_blank"}, you can find a list of tasks to be implemented or bugs already discovered.

## Support

Users and contributors can simply ask questions by [dropping a line](mailto:info@nsdb.io).

The best place to ask for help, to discuss bugs, improvements and contribution is the [Slack WorkSpace](https://nsdbworkspace.slack.com/)

___
## Documentation

* Read more about the [design and architecture](/Architecture) of the project.

___
## Contributing

If you're feeling courageous enough and want to contribute to NSDb You are very welcome!

When you find a new bug, you can open a new issue making sure that:
- a brief description and a path to replicate it is provided.

If you want to propose a new feature or if you are not sure that what you need is a bug or a feature:
- Write an email about your idea at [nsdb.io](mailto:info@nsdb.io) or ask for feedback on the project slack channel. We will help you to analyze your issue and discuss together how to proceed.

Before submitting a pull request (PR), please follow these guidelines:

* A PR must be always associated with a task or a bug, thus make sure that title starts with the issue code and that the issues are linked in the description.
* Make sure to follow this naming convention when opening a new branch for a PR:
  - `bugfix/[PR Code]` for a bug.
  - `feature/[PR Code]` for a new feature.
* Execute tests locally by running `sbt clean test multi-jvm:test it:test`. Besides tests are executed successfully, this guarantees that:
  - the code is properly formatted (by the scalafmt plugin).
  - license headers are generated on each java or scala file created.
* Make sure to add or update documentation according to the changes that are being submitted.
* Make sure to add all the necessary tests that cover the bug or the new feature provided in the PR.
* Do not use author tags in the code.
* PR must not have conflicts with the master branch.
