![Screenshot 2024-11-20 143905](https://github.com/user-attachments/assets/771aa91a-d783-40ef-9836-c3c438946ae1)

# University Campus Network Configuration

## Main Campus
- **Building A**: 
  - Houses administrative staff from the departments of management, HR, and finance. 
  - PCs are distributed in office spaces and share networking equipment (VLANs are implemented here).
  - The **Faculty of Business** is also located in this building.

- **Building B**: 
  - Houses the **Faculty of Engineering and Computing** and the **Faculty of Art and Design**.

- **Building C**: 
  - Contains student labs and the IT department.
  - The IT department hosts the **University Web Server** and other servers.
  - An email server is hosted externally on the cloud.

## Smaller Campus
- **Faculty of Health and Sciences**: 
  - Staff and student labs are located on separate floors.

## Network Requirements
1. Each department/faculty is assigned its own **separate IP network**.
2. **VLANs** are created and configured on switches for segmentation and security.
3. **RIPv2** is used for routing within the internal network, while static routing is configured for external servers.
4. Devices in **Building A** acquire dynamic IP addresses via a **router-based DHCP server**.
5. The entire network is configured using **Cisco Packet Tracer** to achieve the specified connectivity and functionalities.

---

## Technologies Implemented
- **Network Topology Design** using Cisco Packet Tracer.
- **Hierarchical Network Design** principles.
- **Connecting Networking Devices** with appropriate cabling.
- **Creating VLANs** and assigning ports VLAN numbers.
- **Subnetting and IP Addressing** for optimal network performance.
- **Inter-VLAN Routing** using a router-on-a-stick configuration.
- Configuring a **DHCP Server** (router-based).
- Configuring **SSH** for secure remote access.
- Implementing **RIPv2** as the dynamic routing protocol.
- Enforcing **Switchport Security (Port-Security)** on switches.
- Configuring **Host Devices** for network communication.
- **Testing and Verifying** network communication to ensure functionality.

---

## Network Topology Created
The network topology adheres to all user requirements, and its functionality has been verified and tested successfully. 

### Preview:
The network diagram and setup in Cisco Packet Tracer demonstrate the following:
1. VLAN segmentation for departmental security and traffic management.
2. DHCP server functionality for dynamic IP assignment.
3. Proper routing between VLANs using RIPv2.
4. Secure and efficient connectivity between devices across the network.
