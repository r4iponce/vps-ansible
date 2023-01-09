# Ansible's collection for settings up my vps

Roles are make and tested for fedora

## Role :
### dnf
Configure automatic update (with dnf-automatic) and upgrade system.

###  timesyncd
Set timezone and enable ntp

### firewalld
Install and configure firewalld to allow ssh.

### fail2ban
Configure fail2ban for ssh.

### journald
configure journald to keep 7 days log

### nginx
Configure strong TLS with ticket keys rotation. Also configure reverse proxy thing. Log are sent to journald.

### acme
Get wildcard certificates from let's encrypt.

### sshd
Make sshd config more strict and secure

### docker
Install docker
