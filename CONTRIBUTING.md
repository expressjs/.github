# Express Collaborator Guide

## Website Issues

Open issues for the expressjs.com website in https://github.com/expressjs/expressjs.com.

For issues in other Express managed repos (everything in `expressjs`, `pillarjs` or `jshttp` other than `expressjs/express`), be sure to check their contributing guide and open issues and PRs in the appropriate repository.

## PRs and Code contributions

* Tests must pass.
* Follow the [JavaScript Standard Style](https://standardjs.com/) and `npm run lint`.
* If you fix a bug, add a test.

## Branches

Use the `master` branch for bug fixes or minor work that is intended for the
current release stream.

Use the correspondingly named branch, e.g. `6.x`, for anything intended for
a future release of Express.

## Steps for contributing

1. Create an issue for the
   bug you want to fix or the feature that you want to add.
2. Create your own fork on GitHub, then
   checkout your fork.
3. Write your code in your local copy. It's good practice to create a branch for
   each new issue you work on, although not compulsory.
4. To run the test suite, first install the dependencies by running `npm install`,
   then run `npm test`.
5. Ensure your code is linted by running `npm run lint` -- fix any issue you
   see listed.
6. If the tests pass, you can commit your changes to your fork and then create
   a pull request from there. Make sure to reference your issue from the pull
   request comments by including the issue number e.g. `#123`.

## Issues which are questions

We will typically close any vague issues or questions that are specific to some
app you are writing. Please double check the docs and other references before
being trigger happy with posting a question issue.

Things that will help get your question issue looked at:

* Full and runnable JS code.
* Clear description of the problem or unexpected behavior.
* Clear description of the expected result.
* Steps you have taken to debug it yourself.

If you post a question and do not outline the above items or make it easy for
us to understand and reproduce your issue, it will be closed.

If your question meets all of the above requirements but you do not believe it needs to be looked at
by the maintainers
(for example, if you are just looking for community input) please open it as a discussion topic instead
of an issue. If you
are unsure and open an issue, we may move it to discussions if we triage them and decide they do
not need high
visibility or maintainer input. 