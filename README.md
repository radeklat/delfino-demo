<h1 align="center" style="border-bottom: none;"> 🔌&nbsp;&nbsp;Delfino Demo Plugin&nbsp;&nbsp; 🔌</h1>
<h3 align="center">A minimal plugin example for <a href="https://github.com/radeklat/delfino">Delfino</a>.</h3>

<p align="center">
    <a href="https://app.circleci.com/pipelines/github/radeklat/delfino-demo?branch=main">
        <img alt="CircleCI" src="https://img.shields.io/circleci/build/github/radeklat/delfino-demo">
    </a>
    <a href="https://app.codecov.io/gh/radeklat/delfino-demo/">
        <img alt="Codecov" src="https://img.shields.io/codecov/c/github/radeklat/delfino-demo">
    </a>
    <a href="https://github.com/radeklat/delfino-demo/tags">
        <img alt="GitHub tag (latest SemVer)" src="https://img.shields.io/github/tag/radeklat/delfino-demo">
    </a>
    <img alt="Maintenance" src="https://img.shields.io/maintenance/yes/2022">
    <a href="https://github.com/radeklat/delfino-demo/commits/main">
        <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/radeklat/delfino-demo">
    </a>
    <a href="https://www.python.org/doc/versions/">
        <img alt="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/delfino-demo">
    </a>
    <a href="https://pypistats.org/packages/delfino-demo">
        <img alt="Downloads" src="https://img.shields.io/pypi/dm/delfino-demo">
    </a>
</p>

# Installation

- pip: `pip install delfino-demo`
- Poetry: `poetry add -D delfino-demo`
- Pipenv: `pipenv install -d delfino-demo`

## Configuration

Delfino doesn't load any plugins by default. To enable this plugin, add the following config into `pyproject.toml`:

```toml
[tool.delfino.plugins.delfino-demo]

```

# Usage

Run `delfino demo`.
