# Never gonna give

After the afterparty, our good friend Rick told us that its btc  account got hacked! The bad guy is trying to blackmail him and sent him  an audio file with instructions... Luckily for us, it seems that we  might be able to do something with this file. Can you help him and  recover the hacker's secret key?

The bad guy used bip44 to derivate his public address (on path m/44'/0'/0'/0/0).

In order to get the flag, you must decrypt ciphertext.txt with AES-256, in ECB mode, by using the hacker's (BIP32) root key.

[d94561e68d3d049a83efab2c4e9698872a020793.tar.bz2](./files/d94561e68d3d049a83efab2c4e9698872a020793.tar.bz2)
