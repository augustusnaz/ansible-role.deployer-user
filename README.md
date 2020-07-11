Ansible Role: Deployer User
=========

Creates a user with ssh keys and wrx permissions on /var/www directly. Intended for deploying web app artifacts and for [KeyHelp](https://www.keyhelp.de/en/) hosted servers.



Role Variables
--------------

| Var                | Description           | Default    |
| ------------------ | --------------------- | ---------- |
| `ssh_key_filename` | RSA SSH Key name      | `id_rsa`   |
| `deployer_user`    | The created user name | `deployer` |

**Defaults**:

| Var                 | Description                                                  | Default |
| ------------------- | ------------------------------------------------------------ | ------- |
| `keyhelp_installed` | Grants `deployer_user` user wrx access to "/home/users" when set to `true` | `false` |



Dependencies
------------

Written for Ubuntu linux.



License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
