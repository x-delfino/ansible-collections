[windows-10+]: https://img.shields.io/badge/Windows-10%2B-00A4EF?logo=windows&logoColor=white
[macos-12+]: https://img.shields.io/badge/macOS-12%2B-black?logo=apple&logoColor=white
[debian-11]: https://img.shields.io/badge/Debian-11.3-DD1155?logo=debian&logoColor=white
[kali-2022]: https://img.shields.io/badge/Kali-2022.1-367bf0?logo=kali-linux&logoColor=white
[ubuntu-20.04]: https://img.shields.io/badge/Ubuntu-20.04-E95420?logo=ubuntu&logoColor=white


# Ansible Collection - x\_delfino.utils

[![x\_delfino.utils](https://img.shields.io/badge/dynamic/json?color=blueviolet&logo=ansible&label=galaxy&prefix=v&query=%24.latest_version.version&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv2%2Fcollections%2Fx_delfino%2Futils%2F)](https://galaxy.ansible.com/x_delfino/utils)

collection of various utilities. more to come...

## Tested on:
- Debian 11.3.0 ARM64
- Kali 2022.1 ARM64

## Included Roles:

| Role | Function | Tested On |
|------|----------|-----------|
| x\_delfino.utils.alacritty| Installs [Alacritty](https://github.com/alacritty/alacritty) | [![alacritty](https://img.shields.io/chocolatey/v/alacritty?color=80B5E3&label=choco&logo=chocolatey&logoColor=white)](https://community.chocolatey.org/packages/alacritty) [![alacritty](https://img.shields.io/crates/v/alacritty?color=2e572a&logo=rust)](https://crates.io/crates/alacritty) |
| x\_delfino.utils.curl| Installs [curl](https://curl.se/) | [![curl](https://img.shields.io/debian/v/curl/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/curl) [![curl](https://img.shields.io/endpoint?url=https://https://kali-pkg-ver.azurewebsites.net/api/get-pkg-ver?pkg=curl)](https://pkg.kali.org/pkg/curl) |
| x\_delfino.utils.git| Installs [git](https://git-scm.com/) | [![git](https://img.shields.io/debian/v/git/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/git) [![git](https://img.shields.io/endpoint?url=https://https://kali-pkg-ver.azurewebsites.net/api/get-pkg-ver?pkg=git)](https://pkg.kali.org/pkg/git) |
| x\_delfino.utils.golang| Installs [Go](https://go.dev/) | ![debian-11] ![kali-2022] |
| x\_delfino.utils.neovim| Installs [Neovim](https://neovim.io/) | [![neovim](https://img.shields.io/debian/v/neovim/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/neovim) [![neovim](https://img.shields.io/endpoint?url=https://https://kali-pkg-ver.azurewebsites.net/api/get-pkg-ver?pkg=neovim)](https://pkg.kali.org/pkg/neovim) [![neovim](https://img.shields.io/chocolatey/v/neovim?color=80B5E3&label=choco&logo=chocolatey&logoColor=white)](https://community.chocolatey.org/packages/neovim) |
| x\_delfino.utils.nnn| Installs [nnn(_n³_)](https://github.com/jarun/nnn) | ![debian-11] ![kali-2022] |
| x\_delfino.utils.ohmyzsh| Installs [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) | ![debian-11] ![kali-2022] |
| x\_delfino.utils.openssh\_server| Installs [OpenSSH Server](https://www.openssh.com/) | ![windows-10+] |
| x\_delfino.utils.powershell| Installs [PowerShell](https://github.com/PowerShell/PowerShell) | ![debian-11] ![kali-2022] |
| x\_delfino.utils.ps\_nuget| Installs [PowerShell NuGet Provider](https://docs.microsoft.com/en-us/nuget/reference/powershell-reference) | ![windows-10+] |
| x\_delfino.utils.ps\_script\_analyzer| Installs [PSScriptAnalyzer](https://github.com/PowerShell/PSScriptAnalyzer) | [![PSScriptAnalyzer](https://img.shields.io/powershellgallery/v/PSScriptAnalyzer?color=012456&label=gallery&logo=powershell&logoColor=white)](https://www.powershellgallery.com/packages/PSScriptAnalyzer) |
| x\_delfino.utils.py3\_virtualenv| Installs [Python 3 venv](https://docs.python.org/3/library/venv.html) | [![virtualenv](https://img.shields.io/pypi/v/virtualenv?logo=pypi&logoColor=white)](https://pypi.org/project/virtualenv/) |
| x\_delfino.utils.python3| Installs [Python 3](https://www.python.org/) | [![python3](https://img.shields.io/chocolatey/v/python?color=80B5E3&label=choco&logo=chocolatey&logoColor=white)](https://community.chocolatey.org/packages/python) |
| x\_delfino.utils.rust| Installs [Rust](https://www.rust-lang.org/) | ![debian-11] ![kali-2022] [![rust](https://img.shields.io/chocolatey/v/rust?color=80B5E3&label=choco&logo=chocolatey&logoColor=white)](https://community.chocolatey.org/packages/rust) |
| x\_delfino.utils.rust\_analyzer| Installs [rust-analyzer](https://github.com/rust-lang/rust-analyzer) | ![debian-11] ![kali-2022] [![rust](https://img.shields.io/chocolatey/v/rust-analyzer?color=80B5E3&label=choco&logo=chocolatey&logoColor=white)](https://community.chocolatey.org/packages/rust-analyzer) |
| x\_delfino.utils.tmux| Installs [tmux](https://github.com/tmux/tmux/wiki) | [![tmux](https://img.shields.io/debian/v/tmux/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/tmux) [![tmux](https://img.shields.io/endpoint?url=https://https://kali-pkg-ver.azurewebsites.net/api/get-pkg-ver?pkg=tmux)](https://pkg.kali.org/pkg/tmux) |
| x\_delfino.utils.tmuxp| Installs [tmuxp](https://github.com/tmux-python/tmuxp) | [![tmuxp](https://img.shields.io/debian/v/tmuxp/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/tmuxp) |
| x\_delfino.utils.tpm| Installs [tpm](https://github.com/tmux-plugins/tpm) | ![debian-11] ![kali-2022] |
| x\_delfino.utils.unzip| Installs [unzip](https://linux.die.net/man/1/unzip) | [![unzip](https://img.shields.io/debian/v/unzip/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/unzip) [![unzip](https://img.shields.io/endpoint?url=https://https://kali-pkg-ver.azurewebsites.net/api/get-pkg-ver?pkg=unzip)](https://pkg.kali.org/pkg/unzip) |
| x\_delfino.utils.vim\_plug| Installs [vim-plug](https://github.com/junegunn/vim-plug) | ![debian-11] ![kali-2022] |
| x\_delfino.utils.wget| Installs [wget](https://www.gnu.org/software/wget/) | [![wget](https://img.shields.io/debian/v/wget/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/wget) [![wget](https://img.shields.io/endpoint?url=https://https://kali-pkg-ver.azurewebsites.net/api/get-pkg-ver?pkg=wget)](https://pkg.kali.org/pkg/wget) |
| x\_delfino.utils.zip| Installs [zip](https://linux.die.net/man/1/zip) | [![zip](https://img.shields.io/debian/v/zip/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/zip) [![zip](https://img.shields.io/endpoint?url=https://https://kali-pkg-ver.azurewebsites.net/api/get-pkg-ver?pkg=zip)](https://pkg.kali.org/pkg/zip) |
| x\_delfino.utils.zsh| Installs [zsh](https://www.zsh.org/) | [![zsh](https://img.shields.io/debian/v/zsh/stable?color=DD1155&logo=debian)](https://packages.debian.org/stable/zsh) [![zsh](https://img.shields.io/endpoint?url=https://https://kali-pkg-ver.azurewebsites.net/api/get-pkg-ver?pkg=zsh)](https://pkg.kali.org/pkg/zsh) |

## Included Playbooks:

| Playbook | Function | Variables |
| -------- | -------- | --------- |
| x\_delfino.security.all      | Install all roles | `target` to set hosts (default: all) |
