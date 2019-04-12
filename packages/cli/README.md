@cashew/cli
===========

&gt; TODO: description

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@cashew/cli.svg)](https://npmjs.org/package/@cashew/cli)
[![Downloads/week](https://img.shields.io/npm/dw/@cashew/cli.svg)](https://npmjs.org/package/@cashew/cli)
[![License](https://img.shields.io/npm/l/@cashew/cli.svg)](https://github.com/[object Object]/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @cashew/cli
$ @cashew/cli COMMAND
running command...
$ @cashew/cli (-v|--version|version)
@cashew/cli/0.0.0 darwin-x64 node-v10.15.0
$ @cashew/cli --help [COMMAND]
USAGE
  $ @cashew/cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`@cashew/cli hello [FILE]`](#cashewcli-hello-file)
* [`@cashew/cli help [COMMAND]`](#cashewcli-help-command)

## `@cashew/cli hello [FILE]`

describe the command here

```
USAGE
  $ @cashew/cli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/kmannislands/typescript-yarn-workspace-example/blob/v0.0.0/src/commands/hello.ts)_

## `@cashew/cli help [COMMAND]`

display help for @cashew/cli

```
USAGE
  $ @cashew/cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.6/src/commands/help.ts)_
<!-- commandsstop -->
