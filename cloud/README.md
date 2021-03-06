# Ansible Collection - x\_delfino.cloud

[![x\_delfino.cloud](https://img.shields.io/badge/dynamic/json?color=blueviolet&label=galaxy&prefix=v&query=%24.latest_version.version&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv2%2Fcollections%2Fx_delfino%2Fcloud%2F)](https://galaxy.ansible.com/x_delfino/cloud)

collection of various cloud tools. more to come...

## Tested on:
- Debian 11.3.0 ARM64
- Kali 2022.1 ARM64

## Included Roles:

| Role | Function |
|------|----------|
| x\_delfino.cloud.azure\_cli| Installs [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/) |
| x\_delfino.cloud.ps\_az | Installs [Az PowerShell Modules](https://docs.microsoft.com/en-us/powershell/azure/) |

## Included Playbooks:

| Playbook | Function | Variables |
| -------- | -------- | --------- |
| x\_delfino.cloud.all      | Install all roles | `target` to set hosts (default: all) |
