srcds-tools
===

Some utilities to make your life easier managing a Source Dedicated Server.

## Commands

Run commands via `./srctool <command>`

### `config [-s] <file> <dir>`

Copies the specified config file to the specified srcds instance.

### `help`

Prints help.

### `install <dir>`

Installs a srcds instance to the specificed directory.

### `map <archive> <dir>`

Installs the specified map archive to the specified srcds instance.

### `module <smx> <dir>`

Installs the specified module to the specified srcds instance.

### `rcon <addr> <pwd> <cmd>`

Send rcon command to the server at the specified address.

Leave `<cmd>` blank to run tests.

## Supported platforms

* Counter-Strike Source

Most commands should work with TF2 but YMMV.


## Authors

* [jimbru](https://github.com/jimbru)
* [steverobbins](https://github.com/steverobbins)

Based on works from [stellarhopper](https://github.com/stellarhopper/logstreamer)

