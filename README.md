oclif-hello-world
=================

oclif example Hello World CLI

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![CircleCI](https://circleci.com/gh/oclif/hello-world/tree/main.svg?style=shield)](https://circleci.com/gh/oclif/hello-world/tree/main)
[![GitHub license](https://img.shields.io/github/license/oclif/hello-world)](https://github.com/oclif/hello-world/blob/main/LICENSE)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g unity-license-activate-remaster
$ unity-license-activate-remaster COMMAND
running command...
$ unity-license-activate-remaster (--version)
unity-license-activate-remaster/0.0.0 linux-x64 node-v18.13.0
$ unity-license-activate-remaster --help [COMMAND]
USAGE
  $ unity-license-activate-remaster COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`unity-license-activate-remaster hello PERSON`](#unity-license-activate-remaster-hello-person)
* [`unity-license-activate-remaster hello world`](#unity-license-activate-remaster-hello-world)
* [`unity-license-activate-remaster help [COMMANDS]`](#unity-license-activate-remaster-help-commands)
* [`unity-license-activate-remaster plugins`](#unity-license-activate-remaster-plugins)
* [`unity-license-activate-remaster plugins:install PLUGIN...`](#unity-license-activate-remaster-pluginsinstall-plugin)
* [`unity-license-activate-remaster plugins:inspect PLUGIN...`](#unity-license-activate-remaster-pluginsinspect-plugin)
* [`unity-license-activate-remaster plugins:install PLUGIN...`](#unity-license-activate-remaster-pluginsinstall-plugin-1)
* [`unity-license-activate-remaster plugins:link PLUGIN`](#unity-license-activate-remaster-pluginslink-plugin)
* [`unity-license-activate-remaster plugins:uninstall PLUGIN...`](#unity-license-activate-remaster-pluginsuninstall-plugin)
* [`unity-license-activate-remaster plugins reset`](#unity-license-activate-remaster-plugins-reset)
* [`unity-license-activate-remaster plugins:uninstall PLUGIN...`](#unity-license-activate-remaster-pluginsuninstall-plugin-1)
* [`unity-license-activate-remaster plugins:uninstall PLUGIN...`](#unity-license-activate-remaster-pluginsuninstall-plugin-2)
* [`unity-license-activate-remaster plugins update`](#unity-license-activate-remaster-plugins-update)

## `unity-license-activate-remaster hello PERSON`

Say hello

```
USAGE
  $ unity-license-activate-remaster hello PERSON -f <value>

ARGUMENTS
  PERSON  Person to say hello to

FLAGS
  -f, --from=<value>  (required) Who is saying hello

DESCRIPTION
  Say hello

EXAMPLES
  $ oex hello friend --from oclif
  hello friend from oclif! (./src/commands/hello/index.ts)
```

_See code: [src/commands/hello/index.ts](https://github.com/mooooooi/unity-license-activate-remaster/blob/v0.0.0/src/commands/hello/index.ts)_

## `unity-license-activate-remaster hello world`

Say hello world

```
USAGE
  $ unity-license-activate-remaster hello world

DESCRIPTION
  Say hello world

EXAMPLES
  $ unity-license-activate-remaster hello world
  hello world! (./src/commands/hello/world.ts)
```

_See code: [src/commands/hello/world.ts](https://github.com/mooooooi/unity-license-activate-remaster/blob/v0.0.0/src/commands/hello/world.ts)_

## `unity-license-activate-remaster help [COMMANDS]`

Display help for unity-license-activate-remaster.

```
USAGE
  $ unity-license-activate-remaster help [COMMANDS] [-n]

ARGUMENTS
  COMMANDS  Command to show help for.

FLAGS
  -n, --nested-commands  Include all nested commands in the output.

DESCRIPTION
  Display help for unity-license-activate-remaster.
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v5.2.20/src/commands/help.ts)_

## `unity-license-activate-remaster plugins`

List installed plugins.

```
USAGE
  $ unity-license-activate-remaster plugins [--json] [--core]

FLAGS
  --core  Show core plugins.

GLOBAL FLAGS
  --json  Format output as json.

DESCRIPTION
  List installed plugins.

EXAMPLES
  $ unity-license-activate-remaster plugins
```

_See code: [@oclif/plugin-plugins](https://github.com/oclif/plugin-plugins/blob/v4.1.8/src/commands/plugins/index.ts)_

## `unity-license-activate-remaster plugins:install PLUGIN...`

Installs a plugin into the CLI.

```
USAGE
  $ unity-license-activate-remaster plugins add plugins:install PLUGIN...

ARGUMENTS
  PLUGIN  Plugin to install.

FLAGS
  -f, --force    Run yarn install with force flag.
  -h, --help     Show CLI help.
  -s, --silent   Silences yarn output.
  -v, --verbose  Show verbose yarn output.

GLOBAL FLAGS
  --json  Format output as json.

DESCRIPTION
  Installs a plugin into the CLI.
  Can be installed from npm or a git url.

  Installation of a user-installed plugin will override a core plugin.

  e.g. If you have a core plugin that has a 'hello' command, installing a user-installed plugin with a 'hello' command
  will override the core plugin implementation. This is useful if a user needs to update core plugin functionality in
  the CLI without the need to patch and update the whole CLI.


ALIASES
  $ unity-license-activate-remaster plugins add

EXAMPLES
  $ unity-license-activate-remaster plugins add myplugin 

  $ unity-license-activate-remaster plugins add https://github.com/someuser/someplugin

  $ unity-license-activate-remaster plugins add someuser/someplugin
```

## `unity-license-activate-remaster plugins:inspect PLUGIN...`

Displays installation properties of a plugin.

```
USAGE
  $ unity-license-activate-remaster plugins inspect PLUGIN...

ARGUMENTS
  PLUGIN  [default: .] Plugin to inspect.

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

GLOBAL FLAGS
  --json  Format output as json.

DESCRIPTION
  Displays installation properties of a plugin.

EXAMPLES
  $ unity-license-activate-remaster plugins inspect myplugin
```

_See code: [@oclif/plugin-plugins](https://github.com/oclif/plugin-plugins/blob/v4.1.8/src/commands/plugins/inspect.ts)_

## `unity-license-activate-remaster plugins:install PLUGIN...`

Installs a plugin into the CLI.

```
USAGE
  $ unity-license-activate-remaster plugins install PLUGIN...

ARGUMENTS
  PLUGIN  Plugin to install.

FLAGS
  -f, --force    Run yarn install with force flag.
  -h, --help     Show CLI help.
  -s, --silent   Silences yarn output.
  -v, --verbose  Show verbose yarn output.

GLOBAL FLAGS
  --json  Format output as json.

DESCRIPTION
  Installs a plugin into the CLI.
  Can be installed from npm or a git url.

  Installation of a user-installed plugin will override a core plugin.

  e.g. If you have a core plugin that has a 'hello' command, installing a user-installed plugin with a 'hello' command
  will override the core plugin implementation. This is useful if a user needs to update core plugin functionality in
  the CLI without the need to patch and update the whole CLI.


ALIASES
  $ unity-license-activate-remaster plugins add

EXAMPLES
  $ unity-license-activate-remaster plugins install myplugin 

  $ unity-license-activate-remaster plugins install https://github.com/someuser/someplugin

  $ unity-license-activate-remaster plugins install someuser/someplugin
```

_See code: [@oclif/plugin-plugins](https://github.com/oclif/plugin-plugins/blob/v4.1.8/src/commands/plugins/install.ts)_

## `unity-license-activate-remaster plugins:link PLUGIN`

Links a plugin into the CLI for development.

```
USAGE
  $ unity-license-activate-remaster plugins link PLUGIN

ARGUMENTS
  PATH  [default: .] path to plugin

FLAGS
  -h, --help          Show CLI help.
  -v, --verbose
      --[no-]install  Install dependencies after linking the plugin.

DESCRIPTION
  Links a plugin into the CLI for development.
  Installation of a linked plugin will override a user-installed or core plugin.

  e.g. If you have a user-installed or core plugin that has a 'hello' command, installing a linked plugin with a 'hello'
  command will override the user-installed or core plugin implementation. This is useful for development work.


EXAMPLES
  $ unity-license-activate-remaster plugins link myplugin
```

_See code: [@oclif/plugin-plugins](https://github.com/oclif/plugin-plugins/blob/v4.1.8/src/commands/plugins/link.ts)_

## `unity-license-activate-remaster plugins:uninstall PLUGIN...`

Removes a plugin from the CLI.

```
USAGE
  $ unity-license-activate-remaster plugins remove plugins:uninstall PLUGIN...

ARGUMENTS
  PLUGIN  plugin to uninstall

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Removes a plugin from the CLI.

ALIASES
  $ unity-license-activate-remaster plugins unlink
  $ unity-license-activate-remaster plugins remove

EXAMPLES
  $ unity-license-activate-remaster plugins remove myplugin
```

## `unity-license-activate-remaster plugins reset`

Remove all user-installed and linked plugins.

```
USAGE
  $ unity-license-activate-remaster plugins reset
```

_See code: [@oclif/plugin-plugins](https://github.com/oclif/plugin-plugins/blob/v4.1.8/src/commands/plugins/reset.ts)_

## `unity-license-activate-remaster plugins:uninstall PLUGIN...`

Removes a plugin from the CLI.

```
USAGE
  $ unity-license-activate-remaster plugins uninstall PLUGIN...

ARGUMENTS
  PLUGIN  plugin to uninstall

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Removes a plugin from the CLI.

ALIASES
  $ unity-license-activate-remaster plugins unlink
  $ unity-license-activate-remaster plugins remove

EXAMPLES
  $ unity-license-activate-remaster plugins uninstall myplugin
```

_See code: [@oclif/plugin-plugins](https://github.com/oclif/plugin-plugins/blob/v4.1.8/src/commands/plugins/uninstall.ts)_

## `unity-license-activate-remaster plugins:uninstall PLUGIN...`

Removes a plugin from the CLI.

```
USAGE
  $ unity-license-activate-remaster plugins unlink plugins:uninstall PLUGIN...

ARGUMENTS
  PLUGIN  plugin to uninstall

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Removes a plugin from the CLI.

ALIASES
  $ unity-license-activate-remaster plugins unlink
  $ unity-license-activate-remaster plugins remove

EXAMPLES
  $ unity-license-activate-remaster plugins unlink myplugin
```

## `unity-license-activate-remaster plugins update`

Update installed plugins.

```
USAGE
  $ unity-license-activate-remaster plugins update [-h] [-v]

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Update installed plugins.
```

_See code: [@oclif/plugin-plugins](https://github.com/oclif/plugin-plugins/blob/v4.1.8/src/commands/plugins/update.ts)_
<!-- commandsstop -->
