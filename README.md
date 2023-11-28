# systemroles-demo-cli

Change hostnames and `ansible_user` in `inventory.yml`.

```
ansible-navigator run config-ntp.yml -i inventory.yml -m stdout
```

or

```
ansible-navigator run config-ntp.yml -i inventory.yml
```
