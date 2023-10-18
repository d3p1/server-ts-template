<div align=center>

# [SERVER TS TEMPLATE]

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![build](https://github.com/d3p1/server-ts-template/actions/workflows/build.yml/badge.svg)](https://github.com/d3p1/server-ts-template/actions/workflows/build.yml)
[![release](https://github.com/d3p1/server-ts-template/actions/workflows/release.yml/badge.svg)](https://github.com/d3p1/server-ts-template/actions/workflows/release.yml)

</div>

## Introduction

A [repository aimed at serving as a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) to implement projects using [TypeScript](https://www.typescriptlang.org/) on the server side, providing basic configurations for using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), [Prettier](https://prettier.io/), [ESLint](https://eslint.org/), and [Jest](https://jestjs.io/). It also includes a setup for use within a [Dev Container](https://code.visualstudio.com/docs/devcontainers/containers), featuring optimized [VSCode](https://code.visualstudio.com/) configurations for working with these technologies. Lastly, it incorporates [GitHub Actions](https://github.com/features/actions) that automate the project [build](./.github/workflows/build.yml) and [release](./.github/workflows/release.yml).

## Usage

In order to proceed with using this template, you need to:

1. [Create a repository from this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
2. Adjust the following values in the default [`package.json`](./package.json):
    - `name`
    - `version` (it's recommended to use `0.0.0` so that the [release workflow](./.github/workflows/release.yml) can adjust it)
    - `description`
    - `private`
    - `repository.url`
    - `keywords`
    - `bugs.url`
    - `homepage`
    - `license` (if necessary)
3. Remove the [`CHANGELOG.md`](./CHANGELOG.md)
4. Modify the [`LICENSE`](./LICENSE) file (if necessary)
5. Edit the [`README.md`](./README.md). Update texts and create new badges for [build workflow](./.github/workflows/build.yml) and [release workflow](./.github/workflows/release.yml) since they currently point to the template repository
6. Run `npm install` to install the dependencies
7. You can now start working in `./src` using the files there as templates and/or creating new ones

> **Note**
> Enable [code scanning with CodeQL](https://docs.github.com/en/code-security/code-scanning/enabling-code-scanning/configuring-default-setup-for-code-scanning)

> **Warning**
> The [release workflow](./.github/workflows/release.yml) uses a bot that needs to have write access to the repository to create new releases, tags, and the `CHANGELOG.md`. If you are using a personal repository, to allow the bot to work smoothly, you shouldn't protect the branch. If you are using an organization's repository, [you can protect the branch and add the bot as an owner to enable it to perform its tasks](https://github.com/semantic-release/github/issues/175#issuecomment-484964034))

## Changelog

Detailed changes for each release are documented in [`CHANGELOG.md`](./CHANGELOG.md).

## License

This work is published under [MIT License](./LICENSE).

## Author

Always happy to receive a greeting on:

- [LinkedIn](https://www.linkedin.com/in/cristian-marcelo-de-picciotto/)
- [Web](https://d3p1.dev/)
