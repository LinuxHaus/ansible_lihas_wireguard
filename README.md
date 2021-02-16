# lihas-wireguard

Install wireguard on Debian, currently Debian Buster, an create public/private key pairs if they don't already exist

## Requirements

To run solo:
```
ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, wireguard.yml
```

## Example Playbook

```
---
- hosts: '*'
  roles:
    - lihas_wireguard
...
```
