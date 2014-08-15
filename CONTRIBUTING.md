Thanks for contributing to `git-hooks`!

# Writing good issues

If you're filing an bug report, it would be helpful to know:

* the operating system you're running (try running `uname -a`)
* which version of bash you're running (`/usr/bin/env bash --version`),
* which version of Git you're running (`git --version`),
* If you're getting errors from an external program (e.g.: `find`, `grep`), which version you're using

# Contributing code

To set up your development environment,

1. [Fork the repository](https://help.github.com/articles/fork-a-repo).

	Don't forget to configure Git to sync your fork with the original `git-hooks` repository!
2. Clone your fork
3. Run `git hooks --install` (yes, this project has it's own git-hooks! :smile:)

## Working on your feature

Before making any commits, create a branch to put your changes in with `git checkout -b short_description_of_change`


* If you add a file, make sure to put the BSD license at the top of it!
* When you make a commit, don't forget to sign off on it (`git commit --signoff`) to signify you're okay with licensing your changes under the BSD license.

## Sharing your work

1. Make sure you're on the branch you want to publish: `git checkout short_description_of_change`
2. Push your branch to your fork: `git push -t origin short_description_of_change`
2. [Create a pull request](https://help.github.com/articles/creating-a-pull-request).
