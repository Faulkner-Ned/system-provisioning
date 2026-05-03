# Ansible for Configuring My Current 2026 Development Environment

These Ansible playbooks configures a Debian system with the software that I’m currently using in 2026. Lets me set up a working my development environment in minutes instead of hours or days. It works in parallel with my preseed config and my Dotfiles, allowing me to create a USB boot drive for for install Debian with all the software and configurations I used.

## Why Debian? Why KDE Plasma?

I’ve been using Debian-based systems for a long time, mostly Ubuntu in my earlier years. I’m not the type to constantly swap distros for distro/hype sake. This works fine for me.

I’d probably get more benefits from NixOS in the long run, but I’m not in a place where I want to spend hours learning and configuring everything. Maybe one day. As for the desktop environment, I’m on KDE Plasma right now, but honestly, I’m not too fussed about it. GNOME or KDE both work for me.

## What's installed ?

### Utility Tools
- **mise** - Version manager for runtime tools
- **chezmoi** - Dotfile manager
- **wget** - Network downloader
- **tmux** - Terminal multiplexer
- **tree** - Directory listing tool
- **fd** - Fast file finder
- **jq** - JSON processor

### Applications
- **Bitwarden** - Password manager desktop app
- **Mullvad VPN** - Privacy-focused VPN service
- **Ghostty** - Terminal emulator
- **Spotify** - Music streaming client
- **Discord** - Voice and text chat
- **zed** - Modern code editor
- **vim** - Terminal text editor
- **neovim** - Hyperextensible Vim-based editor

### Docker
- **docker-ce** - Docker engine
- **docker-ce-cli** - Docker command line interface
- **containerd.io** - Container runtime
- **docker-compose-plugin** - Docker Compose plugin
- User is added to the `docker` group automatically

### Fonts
- **Lilex** - Monospace font for developers (https://lilex.myrt.co/)

## Where is everything else
I tend to run a very 'stock'/lightweight build. I don't likely relying on too many external tools. Often times I am work on remote systems which don't have all the 'fancy' tools/QoL additions, so I learnt to wield the base unix commands to my advantags.

I am a very big fan of Mise. I manage all installations of programming language runtimes and other tools for local development using it. It makes it very easy to manage multiple versions of different languages using only one tool. These can all be found in my dotfiles.
