# Ansible Role SSH

manage SSH configuration

## Role variables

| variable | default | description |
| --- | --- | --- |
| `ssh_passwordauthentication` | `'no'` | value for [`PasswordAuthentication`](https://man.openbsd.org/sshd_config#PasswordAuthentication) in /etc/sshd_config |
| `ssh_trusted_user_ca_keys` | | content of `/etc/ssh/trusted-user-ca-keys.pem` as value for [`TrustedUserCAKeys`](https://man.openbsd.org/sshd_config#TrustedUserCAKeys) |
| `sshd_remove_authorized_keys` | `false` | if the file `/root/.ssh/authorized_keys` should be deleted |
