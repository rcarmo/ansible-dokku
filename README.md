# ansible-dokku

This ansible playbook provisions an Ubuntu 14.04 server with a `dokku` environment that matches what I currently use in `dokku-alt`, using the official `dokku` .deb packages instead of building from source.

## Instructions

```
$ cp inventory.dist inventory.txt
$ vi inventory.txt
$ ansible-playbook --ask-sudo-pass -i inventory.txt main.yml
```
