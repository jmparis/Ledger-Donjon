masked_boot

A hardware wallet vendor protects the storage of the user PIN by  using firmware encryption. The encrypted user PIN is stored on an  off-chip flash memory. After dumping the external flash that contains the encrypted PIN, I  managed to control the flash contents and register the power consumption during the power up while the flash decryption was performed. AES-128 algorithm is used inverted in the flash encryption, so the flash encryption "encrypt" operation is AES decrypt and the "decrypt"  operation is AES encrypt. 

Could you help me to extract the PIN?

[e25c92afae9aff7d38e876e27bbaee9398e806e9.tar.bz2](./files/e25c92afae9aff7d38e876e27bbaee9398e806e9.tar.bz2)

