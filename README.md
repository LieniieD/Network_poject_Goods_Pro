# Network_poject_Goods_Pro

# Branch Office Network

## 📖 Project Description
This project focuses on designing, implementing, and enhancing the branch office network infrastructure. Using **Cisco** technologies, we aim to build a **stable, secure, and efficient** network.

⚠️ **This project is ongoing!**  
Configurations are still being fine-tuned, and we are planning **future scalability and enhancements** to optimize network performance and security.

## 🎯 Key Objectives:
- 🔍 Business requirements analysis and technical assessment.
- 🏗 Network design and deployment.
- 🔐 Security and redundancy implementation.
- 🤖 Automation and troubleshooting improvements.
- 📊 Documentation and presentation of the solution.

---

## 🛠 Technologies & Equipment

### 🔹 **Network Topology**
- **Model:** Hub-and-Spoke with redundant links.
- **Architecture:** Spine & Leaf, Enterprise Branch Module.
- **Resilience:** Dual ISP Failover, HSRP.

### 🔹 **Equipment**
| Category | Device | Quantity | Approx. Cost |
|----------|--------|----------|--------------|
| Routers | Cisco ISR 1100 | 2 | ~€1800 |
| L3 Switches | Cisco Catalyst 2960-X | 2 | ~€3000 |
| L2 Switches | Cisco Catalyst 9200L (48-port, PoE) | 2 | ~€2200 |
| Firewall | Cisco Firepower 1010 | 2 | ~€1600 |
| Wi-Fi Controller | Cisco 3504 | 1 | ~€550 |
| Access Points | Cisco Aironet 1815i | 10 | ~€300 |
| UPS | 1000W-3000W | 1 | ~€600 |
| Servers | Windows Enterprise, Linux | - | ~€5000 |

---

## 📌 **IP Addressing & VLANs**
| VLAN | Department | IP Address |
|------|-----------|------------|
| 10 | HR | 172.26.10.0/24 |
| 20 | Finance | 172.26.20.0/24 |
| 30 | Sales | 172.26.30.0/24 |
| 40 | Marketing | 172.26.40.0/24 |
| 50 | CEO/Admin | 172.26.50.0/24 |
| 60 | Wi-Fi | 172.26.60.0/24 |
| 70 | Printers | 172.26.70.0/28 |
| 90 | VoIP | 172.26.90.0/24 |
| 111 | Servers | 172.26.111.0/27 |
| 222 | IT | 172.26.222.0/27 |

---

## 📡 **Protocols & Services**
- **Routing:** OSPF, BGP, NAT.
- **Security:** ACL, IPSec VPN, Firewall.
- **Redundancy:** HSRP, EtherChannel, Dual ISP Failover.
- **Traffic Management:** QoS, Inter-VLAN Routing.
- **Monitoring:** SNMP, Syslog, NetFlow.
- **Authentication:** RADIUS, TACACS+.

---

## 🏆 **Key Features**
✅ **Redundancy**: Dual ISP + HSRP ensure failover protection.  
✅ **Security**: **ACLs, Firewalls, VPN** for enhanced data protection.  
✅ **Segmentation**: VLANs for department isolation.  
✅ **Automation**: DHCP, SNMP, Syslog for network management.  
✅ **Monitoring**: Logging, NetFlow, SNMP.  

---

## 🚀 **Deployment & Testing**
1. **Equipment Setup** according to the network topology.
2. **Routing Configuration** (OSPF, BGP).
3. **Security & Access Control** (ACLs, IPSec VPN).
4. **Monitoring & Debugging** (SNMP, Syslog).
5. **Failure Testing** to validate redundancy mechanisms.

---

## 🔮 **Future Plans**
🚀 **This project is not finished yet!**  
- 🔧 Ongoing **configuration improvements**.  
- 📈 **Planned scalability** to support growing business needs.  
- 🔒 **Security enhancements** for better protection.  

---

## 📝 **Author**
📌 **Lieniie Dzhelianchyk**  
📅 **Date:** 17.12.2024  
📄 **Version:** 1.0  

🔗 [Project Documentation](./Goods_pro.pdf)  

---

## 📌 **License**
This project is distributed under the **MIT License**.  
For details, see [LICENSE](./LICENSE).

