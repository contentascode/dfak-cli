[![Travis](https://img.shields.io/travis/contentascode/dfak-cli.svg)](https://travis-ci.org/contentascode/dfak-cli) [![npm](https://img.shields.io/npm/dt/dfak-cli.svg)](https://www.npmjs.com/package/dfak-cli) [![GitHub license](https://img.shields.io/github/license/contentascode/dfak-cli.svg)](https://github.com/contentascode/dfak-cli/blob/master/LICENSE)

# Digital First Aid Kit Content as Code CLI tool

Activist Apprentice is...

Command line tool to manage content workflows for the Apprentice project. It uses the content as code framework.

- [Features](#features)
- [Install](#install)
- [Usage](#usage)
- [Links](#links)

## Features

A quick walk through...

[![IMAGE ALT TEXT HERE]()]()

## Install

### Prerequisites:

- [node v6 minimum, v8.9 LTS recommended](https://nodejs.org/en/)

  - MacOS note that installation via `brew` is not yet supported.

- npm v6.4.0

  - `npm i -g npm`

- docsmith v0.8.0:

  - `npm i -g docsmith@beta`

- pandoc 1.19
  - `brew install pandoc`
  - `apt-get install pandoc`

### Prerequisites for APK build

The following are only required if you wish to use the `dfak build mobile` command which will generate an APK for your project.

- exp v54.0.1:

  - `npm i -g exp`

- docker:
  - https://docs.docker.com/docker-for-mac/install/
  - make sure that you set Docker to minimum **8GB** memory (Docker icon > Preferences > Advanced).

### DFAK Command

You can now install the CLI with:

```bash
npm i -g dfak-cli
```

## Usage

```bash
mkdir workspace
cd workspace
dfak init
```

This will prompt you with a few questions about configuration. The defaults should work in the majority of cases.

```bash
dfak start
```

This will start the preview server and watch your local files for changes. You can open your browser at `http://localhost:8081` to browse the preview.

## Editor

The recommended text editor is Atom https://atom.io together with the following packages:

- [markdown-preview-enhanced](https://atom.io/packages/markdown-preview-enhanced)
- [linter](https://atom.io/packages/linter)
- [linter-ui-default](https://atom.io/packages/linter-ui-default)
- [linter-remark](https://atom.io/packages/linter-remark)

## Links

- Related repositories
  - `dfak` content package https://github.com/iilab/DFAK
  - Content as code https://github.com/iilab/contentascode
  - CLI Framework https://github.com/docsmith/docsmith
