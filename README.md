# Reeve CI / CD - Command Line Tools

## Installing

```sh
go install github.com/reeveci/reeve-cli/reeve@latest

reeve --help
```

## Configuration

Connection settings can be stored in a config file, which is located in the users home directory by default and can be otherwise specified with the `REEVE_CLI_CONFIG` environment variable.

Configuration options can be set using the `config` command.

```sh
reeve config set url https://reeve-server:9080
```
