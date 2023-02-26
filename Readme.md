🖋️ A little collection of ansible playbooks
----------------------------------------

This collection provides various playbooks to configure a local development machine. It is a work in progress.

You can execute any playbook independently of the other with the command

`ansible-playbook --ask-become-pass config-playbook.yml` 

you can use the `--ask-become-pass` to have the necessary privileges to install dependencies.

✔️  These playbooks are intentionally left separated from one another, to give more usage flexibilty, but
you can use in what ever configuration you want, be it separated or merged or defined in roles.
