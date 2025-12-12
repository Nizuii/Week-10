# What is IDS/IPS

- **Intrusion Detection System** & **Intrusion Prevention System** are 2 critical network security tools used to protect systems & networks from cyber threats.
- While they both aim to safeguard against cyber attacks, they differ in how they operate and the actions they take.

## IDS (Intrusion Detection System)

- **IDS** is a hardware or software tool that monitors and analyzes network or system activities for sign of unauthorized access or policy violations.
- It passively scans incomming traffic and compares it to pre-configured  or behavioral patterns.
- **IDS** alerts the system admin when potential threaths are detected but does not take any active action to block or mitigate them. 

**Example**:  
IDS detects an unusual spike in network traffic during off-peak hours and sends an alert to the administrator, notifying them of a possible security breach.

### IDS Rules

IDS Rules are a set of instructions that tells the IDS:

- **What to look for** (Patterns, Strings, Behaviour, Protocol Anomalies)
- **Where to look** (IP, Port, Protocol)
- **What to do** if it finds a match (alert, log, block ➡️ IPS)

### Deployment Types

1️⃣ **NIDS - Network IDS**

Monitors network segments.

2️⃣ **HIDS – Host IDS**

Runs on individual machines (Servers, End-points)

### IDS Tools

- Snort
- Suricata
- OSSEC

## IPS (Intrusion Prevention System)

- **IPS** is an advanced security system that not only detects malicious activities buto also prevents them from happening in real time.
- It interprets network traffic, compares it to known threat signatures, and immediatly blocks and neutralizes suspicious activities before they can cause damage.
- **IPS** is proactive while **IDS** is primarily reactive.

**Example**:
IPS detects a malicious payload based on its signature and immediatly blocks the traffic, preventing the malware to enter the network.
