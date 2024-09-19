# Ansible-Role: acr-ansible-manage-authorized-keys

AIT-CyberRange: Manages authorized keys. 


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
user_list: []
keys_base_path: ""
fixed_authorized_key: ""
```

## Example Playbook

```yaml
- hosts: all
  roles:
    - acr-ansible-manage-authorized-keys
      vars:
        user_list: "{{ users}}"
```

## License

GPL-3.0

## Author

- Lenhard Reuter