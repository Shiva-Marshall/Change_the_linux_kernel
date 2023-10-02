# Change_the_linux_kernel   
## First Check the available kernel version using the command   

apt search linux-image    


## Install the Desired Kernel Version:   

sudo apt install linux-image-5.19.x-xx-generic linux-headers-5.19.x-xx-generic    


### Update GRUB:   

After installing the new kernel, you should update GRUB, which is the bootloader configuration, to recognize the new kernel:   

sudo update-grub

### Reboot the system:   

sudo reboot

that's it !!!


