# NixOSDailyDriver
Config for my NixOS machine

https://itsfoss.com/nixos-package-management/

https://itsfoss.com/things-to-do-after-installing-nixos/

https://itsfoss.com/home-manager-nixos/

# edit to add packages
sudo nano /etc/nixos/configuration.nix

# to push changes
sudo nixos-rebuild switch

# find updates
nix-channel --update

# install updates
sudo nixos-rebuild switch --upgrade

# delete old packages etc
nix-collect-garbage
nix-collect-garbage -d

