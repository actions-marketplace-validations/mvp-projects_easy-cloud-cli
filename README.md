# cloud-cli

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v1.json)](https://github.com/charliermarsh/ruff)
[![Build Status](https://github.com/mvp-projects/cloud-cli/workflows/test/badge.svg?branch=main&event=push)](https://github.com/mvp-projects/cloud-cli/actions?query=workflow%3Atest)

-----

**Table of Contents**

- cloud-cli[#cloud-cli]
  - [Inspiration](#inspiration)
  - [How to run?](#how-to-run)

## Inspiration
Nor Pydantic, FastAPI, Ruff, ... seem to use `Poetry` to manage dependencies. In fact, since Poetry's last update to `v1.20` I have encounter quite a few problems running different project. Another huge issue is that `Poetry` does not respect the [PEP 621](https://peps.python.org/pep-0621/) standard which may cause issue when the project interacts with libraries that expect an standard format for the `pyproject.toml` file.

This Template Project does not require any Package Manager, it runs purely with native Python solutions (`.venv`, for example) and sticks with `requirements.txt` files to manage dependencies (Which, btw, is the pythonic way to handle this).

## How to run?
- Create a virtual environment
- Activate the environment
- run `make install env=dev`
