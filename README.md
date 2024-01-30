# tidydev

[![Lint commit message](https://github.com/yannickkirschen/tidydev/actions/workflows/commit-lint.yml/badge.svg)](https://github.com/yannickkirschen/tidydev/actions/workflows/commit-lint.yml)
[![pytest](https://github.com/yannickkirschen/tidydev/actions/workflows/push.yml/badge.svg)](https://github.com/yannickkirschen/tidydev/actions/workflows/push.yml)
[![release](https://github.com/yannickkirschen/tidydev/actions/workflows/release.yml/badge.svg)](https://github.com/yannickkirschen/tidydev/actions/workflows/release.yml)
[![GitHub release](https://img.shields.io/github/release/yannickkirschen/tidydev.svg)](https://github.com/yannickkirschen/tidydev/releases/)

tidydev is a Python package that provides a set of tools to make your development life easier. It allows analyzing
a directory of git and non-git directories.

## Installation

```bash
pip install tidydev
```

## Usage

```text
Usage: tidydev <commands>

Available commands:
    help              - show this help
    version           - show version
    analyze <path>    - analyze the given path for git repositories and build files
    analyze-git <path>- analyze the given path for git repositories and build files and show git status
```
