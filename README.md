# Wireguard VPN

Ansible playbook for wireguard installation on Ubuntu 20.04+. 


- [x] Auto NAT traffic through wireguard
- [x] Generate Wireguard server/client* configuration automatically

*wireguard client.conf will be generated on the local machine on the folder that ran the playbook.

```
# ansible-playbook [core 2.11.2]
ansible-playbook -i hosts setup-wireguard.yaml
```
