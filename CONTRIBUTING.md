# Contributing guide

## Getting started

First, make sure you have `python` installed. You will need to install all the `requirements` using the following command:

-   `pip install -r requirements.txt`

## Branches

Main is protected and requires an approved PR to be merged.
When you want to contribute, you should create a new branch from `main` and name it `feature/your-feature-name` or `fix/your-fix-name`.
Then push your branch and create a PR to merge it into `main`.

## Git Commit Messages

Commits should start with a Capital letter and should be written in present tense (e.g. `:tada: Add cool new feature` instead of `:tada: Added cool new feature`).
You should also start your commit message with one or two applicable emoji. This does not only look great but also makes you rethink what to add to a commit. Make many but small commits!

| Emoji                                                     | Description                                        |
| --------------------------------------------------------- | -------------------------------------------------- |
| :tada: `:tada:`                                           | When you add a cool new feature                    |
| :beetle: `:beetle:`                                       | When you fixed a bug                               |
| :fire: `:fire:`                                           | When you removed something                         |
| :truck: `:truck:`                                         | When you moved/renamed something                   |
| :wrench: `:wrench:`                                       | When you improved/refactored a small piece of code |
| :hammer: `:hammer:`                                       | When you improved/refactored a large piece of code |
| :sparkles: `:sparkles:`                                   | When you improved code quality (pylint, PEP, ...)  |
| :art: `:art:`                                             | When you improved/added design assets              |
| :rocket: `:rocket:`                                       | When you improved performance.                     |
| :memo: `:memo:`                                           | When you wrote documentation.                      |
| :umbrella: `:umbrella:`                                   | When you improved coverage                         |
| :twisted_rightwards_arrows: `:twisted_rightwards_arrows:` | When you merge a branch                            |

This section was inspired by [this repository](https://github.com/schneegans/dynamic-badges-action).