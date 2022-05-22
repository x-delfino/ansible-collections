# Ansible Collection - x_delfino.cloud

collection of various cloud tools. more to come...

## Included Roles:

| Role | Function |
|------|----------|
| x_delfino.cloud.azure_cli| Installs [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/) |
| x_delfino.cloud.ps_az | Installs [Az PowerShell Modules](https://docs.microsoft.com/en-us/powershell/azure/) |

## Includes Playbooks:

| Playbook | Function | Variables |
| -------- | -------- | --------- |
| x_delfino.cloud.all      | Install all roles | `target` to set hosts (default: all) |
