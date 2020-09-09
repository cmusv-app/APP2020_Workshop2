# GitHub Basics

This week we'll be focusing on how to use GitHub (and git in general) effectively. 

## Commit

When you 'commit' code, you are essentially selecting the files you want to update in the repository. Depending on the circumstances, you may not want every change you've made to be reflected in the repository. When you commit code, you also need to add a message. This message describes what you've changed and is especially helpful in cases where a whole team is working on the same codebase. Every team will have different conventions, but here are a few for you to consider for your own project.

#### [add], [fix], [remove]
These are tags you can use to preface your commit message. E.g. "[add] Multi-styled button component"

Doing so makes it easy for a code reviewer to identify the change that someone has commited.

## Push, pull

Once you've committed code, you 'push' it to the repository. When you're 'pushing' you also need to select the branch you are pushing to. 

By default, code is pushed to 'master' - the main branch of the project. However, in larger projects it is not uncommon to have each feature be it's own branch. Doing so makes it easier to merge or revert big changes while maintaining the integrity of the master branch. If you're contributing to a different branch than master, you need to indicate so in the push interface.

A 'pull' is the opposite of a push. It downloads the code from the repository, rather than upload it. So, if you're working on a big project with other developers and the branch you are working on has been updated, you need to pull the changes from the repository to make sure your work is on the newest codebase.

## Pull request
After you've made a number of commits and pushed them to a select branch, it's time to merge them with the master branch. To do so, you need to open a 'Pull Request.'

A 'pull request' tells the manager of the repository that you wish to merge two branches. In a team setting, a pull request would be reviewed by another developer (usually a senior engineer) and then merged. This process can also be used to initiate a series of tests that makes sure the pull request code follows the code standards and conventions set by the team.

## More git information
[Here's a git guide that goes a bit more in depth.](https://rogerdudler.github.io/git-guide/)

## Markdown

Markdown is a markup language (like HTML and XML) that makes it easy to format text. Markdown was used to render this README file, for example, and virtually every open-source codebase uses Markdown for its documentation. 

Markdown is everywhere. Product Managers can use it in Azure Dev Ops to write requirements. Writers use it on Medium and other blogging platforms. It has huge number of use cases and it doesn't take much time to pick up.

[Here's a quick intro to Markdown.](https://www.markdownguide.org/getting-started/)

[And here's a Markdown cheat sheet you can refer to when writing your own Markdown files.](https://www.markdownguide.org/cheat-sheet/)
