# Trusted Cloud 2
## 200 points

Our favorite cloud hosting provider now enables linking virtual machines with network TPM (Trusted Platform Module). We moved our services to encrypt passwords using RSA keys stored on the TPM.

We thought we were safe, but one of our admins also configured a password on the TPM-protected keys. We have just rebooted the server and now we realized that we did not remember the password. Oops.

Thankfully our hosting provider shared with us the network TPM we are using. It is a virtual machine which can be booted with QEMU.

Can you please decrypt our file?

NB. The files are located in /home/passwords/ in the encrypted disk image provided by challenge "Trusted Cloud 1".



Files:
[ee8e500b7d46ebbd694e47649c1445876916fcde.tar.bz2](./files/ee8e500b7d46ebbd694e47649c1445876916fcde.tar.bz2)