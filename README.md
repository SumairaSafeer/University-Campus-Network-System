# University Campus Network System

**Design and Simulation of a Secure Campus Network using Cisco Packet Tracer**

**Author:** Sumaira Safeer (FA22-BCE-019)  
**Course:** Computer Networks  
**Institution:** COMSATS University Islamabad, Attock Campus

---

## 📌 Project Overview

This mini-project presents the complete **design and simulation** of a secure campus network for a medium-sized university. The network supports five functional departments:
- **IT Department**
- **Accounts Department**
- **Registrar Department**
- **Faculty Department**
- **Student Department**

The design follows a **hierarchical structure** with VLAN segmentation, inter-VLAN routing, DHCP, and controlled external connectivity through an ISP.

---

## 🛠️ Key Features
- **VLAN Segmentation** — One VLAN per department for traffic isolation and security
- **Hierarchical Routing** — ISP Router → Border Router → Campus Router
- **DHCP** — Automatic IP assignment for large departments (Faculty & Students)
- **Static IP** — Manual addressing for IT, Accounts, and Registrar
- **External Connectivity** — Simulated Google and YouTube servers via ISP
- **Private Addressing** — `172.16.0.0/12` block with proper subnetting
- **Testing & Validation** — Ping tests + PDU simulation (same subnet & inter-VLAN)

---

## 📁 Repository Contents
| Folder            | Description                                      |
|-------------------|--------------------------------------------------|
| `Report/`         | Full project report (DOCX)                       |
| `Packet_Tracer/`  | Cisco Packet Tracer file (.pkt)                  |
| `Diagrams/`       | Network topology diagrams and screenshots        |

---

## 🚀 How to Run
1. Download the `.pkt` file from `Packet_Tracer/` folder
2. Open it in **Cisco Packet Tracer** (v8.0 or above recommended)
3. Explore the topology, VLAN configurations, router setups, and DHCP scopes
4. Run ping tests and switch to Simulation mode to trace PDUs

---

## 📊 Network Design Summary
- **Departments**: 5 (IT, Accounts, Registrar, Faculty, Students)
- **Buildings**: Administration Building + Academic Block
- **Addressing**: Private `172.16.0.0/12`
- **DHCP**: Faculty (250 devices) & Students (2000 devices)
- **External Servers**: Google + YouTube (simulated)

---

## ✅ Testing & Validation

The network was verified using:
- End-to-end **ping tests** between departments and external servers
- **PDU Simulation** (same VLAN and inter-VLAN routing)
- All tests passed successfully, confirming correct VLAN isolation and routing

---

## 📄 Report
Detailed documentation including methodology, device configurations, results, and discussion is available in the `Report/` folder.

---

   ## 👩‍🎓 Author
**Sumaira Safeer**  
Computer Engineer 
COMSATS University Islamabad, Attock Campus  
[LinkedIn](https://www.linkedin.com/in/sumaira-safeer-948804418/)

*This project demonstrates practical skills in campus network design, VLAN implementation, DHCP configuration, and hierarchical routing using industry-standard simulation tools.*
