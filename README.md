# UV Python Template

A modern Python project template using [uv](https://github.com/astral-sh/uv) for dependency management and [Copier](https://copier.readthedocs.io/) for project generation.

## Install Copier

Install Copier using pipx (recommended):

```bash
pipx install copier
```

Or using pip:

```bash
pip install copier
```

## Generate a Project With Copier

To create a new project from this template:

```bash
copier copy https://github.com/osushinekotan/uv-template my-project
```

## Input Variables

When generating a project, Copier will prompt you for the following variables:

- **project_name**: Your project's display name (default: "My Awesome Project")
- **project_slug**: Directory name for your project (auto-generated from project_name)
- **project_source**: Python package name (auto-generated from project_slug)
- **python_version**: Python version to use (choices: 3.10, 3.11, 3.12; default: 3.11)
- **use_gpu**: Whether to include GPU support configuration (default: false)

## Update an Existing Project

To update a project with the latest template changes:

```bash
copier update
```

## Features

- 📦 Modern dependency management with [uv](https://github.com/astral-sh/uv)
- 🐍 Python 3.10+ support
- 🔧 Pre-configured development tools (ruff, mypy, pre-commit)
- 🐳 Dev container support with optional GPU
- 🧪 Testing setup with pytest
- 📓 Jupyter notebook support
- 🔄 GitHub Actions CI/CD
