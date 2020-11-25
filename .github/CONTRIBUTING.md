# Contributing to 

This outlines how to propose a change to . 

## Fixing typos

You can fix typos, spelling mistakes, or grammatical errors in the documentation directly using the GitHub web interface, as long as the changes are made in the _source_ file. 

## Bigger changes

If you want to make a bigger change, it's a good idea to first file an issue and make sure someone from the team agrees that it’s needed. 
If you’ve found a bug, please file an issue that illustrates the bug with a minimal 
[reprex](https://www.tidyverse.org/help/#reprex) (this will also help you write a unit test, if needed).

### Pull request process

*   Fork the package and clone onto your computer. If you haven't done this before, we recommend using `usethis::create_from_github("AOSCD/aoscd-matlab", fork = TRUE)`.

*   Create a Git branch for your pull request (PR). 

*   Make your changes, commit to git, and then create a PR by running `usethis::pr_push()`, and following the prompts in your browser.
    The title of your PR should briefly describe the change.
    The body of your PR should contain `Fixes #issue-number`.

## Code of Conduct

Please note that the  project is released with a
[Contributor Code of Conduct](https://github.com/AOSCD/aoscd-matlab/blob/main/CODE_OF_CONDUCT.md). By contributing to this project you agree to abide by its terms.
