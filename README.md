# Design and Implementation of a Multi Building Campus Network - using Cisco Packet Tracer

![Cisco Packet Tracer](https://img.shields.io/badge/Cisco%20Packet%20Tracer-7.3.1-brightgreen)
![CCNA Level](https://img.shields.io/badge/Skill%20Level-CCNA-blue)
![Network Design](https://img.shields.io/badge/Type-Campus%20Network-orange)

A complete **three-tier hierarchical Campus Area Network (CAN)** designed and implemented in Cisco Packet Tracer for a university/educational institution.

---

## 📋 Project Overview

This project demonstrates the design and configuration of a scalable, secure, and redundant campus network supporting multiple faculties, administration, hostels, and a server farm.

The network follows the **Cisco Three-Tier Hierarchical Model** (Access → Distribution → Core) and includes VLAN segmentation, inter-VLAN routing, DHCP, dynamic routing, NAT, and basic security features.

**Ideal for CCNA, Network Engineering, and IT portfolio showcase.**

---

## ✨ Key Features

- **Hierarchical Network Design** (Access, Distribution, Core)
- **VLAN Segmentation** for different departments
- **Inter-VLAN Routing** using Multilayer Switches
- **Dynamic IP Assignment** via DHCP Server
- **OSPF** Dynamic Routing between buildings
- **NAT/PAT** for Internet connectivity
- **Redundancy** with multiple links and STP/RSTP
- **Basic Security** (SSH, Password Encryption, Port Security)
- **Wireless LAN** support (optional)
- End-to-end connectivity testing

---

## 🖼️ Network Topology

The campus consists of the following buildings/blocks:

- **Administration Building**
- **Engineering Faculty**
- **Arts & Science Faculty**
- **Library & IT Center**
- **Student Hostels**
- **Server Farm / Data Center**
- **Core & Border Routers**

**Topology Type**: Three-Tier Hierarchical Design with redundant fiber links between layers.

![App Screenshot](https://raw.githubusercontent.com/sarowarhosen01/Design-and-Implementation-of-a-Multi-Building-Campus-Network-/refs/heads/main/Screenshots/Screenshot_100.jpg)


---

## 📌 IP Addressing Scheme

| VLAN | Department / Purpose     | Network Address     | Subnet Mask       | Default Gateway   |
|------|--------------------------|---------------------|-------------------|-------------------|
| 10   | Administration           | 192.168.10.0/24     | 255.255.255.0     | 192.168.10.1      |
| 20   | Engineering Faculty      | 192.168.20.0/24     | 255.255.255.0     | 192.168.20.1      |
| 30   | Arts & Science           | 192.168.30.0/24     | 255.255.255.0     | 192.168.30.1      |
| 40   | Students / Hostels       | 192.168.40.0/24     | 255.255.255.0     | 192.168.40.1      |
| 50   | Server Farm              | 192.168.50.0/24     | 255.255.255.0     | 192.168.50.1      |
| 99   | Management / Native      | 192.168.99.0/24     | 255.255.255.0     | 192.168.99.1      |

**DHCP Pool**: Configured for dynamic IP allocation to end devices.


---

## 🛠️ Technologies & Protocols Used

- **Switching**: VLANs, Trunking (802.1Q), Port Security, STP/RSTP
- **Routing**: OSPF, Static Routing, Default Routing
- **IP Services**: DHCP, NAT/PAT, DNS
- **Security**: SSH, Enable Secret, Password Encryption, ACLs
- **Wireless**: Access Points (optional)
- **Tools**: Cisco Packet Tracer

---

## 📂 Project Files

Campus-Network-Project/  
├── Campus_Network.pkt  
├── README.md  
├── Configurations/  
│   ├── Routers/  
│   │   └── R1-Core.txt      
│   ├── Switches/  
│   │   ├── SW1-Configuration.txt  
│   │   ├── SW2-Configuration.txt  
│   │   └── SW3-Configuration.txt  
│   └── Servers/  
│       └── DHCP-Server.txt  
├── Screenshots/   
│   ├── topology-overview.jpg   
└── Documentation/   


- `Campus_Network.pkt` → Main Packet Tracer file
- `Screenshots/` → Topology, configurations, and test results

---

## 🚀 How to Use

1. Download the repository.
2. Open `Campus_Network.pkt` using **Cisco Packet Tracer** (version 7.3 or above recommended).
3. Explore different devices (switches, routers, servers).
4. Test connectivity using **Ping**, **Web Browser**, or **PDU Tool**.

---

## 📸 Screenshots

![App Screenshot](https://raw.githubusercontent.com/sarowarhosen01/Design-and-Implementation-of-a-Multi-Building-Campus-Network-/refs/heads/main/Screenshots/Screenshot_100.jpg)

- Overall Network Topology
- VLAN Configuration
- OSPF Neighbor Table
- DHCP Binding Table
- Successful Inter-VLAN & Internet Connectivity Tests

---

## 📌 Skills Demonstrated

- Hierarchical Network Design
- Advanced Switching & Routing
- IP Addressing & Subnetting
- VLAN and Inter-VLAN Routing
- Routing Protocol Configuration (OSPF)
- Network Services (DHCP, NAT)
- Basic Network Security
- Troubleshooting & Documentation

---

## 🔮 Future Enhancements

- Implement VoIP (IP Phones + Call Manager)
- Add IPv6 addressing
- Advanced Security (AAA, VPN, Firewall)
- Wireless Controller (WLC)
- Monitoring using SNMP or Syslog
- High Availability (HSRP/GLBP)

---

## 👨‍💻 Author

**SAROWAR**  
Network Engineering  
Location: Dhaka, Bangladesh

---

## 📄 License

This project is open for educational purposes. Feel free to use and modify it for learning.

---

**Star ⭐ this repository if you found it helpful!**
