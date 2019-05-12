@hiroga/cognito-userpool-cli
============================

cli tool for Cognito UserPool (ex. signin, forgotPasswordSubmit, etc...)

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@hiroga/cognito-userpool-cli.svg)](https://npmjs.org/package/@hiroga/cognito-userpool-cli)
[![Downloads/week](https://img.shields.io/npm/dw/@hiroga/cognito-userpool-cli.svg)](https://npmjs.org/package/@hiroga/cognito-userpool-cli)
[![License](https://img.shields.io/npm/l/@hiroga/cognito-userpool-cli.svg)](https://github.com/hiroga-cc/cognito-userpool-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @hiroga/cognito-userpool-cli
$ cognito-userpool-cli COMMAND
running command...
$ cognito-userpool-cli (-v|--version|version)
@hiroga/cognito-userpool-cli/0.1.3 darwin-x64 node-v10.5.0
$ cognito-userpool-cli --help [COMMAND]
USAGE
  $ cognito-userpool-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`cognito-userpool-cli configure`](#cognito-userpool-cli-configure)
* [`cognito-userpool-cli forget-password [FILE]`](#cognito-userpool-cli-forget-password-file)
* [`cognito-userpool-cli hello [FILE]`](#cognito-userpool-cli-hello-file)
* [`cognito-userpool-cli help [COMMAND]`](#cognito-userpool-cli-help-command)
* [`cognito-userpool-cli signin`](#cognito-userpool-cli-signin)

## `cognito-userpool-cli configure`

describe the command here

```
USAGE
  $ cognito-userpool-cli configure

OPTIONS
  -c, --client=client      userpool client id to access
  -h, --help               show CLI help
  -r, --region=region      region to access
  -u, --userpool=userpool  userpool id to access
```

_See code: [src/commands/configure.ts](https://github.com/hiroga-cc/cognito-userpool-cli/blob/v0.1.3/src/commands/configure.ts)_

## `cognito-userpool-cli forget-password [FILE]`

describe the command here

```
USAGE
  $ cognito-userpool-cli forget-password [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/forget-password.ts](https://github.com/hiroga-cc/cognito-userpool-cli/blob/v0.1.3/src/commands/forget-password.ts)_

## `cognito-userpool-cli hello [FILE]`

describe the command here

```
USAGE
  $ cognito-userpool-cli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ cognito-userpool-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/hiroga-cc/cognito-userpool-cli/blob/v0.1.3/src/commands/hello.ts)_

## `cognito-userpool-cli help [COMMAND]`

display help for cognito-userpool-cli

```
USAGE
  $ cognito-userpool-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.6/src/commands/help.ts)_

## `cognito-userpool-cli signin`

describe the command here

```
USAGE
  $ cognito-userpool-cli signin

OPTIONS
  -h, --help                 show CLI help
  -p, --password=password    password
  -u, --user=user            user
  --newPassword=newPassword  new-password
```

_See code: [src/commands/signin.ts](https://github.com/hiroga-cc/cognito-userpool-cli/blob/v0.1.3/src/commands/signin.ts)_
<!-- commandsstop -->
