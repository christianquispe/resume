<!--


  ** DO NOT EDIT THIS FILE
  **
  ** 1) Make all changes to `provision/generator/README.yaml`
  ** 2) Run`task readme` to rebuild this file.
  **
  ** (We maintain HUNDREDS of open source projects. This is how we maintain our sanity.)
  **


  -->

[![Latest Release](https://img.shields.io/github/release/christianquispe/resume)](https://github.com/christianquispe/resume/releases) [![Lint](https://img.shields.io/github/workflow/status/christianquispe/resume/lint-code)](https://github.com/christianquispe/resume/actions?workflow=lint-code) [![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow)](https://conventionalcommits.org) [![KeepAChangelog](https://img.shields.io/badge/changelog-Keep%20a%20Changelog%20v1.0.0-orange)](https://keepachangelog.com)

# resume-template

An elegant [LaTeX](https://www.latex-project.org/) resume template, compiled with [XeLaTeX](https://www.overleaf.com/learn/latex/XeLaTeX)

## Features

- Easy to be further customized or extended
- Full support for unicode characters
- FontAwesome 5 support

## Requirements

This is a list of applications that need to be installed previously to enjoy all the goodies of this configuration:

- [Pyenv](https://github.com/pyenv/pyenv)
- [Docker](https://www.docker.com/)

## Usage

# How to use this project

## replace name

```bash
agr 'christianquispe/resume' 'owner/resume'
agr 'Resume' 'Resume'
```

```bash
task xelatex.resume
```

## References

For additional context, refer to some of these links.

- [billryan resume](https://github.com/billryan/resume) - Inspiration

## Help

**Got a question?**

File a GitHub [issue](https://github.com/christianquispe/resume/issues).

## Contributing

See [Contributing](./docs/contributing.md).

## Module Versioning

This Module follows the principles of [Semantic Versioning (SemVer)](https://semver.org/).

Using the given version number of `MAJOR.MINOR.PATCH`, we apply the following constructs:

1. Use the `MAJOR` version for incompatible changes.
1. Use the `MINOR` version when adding functionality in a backwards compatible manner.
1. Use the `PATCH` version when introducing backwards compatible bug fixes.

### Backwards compatibility in `0.0.z` and `0.y.z` version

- In the context of initial development, backwards compatibility in versions `0.0.z` is **not guaranteed** when `z` is increased. (Initial development)
- In the context of pre-release, backwards compatibility in versions `0.y.z` is **not guaranteed** when `y` is increased. (Pre-release)

## Copyright

Copyright © 2018-2022 [Hadenlabs](https://hadenlabs.com)

## Trademarks

All other trademarks referenced herein are the property of their respective owners.

## License

The code and styles are licensed under the LGPL-3.0 license [See project license.](LICENSE).

## Don't forget to 🌟 Star 🌟 the repo if you like resume-template

[Your feedback is appreciated](https://github.com/christianquispe/resume/issues)
