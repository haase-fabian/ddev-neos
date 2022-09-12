[![tests](https://github.com/haase-fabian/ddev-neos/actions/workflows/tests.yml/badge.svg)](https://github.com/haase-fabian/ddev-neos/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2022.svg)

## What is ddev-neos?

This repository allows you to quickly install a Neos CMS environment as a Ddev project using just ddev get haase-fabian/ddev-redis.

## Installation

* `ddev get haase-fabian/ddev-neos`
* `ddev restart`

## Explanation

This recipe for ddev installs a .ddev/docker-compose.neos.yaml adding neos specific environment variables to the web container.
And it adds the `ddev flow` command to run ./flow commands.


