[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/haase-fabian/ddev-neos/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/haase-fabian/ddev-neos/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/haase-fabian/ddev-neos)](https://github.com/haase-fabian/ddev-neos/commits)
[![release](https://img.shields.io/github/v/release/haase-fabian/ddev-neos)](https://github.com/haase-fabian/ddev-neos/releases/latest)

# DDEV Neos CMS Addon

## Overview

This add-on configures [Neos](https://neos.io) for your [DDEV](https://ddev.com/) project.

1. It provides a shortcut for the `flow` command via the cli
2. Adds all required configuration to directly start a running Neos installation

## Installation

```bash
ddev add-on get haase-fabian/ddev-neos
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Usage

| Command                       | Description                  |
|-------------------------------|------------------------------|
| `ddev flow list`              | View available flow commands |

