[![Code Style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

# blog.tigrisdata.com

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern
static website generator.

## Prerequisites

[Node.js](https://nodejs.org/en/download/) version >= 14 or above (which can
be checked by running node -v).

## Installation

```shell
npm install
```

## Local Development

```shell
npm run start
```

This command starts a local development server and opens up a browser window.
Most changes are reflected live without having to restart the server.

## Build

```shell
npm run build
```

This command generates static content into the `build` directory and can be
served using any static contents hosting service.

# # Code Quality

## 1. Linting

The coding style rules are defined by [Prettier](https://prettier.io/) and
enforced by [Eslint](https://eslint.org)

## 2. Git Hooks

We use [pre-commit](https://pre-commit.com/index.html) to automatically
setup and run git hooks.

On every `git commit` we check the code quality using prettier and eslint.