# Contributing Guidelines

The following is a set of guidelines for contributing to the project. These are mostly guidelines, not rules.
Feel free to propose changes to this document in a pull request. 

## General

* Please make sure that there aren't existing pull requests attempting to address the issue mentioned
* Develop in a feature/hotfix/bugfix branch, **not MASTER** 
* Branches should be named according to our branching strategy: `/type/TICKET-NUM-short-name`, e.g `feature/ABC-123-rule-the-world`

## Pull Requests

We have a pull request template that will guide you through the process of 
creating an appropriate pull request. Prior to raising a pull request you should:

1. Make sure existing tests pass
2. Add any new tests that are required to test the changes you have made

   
## Styleguides

### Coding Styleguides

* TBD

### Git Commit Messages

We use [Conventional Commits][conv-commits] to ensure consistency of commit messages.
To assist with this, we have implemented  while will walk
you through crafting a compliant commit message.

A compliant commit looks like this:

```
<type>(optional scope): <description>

<optional body>
```

* The first line of the commit becomes the subject line
* Don't capitalize the first letter of the description
* Use the imperative mood ("move cursor to..." not "moves cursor to...")
* Use present tense ("add feature" not "added feature")
* No period (.) at the end of the subject line
* Limit the subject line to 72 characters or less.

To assist with writing acceptable commits, we have implemented [commitizen][commitizen],
which will walk you through the process of creating a good commit message. It can
be used by running `yarn commit` or `npm run commit`


[conv-commits]: https://www.conventionalcommits.org/en/v1.0.0-beta.3/
[commitizen]: https://github.com/commitizen/cz-cli