# A template repository for Python <!-- omit in toc -->

This repository provides a template for a Python project with [Hatch].

- [Features](#features)
- [Usage](#usage)
- [License](#license)

## Features

- [pre-commit] of linting([flake8]), formatting([black], [isort]) and more)
- pytest ([pytest], [pytest-cov], [pytest-describe] and [pytest-mock])
- Type checking([mypy])
- GitHub Actions workflows ([test](./.github/workflows/test.yml) and [release-drafter][release-drafter])
- [Dependabot] for GitHub Actions and Python dependencies

## Usage

Use it for [GitHub Template Repository][github-template-repository].

## License

[MIT License](./LICENSE)

Copyright (c) 2023 Shuhei Nitta

[hatch]: https://hatch.pypa.io/latest/
[pre-commit]: https://pre-commit.com/
[flake8]: https://flake8.pycqa.org/en/latest/
[black]: https://black.readthedocs.io/en/stable/
[isort]: https://pycqa.github.io/isort/
[mypy]: https://mypy.readthedocs.io/en/stable/
[pytest]: https://docs.pytest.org/en/stable/
[pytest-cov]: https://pytest-cov.readthedocs.io/en/latest/
[pytest-describe]: https://github.com/pytest-dev/pytest-describe
[pytest-mock]: https://pytest-mock.readthedocs.io/en/latest/
[poetry-dynamic-versioning]: https://github.com/mtkennerly/poetry-dynamic-versioning
[release-drafter]: https://github.com/release-drafter/release-drafter
[dependabot]: https://docs.github.com/en/code-security/dependabot
[github-template-repository]: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository
