# 🖧 Exam Online System - Computer Networking Project

## 📋 Project Overview
A VLAN-based network simulation built in Cisco Packet Tracer 
featuring Inter-VLAN Routing, DNS, HTTP, and FTP services.

## 🏗️ Network Topology
- **Router1** – Inter-VLAN Routing (Router-on-a-Stick)
- **Switch0** – VLAN Segmentation
- **Server0** – HTTP & DNS Server
- **Server1** – FTP Server
- **5 PCs** – Admin Block & Students Lab

## 🔀 VLAN Configuration
| VLAN | Name | Subnet | Devices |
|------|------|--------|---------|
| 10 | Admin | 192.168.10.0/24 | PC0, PC1 |
| 20 | Students | 192.168.20.0/24 | PC2, PC3, PC4 |
| 30 | Server | 192.168.30.0/24 | Server0, Server1 |

## ⚙️ Services Configured
- ✅ HTTP Server (labexam.com)
- ✅ DNS Server (labexam.com → 192.168.30.2)
- ✅ FTP Server (192.168.30.3)
- ✅ Inter-VLAN Routing via RIP

## 🛠️ Tools Used
- Cisco Packet Tracer 8.x

## 👨‍💻 Author
**Asif Ali** – Roll No. 290 and **Asif Ali** - Roll No. 289
