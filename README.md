# Python Project Template

This project is built as a base for further projects. Below are the steps to set up the project using `mise`, 
and how to configure `.secrets.toml` and `.env` files.

## Prerequisites

- mise-en-place `mise` tool 

[Mise-en-place getting started](https://mise.jdx.dev/getting-started.html)

# Setup

1. Run `mise trust` in the root directory of the project. It is needed to leave mise install all the dependencies.
2. Run `mise install` in the root directory of the project. It will install all the dependencies configured in mise.
3. Run `poetry  --with dev,test` in t,he root directory of the project to install the rest of the dependencies.