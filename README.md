# django-scaffold

The objective of this project is to provide a quick basic setup for a python project. `git clone` and make it yours!


# Table of Contents
- [Prerequisites](#prerequisites)
  - [Install software](#install-software)
- [Get up and running](#get-up-and-running)
- [Configure VS Code](#configure-vs-code)


## Prerequisites

### Install software
- [git](https://git-scm.com/downloads)
- [pyenv - _optional_](https://github.com/pyenv/pyenv)
- [VS Code - _optional_](https://code.visualstudio.com/download)


## Get up and running

Follow the below steps to get up and running. **NOTE**: It assumes that you have installed Python and configured git. If you are using pyenv, `.python-version` file will be used.

1. Clone the repository.
```sh
git clone git@github.com:zen-code-symphony/py-basic-scaffold.git && cd py-basic-scaffold
```
2. Create virtual environment, activate it, install dependencies, and setup pre-commit hooks.
```sh
make init
```
3. Check available `make` targets
```sh
make init
```

## Configure VS Code
  - As part of VS Code workspace extensions recommendations, the extensions mentioned in [.vscode/extensions.json](./.vscode/extensions.json), should be installed. This includes extensions for flake8, black, isort etc.
  - Make sure that you are using the workspace settings mentioned in repository file [.vscode/settings.json](./.vscode/settings.json). `CTRL+,` and open `Workspace` settings tab to check.
