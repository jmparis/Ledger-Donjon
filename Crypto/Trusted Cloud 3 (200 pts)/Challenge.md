# Trusted Cloud 3
## 200 points

Our favorite cloud hosting provider now enables linking virtual machines with network TPM (Trusted Platform Module). We used it to store the private key of our root certificate authority.

However it seems that a hacker was able to capture the network traffic while we were importing it. We though we were safe, as the tools we used to import the key used encryption to protect the channel where the private key was transmitted. But a recent security advisory stated that this encryption was broken.

Could you prove that you can recover the private key? To prove this, there is an encrypted file in /home/ca/ which contains a flag.

NB. The files are located in the encrypted disk image provided by challenge "Trusted Cloud 1".



Files:
[745262e343f06c6ab45c4a6e61fcfa247760b17f.tar.bz2](./files/745262e343f06c6ab45c4a6e61fcfa247760b17f.tar.bz2)