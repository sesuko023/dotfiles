# موضوع Hyprland الخاص بي

هذا هو موضوع Gruvbox الخاص بي.
لقد استخدمت مصادر مختلفة موجودة على الشبكة التي قمت بتعديلها وفقًا لأذواقي.

-   صالة :[كيتي](#workspace)
-   حاجِز :[Waybar](#waybar)
-   مدير الملف:[الحارس](#file-manager-ranger)
-   محرر النصوص: Neovim
-   مشغل الموسيقى:[RMPC](#music-player)
-   قاذفة التطبيق: ROFI
-   قائمة الطاقة: ROFI

## مساحة العمل

يعرض Neofetch معلومات نظام التشغيل بجوار صورة أو شعار OS أو أي ملف ASCII من اختيارك.  
بلدي قذيفة ZSHRC.  
لعرض الصورة ، أضف`neofetch --kitty "$HOME/Images/tux1.png" `في`.zshrc file `.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/hyprland_terminal.png" alt="Bureau">

## مدير الملفات (الحارس)

Ranger هو مدير ملفات وحدة التحكم.
لتمكين معاينة صورة ، باستخدام كيتي ، يمكنك إضافة هذين الخطين:`set preview_images true``set preview_images_method kitty`في`~/.config/ranger/rc.conf`ملف.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/ranger_preview.png" alt="ranger">

## مشغل الموسيقى

لقد استخدمت NCMPCPP لفترة من الوقت ، قبل التحول إلى[RMPC](https://mierak.github.io/rmpc/)التي أجدها أكثر متعة للاستخدام.

<img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rmpc_preview.png" alt="rmpc">

| قاذفة التطبيق                                                                                                                            | قائمة الطاقة                                                                                                                                    |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_app_preview.png" alt="rofi menu" width="500"> | <img src="https://raw.githubusercontent.com/sesuko023/dotfiles/refs/heads/main/Images/rofi_power_menu_preview.png" alt="rofi menu" width="500"> |

## Waybar

![alt text](https://github.com/sesuko023/dotfiles/blob/main/Images/waybar.jpg "Preview waybar")
