- **Secure Socket Layer (SSL)** & **Transport Layer Security** are both protocols used to provide security between web browsers and web servers.
- **SSL** is older (now considered as insecure and deprectaed).
- **TLS** is new improved and what we actually used today.
- In **SSL/TLS** when a client browser connects to a secure website, both sides needs to generate the same encryption keyswithout sending those directly over the network.

  - They do this through:
 
    1. Exchanging some random values.
    1. Running those values through a function to produce the master secret.
    1. Using the master secret to derive the actual encryption keys.
   
## SSL vs TLS (How the Master Secret is created)

### SSL (Older)

- Uses **Message Digest Algorithm** (like MD5+SHA-1) to generate the master secret.
- These algorithms are not very strong by modern standards.
- SSL provides **authentication + confidentiality** but its outdated.

in SSL:

> master_secret = MD5(...) + SHA1(...)
