# My hyprland theme

This is my gruvbox theme.
I used different sources found on the net that I modified according to my tastes.

+ terminal : [kitty](#workspace)
+ bar : [waybar](#waybar)
+ file manager : [ranger](#file-manager-ranger)
+ text editor : neovim
+ music player : [rmpc](#music-player)
+ App launcher : rofi
+ power menu : rofi

## Workspace

Neofetch displays operating system information next to an image, the OS logo, or any ASCII file of your choice.  
My shell is  zshrc.  
To display image, add ``` neofetch --kitty '/home/emmanuel/Images/tux1.png'  ``` in  ``` .zshrc file  ```.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/hyprland_terminal.png" alt="Bureau">

## File manager (ranger)

Ranger is a console file manager.
To enable preview image, using kitty, you can add these two lines :
``` set preview_images true ```
``` set preview_images_method kitty ```
in ``` ~/.config/ranger/rc.conf ``` file.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/ranger_preview.png" alt="ranger">

## Music player

I used ncmpcpp for a while, before switching to [rmpc](https://mierak.github.io/rmpc/) which I find more pleasant to use.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rmpc_preview.png" alt="rmpc">

| App launcher | Power menu |
| ---- | --- |
| <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_app_preview.png" alt="rofi menu" width="500"> | <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_power_menu_preview.png" alt="rofi menu" width="500"> |


## Waybar

![alt text](https://github.com/sesuko023/dotfiles/blob/main/Images/waybar.jpg "Preview waybar")
