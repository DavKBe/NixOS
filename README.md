# NixOS

--->>> Editer une configuration

sudo nano /etc/nixos/configuration.nix



--->>> Mettre à jour le système

sudo nixos-rebuild switch

ou

sudo nixos-rebuild switch && reboot

___________________________________________________________________________________________________________

# Ressources:

Packages NixOS

https://search.nixos.org/packages

Reporter des problèmes avec les Packages

https://github.com/NixOS/nixpkgs/issues

Tutos fonctionnel

https://nokomprendo.gitlab.io/posts/tuto_fonctionnel_45/2020-11-09-fr-README.html

Divers

https://github.com/dustinlyons/nixos-config?tab=readme-ov-file

Organiser les flakes

https://www.reddit.com/r/NixOS/comments/1e95b69/how_do_you_guys_organize_your_nix_config_files_i/?tl=fr&rdt=35850

Problème avec Vivaldi

https://github.com/NixOS/nixpkgs/issues/309056


___________________________________________________________________________________________________________
Config
___________________________________________________________________________________________________________

  # Navigateurs # 

  ungoogled-chromium
  #vivaldi # broken

  # Communicators #

  protonmail-desktop   
  # whatsapp-for-mac # broken
  whatsapp-for-linux 
  telegram-desktop  

  # Dev #

  termius 
  vscodium

  # Divers #

  # Network #

  protonvpn-gui
  
  #Sync  #

  resilio-sync
  syncthing
  syncthingtray  # Tray application and Dolphin/Plasma integration for Syncthing

