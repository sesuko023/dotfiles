# 我的Hyprland主題

這是我的gruvbox主題。
我使用了根據自己的口味修改的網上發現的不同來源。

-   終端 ：[貓咪](#workspace)
-   酒吧 ：[Waybar](#waybar)
-   文件管理器：[遊俠](#file-manager-ranger)
-   文本編輯：Neovim
-   music player : [rmpc](#music-player)
-   應用啟動器：ROFI
-   電源菜單：ROFI

## 工作區

NeoFetch顯示了您選擇的圖像，OS徽標或任何ASCII文件旁邊的操作系統信息。  
我的外殼是ZSHRC。  
要顯示圖像，請添加`neofetch --kitty "$HOME/Images/tux1.png" `在`.zshrc file `.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/hyprland_terminal.png" alt="Bureau">

## 文件經理（遊俠）

Ranger是控制台文件管理器。
要啟用預覽圖像，使用小貓可以添加以下兩行：`set preview_images true``set preview_images_method kitty`在`~/.config/ranger/rc.conf`文件。

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/ranger_preview.png" alt="ranger">

## 音樂播放器

我在切換到[rmpc](https://mierak.github.io/rmpc/)我發現使用更令人愉悅。

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rmpc_preview.png" alt="rmpc">

| 應用啟動器                                                                                                                                    | 電源菜單                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_app_preview.png" alt="rofi menu" width="500"> | <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_power_menu_preview.png" alt="rofi menu" width="500"> |

## Waybar

![alt text](https://github.com/sesuko023/dotfiles/blob/main/Images/waybar.jpg "Preview waybar")
