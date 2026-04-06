# Ansible for Configuring My Current 2026 Development Environment

This Ansible playbook configures a debian system with the software and configuration I’m currently using in 2026. Lets me set up a working my development environment in minutes instead of hours or days. It works in parallel with my preseed config, allowing me to create a USB boot drive for installing Debian and automatically installing all the necessary software and configurations onto a new device but can be run independently.

I will update this playbook and my [dotfile repo](https://github.com/Faulkner-Ned/dotfiles) regularly to reflect the software and configurations to ensure that its up-to date.


## Why Debian? Why KDE Plasma?

I’ve been using Debian-based systems for a long time, mostly Ubuntu in my earlier years. I’m comfortable with it, and I’m not the type to constantly swap distros for distro/hype sake. This works fine for me.

I’d probably get more benefits from NixOS in the long run, but I’m not in a place where I want to spend hours learning and configuring everything. Maybe one day.

As for the desktop environment, I’m on KDE Plasma right now, but honestly, I’m not too fussed about it. GNOME or KDE both work for me.


## What Gets Configured?
### OS Configuration 
KDE settings, Wallpapers, Directory Structure.

### Software Instilation
**Applications**: Spotify, VSCode, Discord, Bitwarden, MullvadVPN, Firefox, Ghosttly, Vim, Neovim

**Utility**: Chezmoi, wget, Starship, Tmux, Tree

**Programming Languages**: Pyenv, Python 3.14, Pip, Pipx, Nvm, Npm, nodeJS 24.14, Gvm, Golang 1.26, Java SE 21, C++ Runtime

**DevOps**: Docker, Kuberneties, Kubectl, Helm, AWS CLI, Terraform, Kubectx

### Dotfiles Configuration
[My dotfiles](https://github.com/Faulkner-Ned/dotfiles), These are managed by Chezmoi. 

### Fonts
- JetBrains Mono
- Fira Code Nerd Font
