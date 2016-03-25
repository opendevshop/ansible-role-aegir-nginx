Ansible Role: Aegir NGINX
=========

Extends the geerlingguy.nginx role to allow usage as an aegir remote server.

Tasks
=====

This role does very little: 

- Symlink from /etc/apache/conf.d to Aegir's Apache.conf
- Add to sudoers to allow aegir to reload apache.
