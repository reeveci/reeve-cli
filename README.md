# Reeve CI / CD - Command Line Tools

## Installing

```sh
go install github.com/reeveci/reeve-cli/reeve@v1.0.0

reeve --help
```

## Configuration

Connection settings can be stored in a config file, which is located in the users home directory by default and can be otherwise specified with the `REEVE_CLI_CONFIG` environment variable.

Configuration options can be set using the `config` command.

```sh
reeve config url https://reeve-server:9080
```

## Usage

The commands available depend on the plugins that are configured for your server.
The `--usage` switch can be used to get a list of available commands.

```sh
reeve --usage
```
