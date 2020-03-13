# HackTheBox-Plymouth-Theme
Simple Plymouth Theme with HackTheBox logo!


Getting Started

    Use sudo preview.sh to view actual Plymouth splash

    If you cant see any splash you have to activate it first in grub /etc/default/grub

     GRUB_CMDLINE_LINUX_DEFAULT="quiet splash"

    Dont forget to use sudo update-grub after changes in grub

Install

sudo cp -R ./brogit-plymouth-theme /usr/share/plymouth/themes/


sudo plymouth-set-default-theme brogit-plymouth-theme -R
