# Ansible Collection - x\_delfino.utils

[![x\_delfino.utils](https://img.shields.io/badge/dynamic/json?color=blueviolet&label=galaxy&prefix=v&query=%24.latest_version.version&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv2%2Fcollections%2Fx_delfino%2Futils%2F)](https://galaxy.ansible.com/x_delfino/utils)

collection of various utilities. more to come...

## Tested on:
- Debian 11.3.0 ARM64
- Kali 2022.1 ARM64

## Included Roles:

| Role | Function |
|------|----------|
| x\_delfino.utils.alacritty| Installs [Alacritty](https://github.com/alacritty/alacritty) |
| x\_delfino.utils.curl| Installs [curl](https://curl.se/) |
| x\_delfino.utils.git| Installs [git](https://git-scm.com/) |
| x\_delfino.utils.golang| Installs [Go](https://go.dev/) |
| x\_delfino.utils.neovim| Installs [Neovim](https://neovim.io/) |
| x\_delfino.utils.nnn| Installs [nnn(_n³_)](https://github.com/jarun/nnn) |
| x\_delfino.utils.ohmyzsh| Installs [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) |
| x\_delfino.utils.powershell| Installs [PowerShell](https://github.com/PowerShell/PowerShell) |
| x\_delfino.utils.ps\_script\_analyzer| Installs [PSScriptAnalyzer](https://github.com/PowerShell/PSScriptAnalyzer) |
| x\_delfino.utils.python3\_9\_venv| Installs [Python 3.9 venv](https://docs.python.org/3/library/venv.html) |
| x\_delfino.utils.rust| Installs [Rust](https://www.rust-lang.org/) |
| x\_delfino.utils.rust\_analyzer| Installs [rust-analyzer](https://github.com/rust-lang/rust-analyzer) |
| x\_delfino.utils.tmux| Installs [tmux](https://github.com/tmux/tmux/wiki) |
| x\_delfino.utils.tmuxp| Installs [tmuxp](https://github.com/tmux-python/tmuxp) |
| x\_delfino.utils.tpm| Installs [tpm](https://github.com/tmux-plugins/tpm) |
| x\_delfino.utils.unzip| Installs [unzip](https://linux.die.net/man/1/unzip) |
| x\_delfino.utils.vim\_plug| Installs [vim-plug](https://github.com/junegunn/vim-plug) |
| x\_delfino.utils.wget| Installs [wget](https://www.gnu.org/software/wget/) |
| x\_delfino.utils.zip| Installs [zip](https://linux.die.net/man/1/zip) |
| x\_delfino.utils.zsh| Installs [zsh](https://www.zsh.org/) |

## Included Playbooks:

| Playbook | Function | Variables |
| -------- | -------- | --------- |
| x\_delfino.security.all      | Install all roles | `target` to set hosts (default: all) |
