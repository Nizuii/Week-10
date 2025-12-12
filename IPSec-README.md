# What is IPSec

- **Internet Protocol Security (IPSec)** refers to a collection of communication protocols used to establish secure network connections.
- **IP (Internet Protocol)** is the common standard that controls how data is transmitted across the internet. IPSec enhances the protocol security by introducing encryption & authentication.
- **IPSec** encrypts the data at the source and decrypts it at the destination. It also verifies the source of the data.
- It also verifies the ource of the data.

## Importance of IPSec

- **IPSec** is important because it helps keeps the data safe and secure when you send it over the internet or any network.

  - **IPSec** protects the data through data encryption.
  - IPSec provides data integrity.
  - IPSec is often used in **Virtual Private Networks (VPN)** to create secure, private connections.
 
## Features of IPSEC

- **Authentication**: IPSec provides authentication of IP packets using digital signatures or shared secrets. This helps ensures that the packets are not tampered with or forged.
- **Confidentiality**: IPSec provides confidentiality by encrypting IP packets, preventing eavesdropping on the network traffic.
- **Integrity**: IPSec provides integrity by ensuring that IP packets have not been modified or corrupted during transmission.

## IPSec building blocks.

IPSec isn't one protocol. Its a collection of protocols working together.

### 1. AH (Authentication Header)

- It provides authentiction, integrity, anti-replay.
- But it does not provide encryption.
- This is rarely used today because it only needs authenticity, not secrecy.

### 2. ESP (Encapsulating Security Protocol)

- This is a core protocol of IPSec.
- It provides encryption, authentiction, integrity, aniti-replay.
- It is used in almost all IPSec VPN's.

## Modes of Operation

- IPSec can work in 2 modes.

- 
