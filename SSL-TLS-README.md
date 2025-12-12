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

```bash
master_secret = MD5(...) + SHA1(...)
```

Message Digest algorithms = simple hashing methods.

### TLS (Latest)

- Uses a **Pseudo Random Function** (PRF) to generate the master secret.
- **PRF** = **MD5 + SHA1** Combined in a stronger way, and in later versions TLS uses only SHA-256 or better.
- Much stronger and more resistant to attacks.

in TLS:
```bash
master_secret = PRF(client_random, server_random, pre_master_secret)
```

PRF = more secure, more modern, more unpredictable.
