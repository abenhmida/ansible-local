A little collection of ansible playbooks
----------------------------------------

This collection provide various playbooks to configure a local development machine. It is a work in progress.

You can execute any playbook independantly of the other wiht command

`ansible-playbook --ask-become-pass config-playbook.yml` 

you can use the `--ask-become-pass` to have the necessary previliges to install dependencies.
