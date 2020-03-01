# Elementary XP
Desde que eu fui forçado a migrar do Deepin por causa do suporte ao HW do meu note novo eu voltei a olhar pro Elementary que eu sempre quis usar...



## Jogos
https://connorkuehl.github.io/dell-inspiron-7559-linux-guide/
https://www.reddit.com/r/linux_gaming/comments/aoh5be/guide_hybrid_graphics_on_linux_nvidia_optimus/?utm_source=amp&utm_medium=&utm_content=post_body

Isso funciona para o video
https://www.dell.com/support/article/br/pt/brbsdt1/sln298431/um-guia-para-a-nvidia-optimus-em-pcs-dell-com-um-sistema-operacional-ubuntu?lang=pt

mais sobre o video
https://www.reddit.com/r/linux_gaming/comments/aoh5be/guide_hybrid_graphics_on_linux_nvidia_optimus/

linux prime is not supported?
https://forum.manjaro.org/t/howto-set-up-prime-with-nvidia-proprietary-driver/40225


tema
https://github.com/B00merang-Project/Windows-10
https://github.com/nana-4/materia-theme
https://github.com/adapta-project/adapta-gtk-theme

icons
https://www.edivaldobrito.com.br/material-design-paper-no-ubuntu/
https://github.com/surajmandalcell/elementary-x/blob/master/install_fixed_icons.sh

cursor
https://www.gnome-look.org/p/1084938/

Ajuste da altura do tema
https://unix.stackexchange.com/questions/276951/how-to-change-the-titlebar-height-in-standard-gtk-apps-and-those-with-headerbars

coisas pra fazer depois de instalar
https://gist.github.com/ankurk91/2327d4881d71a098e3bfcd0b1c255d83

https://ditchwindows.com/elementary-os-community-tips-and-tricks/

https://averagelinuxuser.com/after-install-elementary-juno/

https://github.com/mdh34/elementary-indicators
https://www.youtube.com/watch?v=rg2YBhl7Zhg synapse
http://www.webupd8.org/2013/06/synapse-indicator-new-search.html

https://app.simplenote.com/p/tJ0t2R

http://eos-snippets.blogspot.com/2013/10/fix-boot-screen-plymouth-after.html

https://elementaryos.stackexchange.com/questions/13058/replacing-slingshot


https://github.com/snwh/paper-icon-theme commando para ajustar icon
https://github.com/PapirusDevelopmentTeam/papirus-icon-theme

## Perfect elementary references
https://gist.github.com/ezeeyahoo/b21c0e12bf4c39622af8

http://eos-snippets.blogspot.com/2014/02/add-open-as-root-to-pantheon-files.html

https://www.linuxuprising.com/2019/07/material-shell-is-new-tiling-shell-for.html


## single click (no need sudo)
gsettings set io.elementary.files.preferences single-click false

## grub themes
https://github.com/mateosss/matter
https://github.com/vinceliuice/grub2-themes
https://github.com/endeavouros-team/grub2-theme-endeavouros
https://github.com/shvchk/poly-dark
https://github.com/Generator/Grub2-themes
http://grub.gibibit.com/Theme_format

## grub
http://www.pclinuxos.com/forum/index.php?topic=135915.0
https://ubuntuforums.org/showthread.php?t=1287602

## default grub wallpaper
https://news-cdn.softpedia.com/images/news2/here-s-the-default-theme-and-artwork-for-debian-gnu-linux-10-buster-524538-4.jpg

## default wallpaper + lidghtdm 
https://www.faqforge.com/linux/set-lightdm-wallpaper-that-is-independant-of-the-users-wallpaper-ubuntulinux-mint/
gsettings get org.gnome.desktop.background picture-uri

## etc/systemd to reduce timeout for shutdown
https://unix.stackexchange.com/questions/273876/a-stop-job-is-running-for-session-c2-of-user
Disable "Continue running background apps when Google Chrome is closed".
https://github.com/systemd/systemd/issues/1615#issuecomment-203507283
https://unix.stackexchange.com/questions/328317/reducing-shutdown-timeout-for-a-stop-job-is-running

## Flicker free booting improvments
Systemd Alinhando XDG_VTNR
https://unix.stackexchange.com/questions/521037/what-is-the-environment-variable-xdg-vtnr https://askubuntu.com/questions/910108/why-is-my-gdm-at-a-different-tty-than-my-desktop-environment
https://unix.stackexchange.com/questions/399986/systemd-change-default-login-tty

/etc/init/lightdm.conf
/etc/systemd/system/display-manager.service

## TLP no PopOS
https://support.system76.com/articles/battery/
