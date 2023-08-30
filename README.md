# Automated Ansible Setups
This repo exists to save me a headache setting up new machines.

In order to use it use it, clone the repo. Then run the playbooks with `ansible-playbook`, specifying a become password or using `--ask-become-password` if nessecary.

A few things were copied from [this repo](https://github.com/AlexNabokikh/windows-playbook) achieving a similar thing.

## Feature ideas
Just a list of things I have in mind for this
### Windows
- Ensure Ctrl+D closes Powershell
- Enable Debian WSL
- Install chocolatey
- Copy MS Terminal Config
### Linux (Debian)
- Setup oh-my-zsh
- Setup Ctrl+R for fzf