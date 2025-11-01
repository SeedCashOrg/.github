# SeedCash: A Specialized Device for Managing Bitcoin Cash

## General Description
SeedCash is an specialized device for ultimate security and control over your Bitcoin Cash (BCH). It empowers users to **be their own bank**, offering complete control over private keys and funds while remaining isolated from potential threats. SeedCash focuses exclusively on **BCH security**, providing a reliable, auditable, and user-friendly solution.  

---

## Security Measures
SeedCash implements multiple layers of security:  

- **Air-gapped operation**: The device works offline, reducing exposure to online attack vectors.  
- **Amnesia / No memory**: The device does **not store any private keys or any data** in memory after use.
- **Source Available code**: Publicly auditable to ensure trust and transparency.
- **GPG-signed images**: Each SeedCash .img file includes a digital signature for authenticity verification.
  
---

## Features
- **Generate Seed**: Securely create private keys.   
  - **BIP-39**: 12 words  
  - **BIP-39**: 15 words  
  - **BIP-39**: 18 words  
  - **BIP-39**: 21 words  
  - **BIP-39**: 24 words
    
  - **SLIP-39**: 20 words  
  - **SLIP-39**: 33 words

- **Generate XPUB**: Export extended public keys for watch-only wallets.  

- **Generate XPRIV**: Export extended private keys.  

- **Generate BCH Addresses**: Supports both Cashaddr and Legacy formats.  

- **Sign Transactions**: Feature still in development.  

- **Educational Articles Collection**: Step-by-step guidance and resources for safe BCH management:

### Theoretical and Practical Fundamentals
1. Everything you need to know to use Bitcoin Cash with SeedCash
2. Step-by-step practical guide to using SeedCash
3. Storage and backup of a mnemonic phrase in Bitcoin Cash

### Bitcoin Cash Technical Functioning
4. Public and private keys. A system based on elliptic curve asymmetric cryptography for Bitcoin Cash
5. Technical understanding of BIP-39
6. Technical understanding of SLIP-39
7. Technical understanding of BIP-32 and BIP-44

---

## Software
### SeedCash versions

| Version of SeedCash | Find File |
|----------------------|------|
| v1.1.0 | [seedcash_v1.1.0.img](https://seedcash.cash/resources) |

### Image Verification for SeedCash
SeedCash provides GPG-signed images to ensure the authenticity and security of each .img file. 
You can download the latest image [here](https://seedcash.cash/resources)

# The following commands guide you through verifying the downloaded image on Mac/Linux and Windows.

# -------------------------------
# MAC / LINUX
# -------------------------------

# Open a terminal in the directory containing the downloaded folder.

# Import SeedCash public key
gpg --fetch-keys https://keybase.io/seedcash/pgp_keys.asc

# Verify SeedCash public key fingerprint
gpg --fingerprint

# Verify compatibility between the downloaded image and its signature
gpg --verify seedcash_v.1.1.0.img.sig seedcash_v.1.1.0.img

# -------------------------------
# WINDOWS
# -------------------------------

# Open a terminal in the directory containing the downloaded folder.

# Import SeedCash public key
gpg --fetch-keys https://keybase.io/seedcash/pgp_keys.asc

# Verify SeedCash public key fingerprint
gpg --fingerprint

# Verify compatibility between the downloaded image and its signature
gpg --verify seedcash_v.1.1.0.img.sig seedcash_v.1.1.0.img



---

## Contact & Community
- **Telegram**: [SeedCash Telegram](https://t.me/+tdY1ioshyPZkOGFk)  
- **Twitter**: [@seedcash_](https://twitter.com/seedcash_)  
- **Website**: [seedcash.cash](https://seedcash.cash)

---

© 2025 SeedCash. All rights reserved.  
*"In code we trust"*
