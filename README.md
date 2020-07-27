# dotfiles
Adds scripting support to configure items or install things that do not fit well with homebrew.

This is designed to work with [strap](https://github.com/MikeMcQuaid/strap) using the [scripts to rule them all pattern](https://github.com/github/scripts-to-rule-them-all).

## Supported environment variables
* `GIT_HOST`: the host for git to find repositories (default: `github.com`)
* `GIT_USER`: the user to use for git (default: `$USER`)
* `STRAP_GITHUB_HOST`: the github host to look under for repos these scripts depend on. (default: `github.com`)
* `STRAP_GITHUB_USER`: the github user/org to look under for repos these scripts depend on (default: `gr8routdoors`)
