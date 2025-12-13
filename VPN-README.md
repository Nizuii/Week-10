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
