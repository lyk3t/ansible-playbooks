# ansible-playbooks


Goal is to reduce the overhead of setting up all tools and stuff for CTF and bounty hunting when setting up a new machine.

## Install ansible

Installing the dependencies
`yay -S ansible`


## add the yay modules

ensure that the yay modules can be used
```
sudo mkdir /usr/share/ansible/plugins
sudo mkdir /usr/share/ansible/plugins/modules
sudo cp yay /usr/share/ansible/plugins/modules
```

## add go module




## Running tags

Run tags:
`sudo ansible-playbook play-arch.yml --tags "utils,pip3,go"`

Run whole playbook:
`sudo ansible-playbook play-arch.yml`


## TODOs
[] setup of dotfiles
[] dependencies for editor/prompt/shell
[] dependencies for window manager(s)
[] find a better way to handle Go packages
