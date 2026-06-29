# GRUB/Ventoy-Theme-CRT-TV

GRUB/Ventoy Theme looking like old CRT TV

1024x768
<br>![](https://github.com/bulat-chu/GRUB-Theme-CRT-TV/blob/main/screenshots/CRT-TV_1024x768.png)

1920x1080
<br>![](https://github.com/bulat-chu/GRUB-Theme-CRT-TV/blob/main/screenshots/CRT-TV_1920x1080.png)

How to install

Ventoy:
1. Copy ```ventoy_grub.cfg``` and ```ventoy.json``` and paste into ```ventoy/``` directory
2. Copy ```CRT-TV``` directory and paste into ```ventoy/themes/``` directory
 
GRUB:
1. Copy ```CRT-TV``` directory and paste into ```/boot/grub/themes/CRT-TV``` directory
2. Open ```/etc/default/grub```
3. Uncomment ```GRUB_THEME="blah-blah"``` and add ```/boot/grub/themes/CRT-TV/theme.txt``` instead of "blah-blah"
4. "Apply" ```sudo grub-mkconfig -o /boot/grub/grub.cfg``` and ```sudo grub-mkconfig -o /boot/efi/EFI/arch/grub/grub.cfg```
