Referencias:

Dell:
https://www.dell.com/support/article/br/pt/brbsdt1/sln298431/um-guia-para-a-nvidia-optimus-em-pcs-dell-com-um-sistema-operacional-ubuntu?lang=pt

Blacklist nouveau
https://linuxconfig.org/how-to-disable-nouveau-nvidia-driver-on-ubuntu-18-04-bionic-beaver-linux
https://tutorials.technology/tutorials/85-How-to-remove-Nouveau-kernel-driver-Nvidia-install-error.html
http://lxle.net/forums/discussion/1457/tutorial-how-to-blacklist-nouveau-install-nvidia-drivers/p1

A propria nvia falar pra usar o driver da distro
https://www.nvidia.com.br/Download/driverResults.aspx/156799/br
http://us.download.nvidia.com/XFree86/Linux-x86_64/435.21/README/index.html


touch blacklist-nouveau-nvidia.conf
nano blacklist-nouveau-nvidia.conf
blacklist nouveau
blacklist lbm-nouveau
options nouveau modeset=0
alias nouveau off
alias lbm-nouveau off

echo options nouveau modeset=0 | sudo tee -a /etc/modprobe.d/balcklist-nouveau-kms.conf

sudo update-initramfs -u
reboot

sudo apt install nvidia-driver-XXX nvidia-prime nvidia-settings
