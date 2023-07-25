# Openssl_EVP_Sample
Encrypt and Decryption of a file using aes256_cbc type of encryption method.

Machine: Any Windows Version \n
Visual Studio 2015 or later. \n
Openssl 3.0 \n

1. Open VS<version> x64 Native Tools Command Prompt.
2. cl.exe EncryptDecrypt.c /I <openssl_include_directory> libcrypto.lib
3. Exe will be generated.

How To Use:
Usage: EncryptDecrypt.exe /path/to/file
e.g Usage: EncryptDecrypt.exe .\encrypt.txt

For ease: Exe file is also uploaded.
