# 我的Hyprland主题

这是我的gruvbox主题。
我使用了根据自己的口味修改的网上发现的不同来源。

-   终端 ：[猫咪](#workspace)
-   酒吧 ：[Waybar](#waybar)
-   文件管理器：[游侠](#file-manager-ranger)
-   文本编辑：Neovim
-   音乐播放器：[rmpc](#music-player)
-   应用启动器：ROFI
-   电源菜单：ROFI

## 工作区

NeoFetch显示了您选择的图像，OS徽标或任何ASCII文件旁边的操作系统信息。  
我的外壳是ZSHRC。  
要显示图像，请添加`neofetch --kitty "$HOME/Images/tux1.png" `在`.zshrc file `.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/hyprland_terminal.png" alt="Bureau">

## 文件经理（游侠）

Ranger是控制台文件管理器。
要启用预览图像，使用小猫可以添加以下两行：`set preview_images true``set preview_images_method kitty`在`~/.config/ranger/rc.conf`文件。

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/ranger_preview.png" alt="ranger">

## 音乐播放器

我在切换到[rmpc](https://mierak.github.io/rmpc/)我发现使用更令人愉悦。

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rmpc_preview.png" alt="rmpc">

| 应用启动器                                                                                                                                    | 电源菜单                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_app_preview.png" alt="rofi menu" width="500"> | <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_power_menu_preview.png" alt="rofi menu" width="500"> |

## Waybar

![alt text](https://github.com/sesuko023/dotfiles/blob/main/Images/waybar.jpg "Preview waybar")
