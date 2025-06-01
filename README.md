

# 🌐 Computer Networking Project – Corporate Campus Network Simulation

## 🔖 Project Title

**Data Communication in a Network – Corporate Campus Expansion**

---

## 📄 Project Overview

This project simulates a scalable network infrastructure for a large corporate campus comprising **five major buildings**:

* Headquarters
* Sales Office
* Tech Center
* Human Resources
* Finance Division

Each building is equipped with:

* A **dedicated router**
* A **DHCP server** for dynamic IP assignment
* **Three client PCs**

The network is built using **Class A IP addressing**, and routers are interconnected using the **OSPF (Open Shortest Path First)** protocol for dynamic routing.

The **Headquarters** hosts:

* A **DNS Server** to resolve `www.campusnet.com`
* A **Web Server** accessible from all other buildings

Simulated browser-based applications are included to demonstrate business processes like:

* Employee onboarding
* Asset management
* Invoice processing

---

## ⚙️ Features and Configuration

### ✅ Network Design Includes:

* Subnetting and IP addressing plan
* Router configurations for each building
* DHCP server setups
* OSPF routing across all routers
* DNS and Web Server setup at Headquarters

### 🧪 Experimental Results:

* LAN-to-LAN communication tested using ICMP ping
* Verified browser-based access to `www.campusnet.com` from all PCs
* Successful packet delivery with 0% packet loss

---

## 🧰 Technologies Used

* Cisco Packet Tracer
* OSPF Protocol
* DNS & Web Server configuration
* DHCP implementation
* Network simulation tools

---

## 📁 Project Structure

```
📦 CampusNetworkSimulation
├── 2022-1-60-372.pdf         # Final project report
├── question.pdf              # Project question and requirements
├── campus_network.pkt        # Cisco Packet Tracer simulation file
└── README.md                 # Project description and documentation
```

> **Note:** Open the `.pkt` file using **Cisco Packet Tracer** to view and interact with the full network simulation.

---

## 🏁 Conclusion

This project successfully demonstrates a robust and scalable campus network setup. The simulation confirms full connectivity, dynamic routing, and domain resolution. All business goals were met effectively, showcasing the ability to design, implement, and test a functional enterprise-level network.


