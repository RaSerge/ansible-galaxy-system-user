# ansible-galaxy-system-users
galaxified Ansible role intended for users/groups/ssh keys management

## Configuration:

Please see example in **_example** directory.

- Put user ssh public keys in playbook files dirextory
- Define global and per host/group users group mapping in corresponding host_vars/group_vars

## Dependencies

None.


## Example Playbook

    ---
    - hosts: all
      become: yes
      roles:
         - { role: ansible-galaxy-system-users }
