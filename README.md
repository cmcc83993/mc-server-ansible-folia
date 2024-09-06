# Ansible Minecraft Server with Folia on Ubuntu 22.04

This Ansible playbook will allow you to install and setup a minecraft server
based on [Folia](https://github.com/PaperMC/Folia).

How to run:

```bash
ansible-galaxy install -r requirements.yml
ansible-playbook folia.yml -i hosts -u <your user> --ask-pass --ask-become-pass
```

By default, the Minecraft server will run on port 25565, with rcon available
on the server's localhost on 25575.
