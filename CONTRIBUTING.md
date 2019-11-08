# Contributing Guidelines

The following is a set of guidelines for contributing to the project. These are 
mostly guidelines, not rules. Feel free to propose changes to this document in a
pull request. 

## General

We welcome all contributions to this project, no matter how small. But please
keep a few things in mind when you do contribute:

* Please leave the place nicer than you found it. If something can be made
  simpler or more readable, please make the change.
* While all contributions are welcome, not all will be accepted. This may be for
  any number of reasons, including work that is not aligned with the goal of the
  project, work that introduces unnecessary complexity, and a number of other 
  reasons
* If you are providing feedback on another's contribution, please remember that
  there is a human on the other side of your computer and strive to be:
    * Kind
    * Respectful
    * Constructive

## Branching Strategy

We use a single branch branching strategy where all branches
are made from `master` and and merge back into `master`. Branches should be
named according to the type of work they are - `feature`, `hotfix`, `bugfix`, 
accompanied by the ticket number and a short description. Examples of acceptable
branch names:

* `feature/abc-123-rule-the-world`
* `hotfix/abc-124-fix-the-world`

More detailed documentation of this can be found inc [Confluence][confluence]

## Pull Requests

We have a pull request template that will guide you through the process of 
creating an appropriate pull request. Prior to raising a pull request you should:

1. Make sure existing tests pass
2. Add any new tests that are required to test the changes you have made
3. Be sure there isn't already a pull request in place that address the issue

   
## Styleguides

### Coding Styleguides

* TBD

### Git Commit Messages

We use [Conventional Commits][conv-commits] to ensure consistency of commit 
messages.

A compliant commit looks like this:

```
<type>(optional scope): <description>

<optional body>
```

* The first line of the commit becomes the subject line
* Don't capitalize the first letter of the description
* Use the imperative mood ("add feature" not "adds feature")
* Use present tense ("add feature" not "added feature")
* No period (.) at the end of the subject line
* Limit the subject line to 72 characters or less.

To assist with writing acceptable commits, we have implemented 
[commitizen][commitizen], which will walk you through the process of creating a 
good commit message. It can be used by running `yarn commit` or `npm run commit`


[conv-commits]: https://www.conventionalcommits.org/en/v1.0.0-beta.3/
[commitizen]: https://github.com/commitizen/cz-cli
[confluence]: https://google.com/