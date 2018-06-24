# ansible

A repository containing ansible projects

/etc/ansible/hosts: the groups of servers we consider
/etc/ansible/ansible.cfg: the ansible configuration. We have to set the private key path and turn off authentication via password.
The authentication is based on public key cryptography.

basic test: ansible test_vms -m shell -a "echo $HOME"
