# 🏦 Enterprise Bank Network Infrastructure

## 📌 Project Overview

This project demonstrates the design and implementation of a complete **Enterprise Bank Network Infrastructure** using **Cisco Packet Tracer**.

The network was designed based on Cisco's **Hierarchical Network Design Model** to simulate a real-world enterprise banking environment. It provides secure communication between multiple departments through network segmentation, dynamic routing, centralized services, wireless connectivity, and network security mechanisms.

The project focuses on implementing enterprise networking concepts while ensuring scalability, security, and efficient network management.

---

# 🎯 Project Objectives

* Design a scalable enterprise network.
* Implement the Hierarchical Network Design Model.
* Create separate VLANs for each department.
* Configure Inter-VLAN Routing using Layer 3 Switches.
* Implement Dynamic Routing using OSPF.
* Configure a Dedicated DHCP Server for automatic IP address allocation.
* Configure a DNS Server for hostname resolution.
* Deploy HTTP and Email Servers.
* Configure Secure Remote Access using SSH.
* Secure switch ports using Port Security.
* Provide wireless connectivity for every department.
* Verify full network communication between all devices.

---

# 🏢 Departments

* Management
* Research
* Human Resources
* Marketing
* Accounts
* Finance
* Logistics
* Customer Service
* Guest Network
* Administration
* ICT Department
* Server Room

Each department is assigned to a separate VLAN and subnet to improve network performance and security.

---

# 🏗 Network Design

The network follows Cisco's Hierarchical Network Design consisting of:

### Core Layer

* High-speed routing
* OSPF backbone connectivity
* Communication between distribution devices

### Distribution Layer

* Layer 3 Switches
* Inter-VLAN Routing using SVIs
* Default Gateway for every VLAN
* Route advertisement

### Access Layer

* Access Switches
* PCs
* Laptops
* Network Printers
* Wireless Access Points

---

# 🌐 Technologies Implemented

* Cisco Packet Tracer
* Hierarchical Network Design
* VLAN Configuration
* Inter-VLAN Routing (SVI)
* Layer 3 Switching
* OSPF Dynamic Routing
* Dedicated DHCP Server
* DNS Server
* HTTP Server
* Email Server
* SSH Remote Access
* Wireless LAN (WLAN)
* Port Security (Sticky MAC)
* IP Addressing and Subnetting
* Network Verification and Troubleshooting

---

# 🌐 IP Addressing

* Base Network: **192.168.10.0**
* Subnetting performed according to the number of hosts required for each department.
* Every department has:

  * Separate Subnet
  * Dedicated VLAN
  * Default Gateway
  * DHCP Scope

---

# 🔄 Routing

Dynamic routing is implemented using **OSPF (Open Shortest Path First)**.

Features include:

* Automatic Route Advertisement
* Fast Convergence
* Scalable Routing
* Neighbor Discovery
* Dynamic Routing Table Updates

---

# 📥 DHCP

A centralized DHCP Server located in the Server Room provides automatic IP address allocation for all departments.

Each VLAN has its own DHCP Pool configured with:

* IP Address
* Subnet Mask
* Default Gateway
* DNS Server

---

# 🌍 DNS

A dedicated DNS Server is configured to provide hostname resolution for all network devices and enterprise services.

---

# 🌐 Enterprise Servers

The Server Room hosts:

* DHCP Server
* DNS Server
* HTTP Server
* Email Server

These services simulate a real enterprise environment.

---

# 📡 Wireless Network

Every department includes a Wireless Access Point that allows wireless users to connect securely while remaining members of their assigned VLAN.

---

# 🔒 Security Features

The project includes several security mechanisms:

* SSH Version 2
* Local User Authentication
* Password Encryption
* Console Password
* Enable Secret Password
* Banner Message
* Disable DNS Lookup
* Port Security
* Sticky MAC Address Learning
* Shutdown Violation Mode

---

# 🧪 Network Testing

The network was successfully verified by performing:

* Dynamic IP Address Allocation
* Inter-VLAN Communication
* OSPF Neighbor Verification
* Routing Table Verification
* DNS Name Resolution
* HTTP Server Accessibility
* Email Communication
* Wireless Connectivity
* SSH Remote Login
* Port Security Verification
* End-to-End Ping Tests

All tests were completed successfully.

---

# 💡 Skills Demonstrated

This project demonstrates practical experience in:

* Enterprise Network Design
* Cisco Routing & Switching
* Layer 3 Switching
* Dynamic Routing (OSPF)
* VLAN Segmentation
* Network Security
* DHCP & DNS Services
* Wireless Networking
* Cisco IOS Configuration
* Network Troubleshooting

---

# 📂 Repository Contents

* Enterprise Bank Network (.pkt)
* Project Documentation
* Network Configuration Files
* Verification Outputs

---

# 🚀 Future Improvements

* Access Control Lists (ACLs)
* HSRP for Gateway Redundancy
* EtherChannel
* IPv6 Implementation
* Network Monitoring (SNMP)
* Syslog Server
* NTP Server

---

# 👩‍💻 Author

**Nermin**

IT Specialist | Network Administration | Cisco Networking

---

## ⭐ Project Summary

This project simulates a complete enterprise bank network by integrating routing, switching, wireless networking, centralized services, and security mechanisms into a scalable and secure infrastructure. It reflects practical implementation of CCNA-level networking concepts in a real-world enterprise scenario.
