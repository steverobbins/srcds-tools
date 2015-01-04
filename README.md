srcds-tools
===

Some utilities to make your life easier managing a Source Dedicated Server.
Currently supports only Counter-Strike Source.

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

## Support

Currently supports only Counter-Strike Souce.

## Author

* [jimbru](https://github.com/jimbru)
