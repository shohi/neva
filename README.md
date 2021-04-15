# neva

A Neovim version manager

## Supported systems

- `MacOS`
- `Linux`

> **NOTE:** if your OS isn't on the list of supported systems,
> you can support it and do a PR.

## Requirements

- `lua 5.3+`
- `curl`
- `tar`
- [`gojq`](https://github.com/itchyny/gojq)

## Install

```bash
# download script
mkdir -p $HOME/.neva/bin
curl -L -o $HOME/.neva/bin/neva https://github.com/shohi/neva/raw/main/neva

# add to $PATH, adding also $HOME/.local/bin because there is where the used
# neovim version will be symlinked.
export PATH=$HOME/.neva/bin:$HOME/.local/bin:$PATH
```

## Usage

```bash
❯ neva help
neva - Neovim version manager

Usage:
  neva [command]

Available Commands:
  help, --help, -h       Print help info
  install                Install a specific version
  uninstall              Uninstall a specific version
  use                    Switch to specific version
  list, ls               List all installed versions
  list-remote            List latest version
  clean                  Remove downloaded source file(s if no version was specified)
```
