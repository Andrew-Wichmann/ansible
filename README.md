# Ansible

My personal Ansible Playbook to set up an Ubuntu machine just how I like it.

# Requirements

## Ubuntu

```bash
sudo apt update && sudo apt install -y software-properties-common && sudo apt-add-repository -y ppa:ansible/ansible && sudo apt update && sudo apt install -y curl git ansible build-essential
```

# Usage

```bash
git clone https://github.com/Andrew-Wichmann/ansible.git
cd ansible
ansible-playbook local.yml --ask-become-pass --ask-vault-pass
```

# TODO
- [ ] install GoMono nerd font
- [ ] install catppuccin mocha tmux theme
- [ ] install TheFuck

# Credits

Heavily inspired by [ThePrimeagen](https://github.com/ThePrimeagen/ansible/)
