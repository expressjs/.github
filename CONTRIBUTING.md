# Contributing to Express Ecosystem

Thank you for your interest in contributing to the Express ecosystem! This document outlines
how you can contribute to the Express project, including reporting issues, submitting pull requests,
and participating in discussions and more.

Express has a open governance model. For information about the governance of the Express project,
see the [GOVERNANCE.md](https://github.com/expressjs/discussions/blob/HEAD/docs/GOVERNANCE.md)
document.

> [!TIP]
> For new contributors: Take a look at <https://github.com/firstcontributions/first-contributions> for helpful information on contributing

## Code of Conduct

Everyone who participates in this project, either as a user or a contributor, is obliged
to follow the project [Code of Conduct](https://github.com/expressjs/.github/blob/HEAD/CODE_OF_CONDUCT.md).

## Issues

Submitting a pull request is not the only way to contribute to the Express project.
You can also help by reporting issues, providing feedback, and participating in discussions.

### Reporting New Issues

Before opening a new issue, search existing and closed issues to avoid duplicates. If the solution
provided in a previous issue doesn't work, please open a new issue with a clear description of the problem.

Report issues for bugs, documentation improvements, or general enhancements. Please fill out all required
fields in the relevant issue form.

For issues in other express managed repos (everything in `expressjs`, `pillarjs` or `jshttp` other
than `expressjs/express`), be sure to check their contributing guide and open issues and PRs in
the appropriate repository.

#### Providing a reproducible example

A minimal, self-contained example helps others quickly understand and reproduce your issue.

Steps:

1. Isolate the Problem:
   - Reduce your code to the smallest version that reproduces the issue.
   - Remove unrelated code and dependencies.
2. Make It Easy to Run:
   - Avoid requiring special setup (e.g., CI tools, external services).
   - Include clear instructions to run the example.
3. Share It:
   - Push the example to a new public GitHub repo.
   - Share the link in your issue, describing the observed vs. expected behavior.

Note: Issues without a reproducible example may be closed.

#### Security Bugs

If you believe you have found a security vulnerability in a package maintained by the Express project,
please do not open a public issue or pull request. Instead, follow the instructions in the
[Security Policy](https://github.com/expressjs/.github/blob/master/SECURITY.md)

#### Issues which are questions

We will typically close any vague issues or questions that are specific to some
app you are writing. Please double check the docs and other references before
being trigger happy with posting a question issue.

Things that will help get your question issue looked at:

- Full and runnable JS code.
- Clear description of the problem or unexpected behavior.
- Clear description of the expected result.
- Steps you have taken to debug it yourself.

If you post a question and do not outline the above items or make it easy for
us to understand and reproduce your issue, it will be closed.

If your question meets all of the above requirements but you do not believe it needs to be looked at
by the maintainers (for example, if you are just looking for community input), please open it as a discussion
topic instead of an issue. If you are unsure and open an issue, we may move it to discussions if we triage
them and decide they do not need high visibility or maintainer input.

### Triaging Existing Issues

You can help by contributing to issues that need attention.
Check out this [guide](https://github.com/expressjs/discussions/blob/master/docs/contributing/triager-guide.md)
to learn more about the triage process.

### Website and Documentation Issues

There are two main ways you can help improve Express documentation:

- **Repository Documentation Issues:**  
  
   If you spot mistakes or areas for improvement in this repository’s documentation (such as guides, README content, or inline API docs), please open an issue here. Your feedback helps us keep our docs accurate and useful for everyone.

- **Website Documentation Issues:**  

   If you notice errors or have suggestions for the Express website—like problems in guides, API documentation, or other website content—please report them in the [`expressjs/expressjs.com` repository](https://github.com/expressjs/expressjs.com).

We encourage you to participate! Whether you’re fixing a typo or suggesting a new guide, your contributions make a difference. Open an issue in the right place and help us make Express documentation better for the whole community.

## Sending a Pull Request

We actively welcome your Pull Requests! A couple of things to keep in mind before you submit:

- If fixing an issue, ensure no one else has an open PR for it, unless you’re offering a different solution.
Likewise, make sure to link your PR to the related Issue(s).
- We will always try to accept the first viable PR that resolves the Issue.

Prior to submitting your PR, please conduct the following pre-flight checks:

- All tests must pass.
- Code must follow [JavaScript Standard Style](https://standardjs.com/) and pass `npm run lint`
- Bug fixes must include a test, PRs without tests will not be merged.

### Branches

Use the `master` branch for bug fixes or minor work that is intended for the
current release stream.

Use the correspondingly named branch, e.g. `6.x`, for anything intended for
a future release of package.

### Granular PRs

Keep pull requests focused on a single purpose. Don’t mix unrelated changes,
as it makes reviews harder, delays merges, and complicates semantic titles

### Pull Request Reviews

When a PR is not in draft, it is considered ready for review. You do not need to be a maintainer to review or comment on a PR, everyone is welcome to provide constructive feedback and suggestions! If you have time, please check open PRs and help improve the project. Do not manually tag anyone to request a review; a maintainer will assign reviewers as needed.

Before requesting a review, make sure all GitHub checks are passing, unless you have specific questions about a failure.

### Requested Changes

After a maintainer reviews your PR, they may request changes on it. Once you've made those changes,
re-request review on GitHub.

Please try not to force-push commits to PRs that have already been reviewed. Doing so makes it harder
to review the changes. We squash merge all commits so there's no need to try to preserve Git history
within a PR branch.

## Steps for contributing

In short, here’s how to contribute:

1. Create an issue for the
   bug you want to fix or the feature that you want to add.
2. [Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) and clone the repository to your local machine.
3. Create a separate branch for your changes. This is important to keep
   your work organized and to avoid conflicts with the main branch.
   You can do this with `git checkout -b my-feature-branch`.
   Replace `my-feature-branch` with a descriptive name for your branch.
4. Write your code in your local copy.
5. To run the test suite, first install the dependencies by running `npm install`,
   then run `npm test`.
6. Ensure your code is linted by running `npm run lint`, fix any issue you
   see listed.
7. If the tests pass, you can commit your changes to your fork and then create
   a pull request from there. Make sure to reference your issue from the pull
   request comments by including the issue number e.g. `#123`.

## More Resources

- Triager Guide: <https://github.com/expressjs/discussions/blob/master/docs/contributing/triager-guide.md>
- Governance: <https://github.com/expressjs/discussions/blob/master/docs/GOVERNANCE.md>
- Release Guide: <https://github.com/expressjs/discussions/blob/master/docs/contributing/release-process.md>
- Slack: <https://slack-invite.openjsf.org/>

## Developer's Certificate of Origin 1.1

```text
By making a contribution to this project, I certify that:

 (a) The contribution was created in whole or in part by me and I
     have the right to submit it under the open source license
     indicated in the file; or

 (b) The contribution is based upon previous work that, to the best
     of my knowledge, is covered under an appropriate open source
     license and I have the right under that license to submit that
     work with modifications, whether created in whole or in part
     by me, under the same open source license (unless I am
     permitted to submit under a different license), as indicated
     in the file; or

 (c) The contribution was provided directly to me by some other
     person who certified (a), (b) or (c) and I have not modified
     it.

 (d) I understand and agree that this project and the contribution
     are public and that a record of the contribution (including all
     personal information I submit with it, including my sign-off) is
     maintained indefinitely and may be redistributed consistent with
     this project or the open source license(s) involved.
```
