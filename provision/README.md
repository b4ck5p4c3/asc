Provisioning scripts requires \*nix host with POSIX-compiant shell and docker-machine preinstalled.

To provision a brand new Raspberry PI:
1. write the latest [Raspbian lite image](http://downloads.raspberrypi.org/raspbian_lite/images/) to an SD card, using something like `dd if=raspbian.img of=/dev/sdb status=progress`
2. run `provision_1_sd_card`
3. install SD card, power up Raspberry PI and somehow discover its IP address
4. run `provision_2_ssh_docker`
