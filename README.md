fundingbox-wiki-cli
========

This utility requires [`yarn`](https://yarnpkg.com/) and [`git`](https://git-scm.com/) to be installed.

Configure the utility with a config json. See a example [`here`](./config.example.json).

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g fundingbox-wiki-cli
$ fundingbox-wiki-cli COMMAND
running command...
$ fundingbox-wiki-cli (-v|--version|version)
fundingbox-wiki-cli/1.6.0 linux-x64 node-v14.16.1
$ fundingbox-wiki-cli --help [COMMAND]
USAGE
  $ fundingbox-wiki-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`fundingbox-wiki-cli checkout`](#fundingbox-wiki-cli-checkout)
* [`fundingbox-wiki-cli clean`](#fundingbox-wiki-cli-clean)
* [`fundingbox-wiki-cli help [COMMAND]`](#fundingbox-wiki-cli-help-command)
* [`fundingbox-wiki-cli setup`](#fundingbox-wiki-cli-setup)
* [`fundingbox-wiki-cli start`](#fundingbox-wiki-cli-start)

## `fundingbox-wiki-cli checkout`

checkout content repositories

```
USAGE
  $ fundingbox-wiki-cli checkout

OPTIONS
  -h, --help            show CLI help
  -o, --[no-]overwrite  Disable/Enable overwriting of static content

EXAMPLE
  $ fundingbox-wiki-cli checkout
```

## `fundingbox-wiki-cli clean`

completely removes local wiki

```
USAGE
  $ fundingbox-wiki-cli clean

OPTIONS
  -h, --help  show CLI help
```

## `fundingbox-wiki-cli help [COMMAND]`

display help for fundingbox-wiki-cli

```
USAGE
  $ fundingbox-wiki-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_

## `fundingbox-wiki-cli setup`

setup local wiki

```
USAGE
  $ fundingbox-wiki-cli setup

OPTIONS
  -h, --help     show CLI help
  -r, --ref=ref  wiki revison to checkout

EXAMPLE
  $ fundingbox-wiki-cli setup --ref main
```

## `fundingbox-wiki-cli start`

start local wiki

```
USAGE
  $ fundingbox-wiki-cli start

OPTIONS
  -h, --help  show CLI help
  --dry-run   Test build the wiki with the current edited content
```
<!-- commandsstop -->
