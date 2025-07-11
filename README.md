<img
  src="https://flagcdn.com/20x15/gb.png"
  srcset="https://flagcdn.com/40x30/gb.png 2x,
    https://flagcdn.com/60x45/gb.png 3x"
  width="20"
  height="15"
  alt="Royaume-Uni">
 [Engish version](https://github.com/sesuko023/dotfiles/blob/main/README.md)

# Mon theme hyprland

Voici mon thème basé sur gruvbox.
Je me suis inspiré de différentes sources pour construire ce thème.

+ terminal : [kitty](#workspace)
+ bar : [waybar](#waybar)
+ file manager : [ranger](#file-manager-ranger)
+ éditeur de texte : neovim
+ music player : [rmpc](#music-player)
+ App launcher : rofi
+ power menu : rofi

## Workspace

Neofetch permet d'afficher différentes informations systèmes en mode texte ainsi que des images, le logo de l'OS, sous forme ASCII ou autre.  
J'utilise zshrc comme shell.  
Pour afficher une image, ajouter ``` neofetch --kitty "$HOME/Images/tux1.png"  ``` dans le fichier  ``` .zshrc file  ```.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/hyprland_terminal.png" alt="Bureau">

## File manager (ranger)

Ranger est un gestionnaire de fichiers en mode console.  
Il permet de prévisualiser les images, à l'aide de kitty. Pour cela, il faut ajouter les deux lignes suivantes dans le fichier  ``` ~/.config/ranger/rc.conf ```  :  
``` set preview_images true ```  
``` set preview_images_method kitty ```  

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/ranger_preview.png" alt="ranger">

## Music player

J'ai utilisé pendant un certain temps ncmpcpp, avant de passer à [rmpc](https://mierak.github.io/rmpc/) que je trouve plus convivial et plus simple d'utilisation.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rmpc_preview.png" alt="rmpc">

| App launcher | Power menu |
| ---- | --- |
| <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_app_preview.png" alt="rofi menu" width="500"> | <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_power_menu_preview.png" alt="rofi menu" width="500"> |


## Waybar

![alt text](https://github.com/sesuko023/dotfiles/blob/main/Images/waybar.jpg "Preview waybar")
