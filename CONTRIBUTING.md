Contributing
============

Thank you for contributing to this project!

Bug reports
-----------

If you find a bug, please submit an issue. Try to be as detailed as possible
in your problem description to help us fix the bug.

Feature requests
----------------

If you wish to propose a feature, please submit an issue. Try to explain your
use case as fully as possible to help us understand why you think the feature
should be added.

Creating a pull request (PR)
----------------------------

First [fork the repository](https://help.github.com/articles/fork-a-repo/) on
GitHub.

Then clone your fork:

```bash
$ git clone https://github.com/your-name/repo-name.git
$ git checkout -b bug-or-feature-description
```

And install the dependencies:

```bash
$ composer install
```

Write your code and add tests. Then run the tests:

```bash
$ composer test
```

Commit your changes and push them to GitHub. Please write your commit messages
in the imperative and follow the [guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
for clear and concise messages:

```bash
$ git commit -m "Fix nasty bug"
$ git push -u origin bug-or-feature-description
```

Then [create a pull request](https://help.github.com/articles/creating-a-pull-request/)
on GitHub.

If you need to make some changes, commit and push them as you like. When asked
to squash your commits, do so as follows:

```bash
git rebase -i
git push origin bug-or-feature-description -f
```

Coding standard
---------------

This project follows the [PSR-2](http://www.php-fig.org/psr/psr-2/) coding style.
Please make sure your pull requests adhere to this standard.
