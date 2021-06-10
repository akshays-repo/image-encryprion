# Henon-Arnold-Image-Encryption
Chaos-based image encryption for RGB images using combination of Henon map and Arnold cat map as the chaotic maps.
This encryption method needs a shared secret key for the Henon map and Arnold cat map parameters/initial values, which involves Diffie-Hellman algorithm for the key generation.

## How to encrypt
- Run **main.py**
- If you don't have the key pairs, **Generate new key pairs**
- Login with the generated private key
- Select **encrypt** mode
- Add images to be encrypted
- Select output destination path
- Input **receiver's public key**
- Encrypt

## How to decrypt 
- Run **main.py**
- Login with **your private key**
- Select **decrypt** mode
- Add images to be decrypted
- Select output destination path
- Input **sender's public key**
- Decrypt
