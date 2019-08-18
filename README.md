# Using ansible to configure my VPS

tested on ansible version 2.83

- base
- ssserver
- kcptun-server


# How to use
You can reference *.example* to configure your configuration files.

For example:
```
cp hosts.example hosts
cp kcptun-server-config.json.example kcptun-server-config.json
ansible-playbook -i hosts kcptun-server.yml
```