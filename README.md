# Playbook to manage Linux users and groups

- Requires Ansible 2.9 or newer
- Expects Fedora 37

The inventory file 'hosts' defines the nodes in which the stacks should be configured.

    [all]
    fedora ansible_host=192.168.1.60

The stack can be deployed using the following command:

        ansible-playbook -i hosts site.yml
