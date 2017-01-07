# Ansible Role: Simple IP Forwarding

Installs basic IP forwarding.

## Requirements

This role only is needed/runs on RHEL and its derivatives.

## Role Variables

See `defaults/main.yml`.

## Dependencies

- nexcess.server

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-ip-forward.git
      name: nexcess.ip-forward

## Example Playbook

    - hosts: gateway
      roles:
        - nexcess.ip-forward

## License

MIT / BSD
