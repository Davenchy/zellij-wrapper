# zellij-wrapper
A bash script to ease working with zellij using fzf

## Usage

Set execute permissions to the script

```bash
chmod +x zellij_run
```

This script runs in interactive/non-interactive mode

```bash
./zellij_run [action]
Welcome to zellij runner!


1) attach
2) create
3) list
4) delete
Please enter your choice: 
```

## Dependencies

This script requires `fzf` `zellij` packages to be installed

## Commands

- `create`: to create and attach to a new named session
- `attach`: use fzf to select and attach to a session
- `list`: list all available sessions
- `delete`: select multiable sessions to delete
