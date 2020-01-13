## Code of Conduct

This project and everyone participating in it is governed by the [Justice Hub Code of Conduct](https://github.com/justicehub-in/Justice-Hub/blob/master/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior to [judiciary@civicdatalab.in](mailto:judiciary@civicdatalab.in).

## If you have questions:

* You can write us at [judiciary@civicdatalab.in](mailto:judiciary@civicdatalab.in).
* Start a discussion on our [Project Taiga Board](https://taiga.civicdatalab.in/project/apoorv-justice-data-hub/issues).
* Use [this template](https://github.com/justicehub-in/Justice-Hub/blob/master/.github/ISSUE_TEMPLATE/question.md) to create a new issue in this repository.

`NOTE: Please avoid creating github issues for questions related to the usage of the platform, you can ask them on the Taiga Board or write to us instead.`

## Setting up your Dev env
Please refer to the [wiki]().  
[TBD: add wiki link when page added.]

## Workflow

* Create an issue for a feature/bug.
* Discuss the implementation on the issue itself while attaching the supporting docs there.
* Create a new branch for the issue.
* Code in the branch.
* Open a PR using [this template](https://github.com/justicehub-in/Justice-Hub/blob/master/.github/PULL_REQUEST_TEMPLATE/pull_request_template.md) with the very first commit and add a WIP prefix to the title of the PR. e.g. `WIP: Fix #1 - add base project structure with spiders.`
* When finished with the implementation, request reviews and remove the WIP prefix.
* If approved, merge the branch. If you are merging from your local CLI(instead of Github UI), make sure your merge commit message contain `Fix #1` (for our example, the issue number is 1, replace it with whatever issue number you worked on).
* Go back and check if your issue is closed or not, if not just close it with a reference to the PR which closes it and then go ahead and delete the branch.

### Branching Model

* Protect Master Branch  
  Resources:
  * [Defining the mergeability of PRs](https://help.github.com/en/articles/defining-the-mergeability-of-pull-requests)

* Branches should be created with respect to issues with the name convention as:

      <feature_name-#issue_number> e.g. scraper-#1.


## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line
- When only changing documentation, include [ci skip] in the commit title
- Consider starting the commit message with an applicable emoji:

    - :art: `:art:` when improving the format/structure of the code
    - :racehorse: `:racehorse:` when improving performance
    - :non-potable_water: `:non-potable_water:` when plugging memory leaks
    - :memo: `:memo:` when writing docs
    - :bug: `:bug:` when fixing a bug
    - :fire: `:fire:` when removing code or files
    - :green_heart: `:green_heart:` when fixing the CI build
    - :white_check_mark: `:white_check_mark:` when adding tests
    - :lock: `:lock:` when dealing with security
    - :arrow_up: `:arrow_up:` when upgrading dependencies
    - :arrow_down: `:arrow_down:` when downgrading dependencies
    - :shirt: `:shirt:` when removing linter warnings

### Python Styleguide

* We really like [Google's Python Styleguide](https://google.github.io/styleguide/pyguide.html).
  * Do not miss the `pylint` specific instructions.
* We try to stick to [Pep8](https://pep8.org/) as much as possible.

### Documentation Styleguide

* Use [Markdown](https://daringfireball.net/projects/markdown/).
* [Don’t document your code. Code your documentation.](https://medium.com/@morillas/dont-document-your-code-code-your-documentation-5b940357a829)
* [How to document source code responsibly.](https://medium.com/@andrewgoldis/how-to-document-source-code-responsibly-2b2f303aa525)
* [The Hitchhiker's guide to Documentation.](https://docs.python-guide.org/writing/documentation/)
* [A beginner’s guide to writing documentation.](https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/)

## How to lint locally

* [Integrating pylint in your workflow.](https://github.com/CivicDataLab/hp-fiscal-data-explorer-backend/wiki/Integrate-code-linting-to-your-workflow)

`NOTE: Any PR that needs to be merged must get a score > 8 to be passed from CI pipeline.`

## Testing
[TBD: add test instructions]

## Additional Notes

### Issues and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests.
Please open an issue on `justicehub-in/Justice-Hub` if you have suggestions for new labels,
and if you notice some labels are missing on some repositories, then please open an issue on that repository.

#### Type of Issue and Issue State
[TBD: Add table, [ref](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#type-of-issue-and-issue-state)]

#### Pull Request Labels
[TBD: Add table, [ref](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#pull-request-labels)]
