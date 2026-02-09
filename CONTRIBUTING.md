# Contributing

This guide is based on [Spatie's guidelines](https://github.com/spatie/.github/blob/main/CONTRIBUTING.md).

Contributions are **welcome** and will be **credited**.

Please read and understand the contribution guide before creating an issue or pull request.

## Background

The Phlib packages are open source, developed by present and past developers at Emailcenter UK Ltd.,
as part of wider projects or in personal time.
They make the code freely available in the hope that it will be of use to other developers.

Please be considerate towards maintainers when raising issues or presenting pull requests.

## Viability

It is the duty of the maintainer to ensure that all submissions to the project are of sufficient quality to benefit the project.

When requesting or submitting new features, first consider whether it might be useful to others.
Open source projects may be used by many developers, who may have entirely different needs to your own.
Some features may be more appropriate as a fork, if they are not likely to be used by other users of the project.

## Procedure

Before filing an issue:

- Attempt to replicate the problem, to ensure that it wasn't a coincidental incident.
- Check to make sure your feature suggestion isn't already present within the project.
- Check the pull requests tab to ensure that the bug doesn't have a fix in progress.
- Check the pull requests tab to ensure that the feature isn't already in progress.

Before submitting a pull request:

- Check the codebase to ensure that your feature doesn't already exist.
- Check the pull requests to ensure that another person hasn't already submitted the feature or fix.

## Requirements

If the project maintainer has any additional requirements, you will find them listed here.

- **[PER Coding Style](https://www.php-fig.org/per/coding-style/)** - Packages are configured to test against EasyCodingStandard, so you should test this manually before pushing commits.

- **Add tests!** - Your patch won't be accepted if it doesn't have tests.

- **Document any change in behaviour** - Make sure the `README.md` and any other relevant documentation are kept up-to-date.

- **Consider our release cycle** - We try to follow [Semantic Versioning](http://semver.org/). Breaking public APIs will typically require a new major version, and should be avoided if possible.

- **One pull request per feature** - If you want to do more than one thing, send multiple pull requests.

- **Send coherent history** - Make sure each individual commit in your pull request is meaningful. If you had to make multiple intermediate commits while developing, please [squash them](http://www.git-scm.com/book/en/v2/Git-Tools-Rewriting-History#Changing-Multiple-Commit-Messages) before submitting.

## PHP versions

As these packages are used as dependencies in other projects, they may continue to offer support for older PHP versions while no API changes are required.
Dropping support for an older PHP version may be done in *minor* version releases, as long as the Phlib package's public API has not changed.

For a more detailed explanation, see these blog posts from
[Sam Partington](https://medium.com/@sampart/semantic-versioning-when-you-change-the-required-programming-language-version-16a3a3555c95) and
[Doctrine](https://www.doctrine-project.org/2017/07/25/php-7.1-requirement-and-composer.html#why-dropping-php-support-in-a-minor-version-is-not-a-bc-break).

**Happy coding**!
