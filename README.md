# manjaro-bootsplash-mi
Nothing special, just another bootsplash theme for Manjaro Linux (Xiaomi logo). 

# installation & configuration

run bootsplash-manjaro-mi.sh to generate bootsplash-manjaro-mi STL model
run makepkg to create Arch package and install it with pacman -U %packagename%
append bootsplash-manjaro-mi hook into HOOKS /etc/mkinitcpio.conf
add quiet bootsplash.bootfile=bootsplash-themes/manjaro-mi/bootsplash into GRUB_CMDLINE_LINUX /etc/default/grub
sudo mkinitcpio -p linux414
sudo update-grub
