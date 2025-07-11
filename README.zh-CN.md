# Mon主题Hyprland

这是我基于Gruvbox的主题。
我的灵感来自不同的来源来建立这个主题。

-   终端 ：[猫咪](#workspace)
-   酒吧 ：[Waybar](#waybar)
-   文件管理器：[游侠](#file-manager-ranger)
-   文本编辑：Neovim
-   音乐播放器：[rmpc](#music-player)
-   应用启动器：ROFI
-   电源菜单：ROFI

## 工作区

Neofetch允许您以文本模式以及图像，OS徽标，ASCII或其他形式显示不同的信息系统信息。  
我将ZSHRC用作外壳。  
要显示图像，请添加`neofetch --kitty "$HOME/Images/tux1.png" `在文件中`.zshrc file `.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/hyprland_terminal.png" alt="Bureau">

## 文件经理（游侠）

Ranger是控制台模式的文件管理器。  
Il permet de prévisualiser les images, à l'aide de kitty. Pour cela, il faut ajouter les deux lignes suivantes dans le fichier  `~/.config/ranger/rc.conf`:  
`set preview_images true`  
`set preview_images_method kitty`

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/ranger_preview.png" alt="ranger">

## 音乐播放器

我使用ncmpcpp一段时间了，然后继续前进[rmpc](https://mierak.github.io/rmpc/)我发现更多的用户 - 友好且易于使用。

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rmpc_preview.png" alt="rmpc">

| 应用启动器                                                                                                                                    | 电源菜单                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_app_preview.png" alt="rofi menu" width="500"> | <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_power_menu_preview.png" alt="rofi menu" width="500"> |

## Waybar

![alt text](https://github.com/sesuko023/dotfiles/blob/main/Images/waybar.jpg "Preview waybar")
