# ArchLinux
 
## Find miscellaneous Arch-related files here!

### 230129 Added Xfce desktop package list

order KDE

pacman -Syy

pacman -Syu

pacman -S --needed - < ArchISO_paclist_221216.txt

pacman -S --needed - < Drivers_paclist_221216.txt

pacman -S --needed - < Net_paclist_221216.txt

pacman -S --needed - < Fonts_paclist_221216.txt

pacman -S --needed - < Print_paclist_221216.txt

pacman -S --needed - < MMedia_paclist_221216.txt

pacman -S --needed - < Xorg_paclist_221216.txt

pacman -S --needed - < KDE_paclist_221216.txt

pacman -S --needed - < Apps_paclist_221216.txt

systemctl enable avahi-daemon
systemctl enable bluetooth.service
systemctl disable dhcpcd.service
systemctl enable haveged.service
systemctl enable cups.service
systemctl enable firewalld.service
systemctl enable sddm.service
systemctl enable NetworkManager
systemctl enable sshd
systemctl enable upower

usermod -aG \
sys,adm,network,scanner,power,uucp,audio,lp,rfkill,video,storage,optical,users \
username

reboot
