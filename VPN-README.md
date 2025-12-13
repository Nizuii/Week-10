# What is a VPN

<img src="images/vpn1.jpg">

- **VPN** stands for virtual private network.
- It establishes a secure and reliable network connection over an unsecure network such as internet.
- It protects the internet activity and disguises the identity of the user on internet.

## Why VPN Exists

VPN solves 3 major problems:

### 1. Confidentiality.

- The data is encrypted.
- Hackers, ISP's, WiFi sniffers see's gibberish.

### 2. Privacy.

- Your real IP is hidden.
- Websites sees the VPN servers IP, not users.

### 3. Secure Remote Access

- Employees access companies internal network safely.
- Users can securely reach:

  - FileServers.
  - Internal apps
  - Databases
 
## What happens when we use a VPN

1. User connect to a VPN server
1. VPN Client + Server authenticate each other.
1. They agree on encryption keys.
1. A secure tunnel is created.
1. All traffic of the user goes through that tunnel.

So instead of:
```bash
User's PC ➡️ ISP ➡️ Website
```

It becomes:
```bash
User's PC ➡️ VPN Tunnel ➡️ VPN Server ➡️ Website
```

Return traffic comes back the same encrypted way.

## Types of VPN'S

### 1. Remote Access VPN's

- A Remote Access VPN permits a user to connect to a private network and aceess all its services and resources remotely.
- The connection between the user and the private occurs through the internet and the connection is secure and private.
- Remote Access VPN;s are useful for both home users and business users. A remotely working employee of a company uses this VPN to connect to his/her companies private network and remotely access the files and resources on the private network. 

### 2. Site to Site VPN

- A Site-to-Site VPN is also called as Router-to-Router VPN and is commonly used in the large companies.
- Companies or organizations, with branch offices in different locations, use Site-to-site VPN to connect the network of one office location to the network at another office location.

  - **Intranet based VPN**: When several offices of the same company are connected using Site-to-Site VPN type, it is called as Intranet based VPN.
  - **Extranet based VPN:** When companies use Site-to-site VPN type to connect to the office of another company, it is called as Extranet based VPN.
 
## Important VPN Protocols

- **Internet Protocol Security (IPSEC)**: Internet Protocol Security, known as IPSec, is used to secure Internet communication across an IP network. IPSec secures Internet Protocol communication by verifying the session and encrypts each data packet during the connection. IPSec runs in 2 modes:

  - Transport mode.
  - Tunneling mode.
 
- **Layer 2 Tunneling Protocol (L2TP)**: L2TP or Layer 2 Tunneling Protocol is a tunneling protocol that is often combined with another VPN security protocol like IPSec to establish a highly secure VPN connection. L2TP generates a tunnel between two L2TP connection points and IPSec protocol encrypts the data and maintains secure communication between the tunnel.

- **SSL and TLS**: SSL (Secure Sockets Layer) and TLS (Transport Layer Security) generate a VPN connection where the web browser acts as the client and user access is prohibited to specific applications instead of entire network. Online shopping websites commonly uses SSL and TLS protocol. It is easy to switch to SSL by web browsers and with almost no action required from the user as web browsers come integrated with SSL and TLS. SSL connections have "https" in the initial of the URL instead of "http".

- **OpenVPN**: An open-source VPN protocol that is highly configurable and secure, widely supported by VPN providers and considered one of the most secure VPN protocols.
