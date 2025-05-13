# Role Name: proton_suite

This Ansible Role that will install the Proton (proton.me) .deb packages for the applications you select.

## Requirements

- Debian-based system.

## Role Variables

- N/A

## Dependencies

- N/A

## Example Playbook

```yaml
---
- name: "Install Proton Suite Playbook Example"
  hosts:
    - all
  become: true


  tasks:

    - name: "Install proton_suite on my system please!"
      ansible.builtin.include_role:
        name: "aaronvonawesome.proton_suite
```

## License

BSD

## Author Information

| Name | Website |
| --  | -- |
| Aaron von Awesome | https://aaronvonawesome.com |
