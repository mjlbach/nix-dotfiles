# My nix dotfiles

nixos contains my nixos configuration, and is symlinked to /etc/nixos

nixpkgs contains my userland nix configuration, and is symlinked to $HOME/.config/nixpkgs via the install script

# To install nix

```bash
curl -L https://nixos.org/nix/install | sh
```

# To install my home-manager configuration

```
cit clone https://github.com/mjlbach/nix-dotfiles.git
cd nix-dotfiles/nixpkgs
bash install.sh {fedora, macos, cluster, nixos}`
bash switch.sh
```

# To install my NixOS configuration

Coming soon...
