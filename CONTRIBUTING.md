# Contributing to Techramento

If you're reading this, you are probably looking to find out how to contribute
to Techramento. You've come to the right place! Thanks for taking the time to
contribute!

The following is a set of guidelines for contributing to the Techramento site
as well as our operations and our community. These are just guidelines, not
rules, use your best judgement and feel free to propose changes to this
document in a pull request.

This project adheres to the [Contributor Covenant 1.2](http://contributor-covenant.org/version/1/2/0/) and our community interactions adhere to our
[Code of Conduct](https://github.com/techramento/techramento.github.io/blob/master/CODE_OF_CONDUCT.md). Please report unacceptable behavior to any of our core
contributors.

## Submitting Issues or Changes

Please [create a GitHub Issue](https://github.com/techramento/techramento.github.io/issues/new)
or [send a GitHub Pull Request](http://help.github.com/pull-requests/) with a
clear indication of what you're reporting or a list of what you've done. Please
follow our commit conventions and our coding conventions listed below.

## Commit Conventions

  * Use the present tense ("Add feature" not "Added feature")

  * Use the imperative mood ("Move cursor to..." not "Moves cursor to...")

  * Follow the [50/72 line length rule](http://stackoverflow.com/questions/2290016/git-commit-messages-50-72-formatting) where possible

  * Always write a clear log message for your commits

    One-line messages are fine for small changes, but bigger changes should look like this:

        $ git commit -m "A brief summary of the commit
        >
        > A paragraph describing what changed and its impact."

  * Reference issues and pull requests liberally using [GitHub's built-in Issues keywords](https://help.github.com/articles/closing-issues-via-commit-messages/)

  * In order to keep the project history readable, Pull Request commits should
    be squashed into as few atomic commits as makes sense given the nature of
    the change and the complexity of the steps needed to accomplish it

For more information on writing high-quality commit messages, we recommend
checking out Ryan McGeary's lightning talk, ["Do
Your Commit Messages Suck"](http://ryan.mcgeary.org/2011/09/02/do-your-commit-messages-suck-rockymtnruby/)
from Rocky Mountain Ruby 2011.

## Coding Conventions

Keeping a project's code consistent between authors and through time increases
the quality of the project. The following coding conventions will ensure that
all contributions are consistent throughout the project:

  * For simple, content-driven pages, we use [Markdown](https://daringfireball.net/projects/markdown/)

  * For more complex layouts, we use HTML

  * All CSS follows the [SUIT CSS naming conventions](https://github.com/suitcss/suit/blob/master/doc/naming-conventions.md)

  * End files with at least one, and no more than one, newline

  * Alphabetize configuration settings, functions, variable declarations, and
    CSS styles where possible

  * All Ruby variables should be written in `snake_case` and all Javascript
    variables in `camelCase`

  * First lines of Markdown List items should avoid ending with a period "."

  * Where possible, avoid automated line wrapping by manually entering line
    breaks so as not to exceed an 80-character line length

This project uses various coding convention tools in order to maintain
consistency across the entire codebase.

Please ensure that your code editor of choice is compatible with, and properly
configured to take advantage of, these tools:

  * [Editor Config](http://editorconfig.org/)

When in doubt, please refer to the rest of the code base for guidance or create
an issue asking for clarification.

## Site Organization

All legal and community guideline documents should be written in Markdown and
stored in the root folder with a `SCREAM_CASE` filename. This makes it easier
for users to quickly find the most important documents in the project.

Legal documents that are publicly facing through the website should contain
[Jekyll-compatible YAML Front Matter](http://jekyllrb.com/docs/frontmatter/)
with a `permalink` value. This ensures that they follow an appropriate URL
hierarchy.

## Making changes

All changes to the project's source code should be made through a Pull Request.
This ensures that the entire staff has the chance to be notified about any
changes to the project.

Where possible, Pull Requests should not be merged by the author. Core
maintainers are encouraged to prompt the other maintainers to review any
proposed change by assigning the Pull Request to a specific member. This helps
ensure that all of the preceeding guidelines are followed in the name of
clarity and openness and pending requests are communicated clearly.

All discussion about the proposed change should be made in the open through
GitHub's Issues interface.

In the event that a Pull Request needs sign off from all Board Members, the
author should add a [Task List](https://github.com/blog/1375%0A-task-lists-in-gfm-issues-pulls-comments)
with the GitHub usernames of all standing Board Members. In a timely manner,
those Board Members are then expected to check the mark next to their name
which will constitute their acceptance of proposed change.

    - [ ] @daprez
    - [ ] @veep
    - [ ] @treasuremoney
    - [ ] @secretariat

