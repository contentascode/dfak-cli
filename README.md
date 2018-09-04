[![Travis](https://img.shields.io/travis/contentascode/dfak-cli.svg)](https://travis-ci.org/contentascode/dfak-cli) [![npm](https://img.shields.io/npm/dt/dfak-cli.svg)](https://www.npmjs.com/package/dfak-cli) [![GitHub license](https://img.shields.io/github/license/contentascode/dfak-cli.svg)](https://github.com/contentascode/dfak-cli/blob/master/LICENSE)

# Digital First Aid Kit Content as Code CLI tool

Activist Apprentice is...

Command line tool to manage content workflows for the Apprentice project. It uses the content as code framework.

- [Features](#features)
- [Install](#install)
- [Usage](#usage)
- [Links](#links)

## Features

This tool currently enables users to:

  - Deploy and navigate a local version of the DFAK content.
  - Customise DFAK content locally and preview changes.
  - Contribute back your changes

## Install

### Prerequisites

  - Install `nvm` (cf. https://github.com/creationix/nvm#install-script)

    - `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash`
    - Open a new Terminal window and check if nvm is installed correctly:
      - `command -v nvm`

  - Install `node` v8.11.4 with `nvm`

    - `nvm install v8.11.4`
    - `nvm alias default v8.11.4`
    - Check your version of node with: `node --version`

  - Install `npm` v6.4.1

    - `npm i -g npm`
    - Check your npm version : `npm --version`

  - Install `docsmith` v0.8.2:

    - `npm i -g docsmith@beta`

  - Install `pandoc` 1.19
    - `brew install pandoc`
    - `apt-get install pandoc`

### DFAK Command Line Interface Tool (CLI)

You can now install the CLI with:

```bash
npm i -g dfak-cli
```

### Initialise workspace

```bash
mkdir workspace
cd workspace
dfak init
```

## Usage

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
