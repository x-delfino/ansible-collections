# Ansible Collection - x\_delfino.security

[![x\_delfino.security](https://img.shields.io/badge/dynamic/json?color=blueviolet&label=galaxy&prefix=v&query=%24.latest_version.version&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv2%2Fcollections%2Fx_delfino%2Fsecurity%2F)](https://galaxy.ansible.com/x_delfino/security)

collection of various security tools. more to come...

## Tested on:
- Debian 11.3.0 ARM64
- Kali 2022.1 ARM64

## Included Roles:

| Role | Function |
|------|----------|
| x\_delfino.security.gobuster| Installs [Gobuster](https://github.com/OJ/gobuster) |
| x\_delfino.security.impacket| Install [Impacket](https://github.com/SecureAuthCorp/impacket) |
| x\_delfino.security.pyftpdlib| Installs [pyftpdlib](https://pypi.org/project/pyftpdlib/) |
| x\_delfino.security.rlwrap| Installs [rlwrap](https://github.com/hanslub42/rlwrap) |
| x\_delfino.security.scoutsuite| Installs [ScoutSuite](https://github.com/nccgroup/ScoutSuite) |
| x\_delfino.security.trufflehog| Installs [TruffleHog](https://github.com/trufflesecurity/trufflehog) |
| x\_delfino.security.updog| Install [Updog](https://github.com/sc0tfree/updog) |


## Included Playbooks:

| Playbook | Function | Variables |
| -------- | -------- | --------- |
| x\_delfino.security.all      | Install all roles | `target` to set hosts (default: all) |
