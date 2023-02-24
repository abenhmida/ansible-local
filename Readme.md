A little collection of ansible playbooks
----------------------------------------

This collection provides various playbooks to configure a local development machine. It is a work in progress.

You can execute any playbook independantly of the other with the command

`ansible-playbook --ask-become-pass config-playbook.yml` 

you can use the `--ask-become-pass` to have the necessary privileges to install dependencies.
