# binary
This is cross compile container.You can use it to compile the roller_eye project on the ubuntu host.  
binary.tar.gz is a large file. You need to install git lfs to download it.

Follow these steps： 

sudo apt-get update
sudo apt-get install git-lfs
git lfs install

sudo apt-get install qemu-user-static  
sudo git clone https://github.com/Pilot-Labs-Dev/binary.git  
sudo tar -zxvf binary.tar.gz  
sudo chroot binary  
su linaro  
