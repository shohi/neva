# neva
a neovim version manager


## Install

```bash
# download script
mkdir -p $HOME/.neva/bin
curl -L -o $HOME/.neva/bin/neva https://github.com/shohi/neva/raw/main/neva

# add to $PATH
export PATH="$HOME/.neva/bin":$PATH
```

Note: require `lua 5.3+` installed

## Usage

```bash
$> neva --help

neovim version manager

Usage:
  neva [command]

Availalbe Commands:
  -h --help    Print help info
  install      Install a specific version
  uninstall    Uninstall a specific version
  use          Switch to specific version
  list/ls      List all installed versions
  list-remote  List latest version
  clean        Remove downloaded source file

```
