# encrypt and decrypt a file with pgp

Select a file to encrypt/decrypt through gpg.
    
+++++++++++++++++++++++++++++++++++++++++++++

Install gpg on Linux or Termux.

apt-get install -y gpg
  or
pkg istall -y gnupg

+++++++++++++++++++++++++++++++++++++++++++++

Uses single prefix to quick encrypt/decrypt file after recognizing if file is .gpg or not.

EXAMPLE: 
  bash EandD file.txt
    or
  bash EandD file.txt.gpg
