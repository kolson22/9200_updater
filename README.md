# WIP: Catalyst 9200 Update Playbook

1.) Update [hosts.yml](hosts.yml) to include switches and IP addresses of the devices you want to upgrade

2.) Update [upgrade.yml](upgrade.yml) to include version and tftp IP hosting the new image

3.)
``` bash
ansible-playbook upgrade.yml
```
4.) Wait for it to finish
