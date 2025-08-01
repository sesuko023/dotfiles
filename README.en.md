<img
  src="https://flagcdn.com/20x15/gb.png"
  srcset="https://flagcdn.com/40x30/gb.png 2x,
    https://flagcdn.com/60x45/gb.png 3x"
  width="20"
  height="15"
  alt="Royaume-Uni">[Engish version](https://github.com/sesuko023/dotfiles/blob/main/README.en.md)

# Mon theme hyprland

Here is my theme based on Gruvbox.
I was inspired by different sources to build this theme.

-   terminal :[kitty](#workspace)
-   bar :[waybar](#waybar)
-   file manager :[ranger](#file-manager-ranger)
-   Text editor: Neovim
-   music player :[RMPC](#music-player)
-   App Launcher: Rofi
-   Power Menu: Rofi

## Workspace

Neofetch allows you to display different information systems information in text mode as well as images, the OS logo, in ASCII or other form.  
I use Zshrc as Shell.  
To display an image, add`neofetch --kitty "$HOME/Images/tux1.png" `in the file`.zshrc file `.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/hyprland_terminal.png" alt="Bureau">

## File manager (ranger)

Ranger is a file manager in console mode.  
It allows you to preview the images, using Kitty. To do this, add the following two lines to the file`~/.config/ranger/rc.conf`:  
`set preview_images true`  
`set preview_images_method kitty`

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/ranger_preview.png" alt="ranger">

## Music player

I used NCMPCPP for a certain time as MPD customer, before moving on to[RMPC](https://mierak.github.io/rmpc/)that I find more user -friendly and easier to use.  
The configuration file used is not that by default, I added the section concerning that of the northern theme.
It is necessary, beforehand, to install configure[MPD](https://wiki.archlinux.org/title/Music_Player_Daemon_(Fran%C3%A7ais)).

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rmpc_player_preview.png" alt="rmpc">

| App launcher                                                                                                                             | Power menu                                                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_app_preview.png" alt="rofi menu" width="500"> | <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_power_menu_preview.png" alt="rofi menu" width="500"> |

## Waybar

![alt text](https://github.com/sesuko023/dotfiles/blob/main/Images/waybar.jpg "Preview waybar")
