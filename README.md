# binary

This is cross compile container.You can use it to compile the roller_eye project on the ubuntu host.  
Follow these steps：

```bash
sudo apt-get update && apt-get install git git-lfs qemu-user-static
sudo git lfs clone --depth 1 https://github.com/Pilot-Labs-Dev/binary.git  
sudo tar -zxvf ./binary/binary.tar.gz  
sudo chroot binary  
su linaro  
```
