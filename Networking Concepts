# 📘 CompTIA Network+ (N10-007) — Full Study Notes

These are extended personal study notes covering all Network+ exam domains.  
The notes combine theoretical summaries, key terminology, and practical references useful for SOC and network troubleshooting work.

---

## 🧩 Domain 1.0 — Networking Concepts

### 1.1 Explain the purposes and uses of ports and protocols
- **HTTP (80)** – web traffic (unencrypted)
- **HTTPS (443)** – secure web traffic
- **FTP (20,21)** – file transfer
- **SSH (22)** – secure remote access
- **DNS (53)** – domain name resolution (UDP/TCP)
- **DHCP (67,68)** – dynamic IP addressing
- **SNMP (161,162)** – device monitoring
- **SMTP (25)** – sending email
- **POP3 (110)**, **IMAP (143)** – receiving email
- **RDP (3389)** – remote desktop
- **NTP (123)** – network time sync

**Key concept:** protocols = communication rules between devices.  
Understanding their purpose helps determine which layer of the OSI model they operate on.

---

### 1.2 Compare OSI and TCP/IP Models
| OSI Layer | Function | Example Protocols |
|------------|-----------|------------------|
| 7. Application | User interface | HTTP, DNS, SMTP |
| 6. Presentation | Data translation/encryption | TLS, SSL |
| 5. Session | Manages sessions | NetBIOS, RPC |
| 4. Transport | Segmentation, reliability | TCP, UDP |
| 3. Network | Logical addressing | IP, ICMP |
| 2. Data Link | MAC addressing | Ethernet, PPP |
| 1. Physical | Transmission medium | Cables, hubs |

**Mnemonic:**  
> "Please Do Not Throw Sausage Pizza Away"

---

### 1.3 Explain common networking topologies and types
- **Star** – most common; devices connect via central switch.
- **Bus** – legacy topology using one shared cable.
- **Ring** – data travels in one direction; token ring.
- **Mesh** – redundant links between all nodes.
- **Hybrid** – combination of topologies.

**Network types:**
- **LAN** – local area network.
- **WAN** – wide area (ISP connections).
- **MAN** – metropolitan area.
- **PAN** – Bluetooth, personal area.
- **CAN** – campus area.

---

### 1.4 Configure and apply IP addressing schemes
- **IPv4:** 32-bit addresses, e.g., `192.168.1.10`
- **Subnet Mask:** defines network and host parts.
- **CIDR Notation:** `/24` = 255.255.255.0
- **Private Ranges:**  
  - 10.0.0.0/8  
  - 172.16.0.0/12  
  - 192.168.0.0/16

- **IPv6:** 128-bit, e.g., `2001:0db8::1`
- **Link-local:** `fe80::/10`

**Common Tools:** `ping`, `ipconfig`, `ifconfig`, `tracert`, `nslookup`, `arp -a`

---

## 🧠 Domain 2.0 — Infrastructure

### 2.1 Cabling and Connectors
| Cable | Max Distance | Speed | Connector |
|--------|---------------|--------|------------|
| Cat5e | 100m | 1 Gbps | RJ45 |
| Cat6 | 100m | 10 Gbps (short runs) | RJ45 |
| Cat6a | 100m | 10 Gbps | RJ45 |
| Fiber (SM/MM) | km-range | up to 100 Gbps | LC/SC/ST |

**Tools:** Cable tester, TDR, tone generator, loopback plug.

---

### 2.2 Networking Devices
- **Router:** Layer 3 device for inter-network communication.
- **Switch:** Layer 2 (sometimes 3) device for LAN segmentation.
- **Firewall:** traffic filtering by rules.
- **Access Point:** wireless bridge for clients.
- **Proxy:** mediates requests, adds caching and filtering.
- **Load Balancer:** distributes traffic among servers.

---

## 🧰 Domain 3.0 — Network Operations

### 3.1 Monitoring and Documentation
- **Logs:** firewall, IDS/IPS, DHCP, system events.
- **Performance Metrics:** CPU, memory, latency, packet loss.
- **Documentation Types:**
  - Network diagrams
  - Change management records
  - Asset inventory

### 3.2 Business Continuity
- **Redundancy:** dual power, RAID, failover.
- **High Availability:** clustering, load balancing.
- **Disaster Recovery:** backups, hot/warm/cold sites.

---

## 🔒 Domain 4.0 — Network Security

### 4.1 Security Concepts
- **CIA Triad:** Confidentiality, Integrity, Availability.
- **Authentication / Authorization / Accounting (AAA).**
- **Least Privilege Principle.**
- **Defense in Depth.**

### 4.2 Common Attacks
- **Phishing, Spear Phishing, Whaling**
- **DDoS / DoS**
- **MITM (Man-in-the-Middle)**
- **Spoofing / ARP poisoning**
- **Social Engineering**
- **Rogue AP, Evil Twin**

### 4.3 Mitigation
- **Firewall & ACLs**
- **IDS/IPS systems**
- **Patch management**
- **Antivirus / EDR**
- **Security Awareness Training**

---

## 🧩 Domain 5.0 — Troubleshooting and Tools

### 5.1 Command Line Tools
| Command | Purpose |
|----------|----------|
| `ping` | Check connectivity |
| `tracert` | Route path |
| `ipconfig /all` | View adapter info |
| `nslookup` | DNS lookup |
| `netstat` | View connections |
| `arp -a` | View MAC table |
| `nmap` | Network scan |
| `wireshark` | Packet capture |

### 5.2 Troubleshooting Methodology
1. Identify the problem  
2. Establish a theory  
3. Test the theory  
4. Establish a plan  
5. Implement solution  
6. Verify full system functionality  
7. Document findings

---

## 📚 Key Abbreviations & Terms
- **MAC** — Media Access Control  
- **ARP** — Address Resolution Protocol  
- **DHCP** — Dynamic Host Configuration Protocol  
- **DNS** — Domain Name System  
- **NAT** — Network Address Translation  
- **VPN** — Virtual Private Network  
- **QoS** — Quality of Service  
- **PoE** — Power over Ethernet  
- **VLAN** — Virtual LAN  
- **SSID** — Service Set Identifier  

---

## 🎯 Summary

These notes cover ~80% of core Network+ (N10-007) exam content.  
They are formatted to serve both as **study reference** and **SOC analyst refresher sheet**.  
Use together with practice labs, Wireshark analysis, and subnetting exercises.

---

**Author:** Ievgen Bondarenko  
**Repository:** [NetworkPlus-007-Notes](https://github.com/ibondarenko1/NetworkPlus-007-Notes)
