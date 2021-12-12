# `sudo set-up my-mac`

## TL;DR
set up my MacBook via Ansible  

`$ ansible-playbook site.yml`

## Requirements
- Ansible >= 2.12.1
- Python >= 3.5 [Ansible Docs -> Python 3 Support](https://docs.ansible.com/ansible/latest/reference_appendices/python_3_support.html)

## Install List
```yaml
brew:
  - "openssl@1.1"
  - "readline"
  - "sqlite"
  - "xz"
  - "python@3.9"
  - "curl"
  - "fd"
  - "gcc"
  - "fish"
  - "fzf"
  - "gawk"
  - "git"
  - "go"
  - "htop"
  - "mysql"
  - "neovim"
  - "node"
  - "ruby"
  - "starship"
  - "tig"
  - "tldr"
  - "tmux"
  - "wget"
  - "zlib"
  - "zlib-ng"

cask:
  - "alfred"
  - "arduino"
  - "discord"
  - "dozer"
  - "dropbox"

tap:
  - "homebrew/bundle"
  - "homebrew/cask"
  - "homebrew/cask-fonts"
  - "homebrew/core"
  - "homebrew/services"
```