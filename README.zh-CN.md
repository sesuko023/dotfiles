<img
  src="https://flagcdn.com/20x15/gb.png"
  srcset="https://flagcdn.com/40x30/gb.png 2x,
    https://flagcdn.com/60x45/gb.png 3x"
  width="20"
  height="15"
  alt="Royaume-Uni">[结尾版](https://github.com/sesuko023/dotfiles/blob/main/README.en.md)

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

Ranger est un gestionnaire de fichiers en mode console.  
它允许您使用小猫预览图像。为此，将以下两行添加到文件中`~/.config/ranger/rc.conf`:  
`set preview_images true`  
`set preview_images_method kitty`

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/ranger_preview.png" alt="ranger">

## 音乐播放器

在继续前进之前[rmpc](https://mierak.github.io/rmpc/)我发现更多的用户 - 友好且易于使用。  
使用的配置文件不是默认情况下，我添加了有关北方主题的部分。
必须事先安装配置[MPD](https://wiki.archlinux.org/title/Music_Player_Daemon_(Fran%C3%A7ais)).

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rmpc_player_preview.png" alt="rmpc">

| 应用启动器                                                                                                                                    | 电源菜单                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_app_preview.png" alt="rofi menu" width="500"> | <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_power_menu_preview.png" alt="rofi menu" width="500"> |

## Waybar

![alt text](https://github.com/sesuko023/dotfiles/blob/main/Images/waybar.jpg "Preview waybar")
