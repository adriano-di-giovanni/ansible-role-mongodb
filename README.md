# Ansible Role: MongoDB

Ansible role for MongoDB Community Edition:

* basic, opinionated install
  * version 3.2
  * mongodb-org metapackage

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  become: true
  roles:
    - adriano-di-giovanni.mongodb
```

The `example/` folder contain project files to provision an Ubuntu Trusty VM using Vagrant and VirtualBox.

## License

MIT

## Resources

* https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/

## Author Information

Adriano Di Giovanni
