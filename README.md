![Screenshot 2024-11-20 143905](https://github.com/user-attachments/assets/771aa91a-d783-40ef-9836-c3c438946ae1)


https://github.com/user-attachments/assets/ed17000a-1278-475b-a565-27f747e28414


# University Network Topology Configuration

This project involves designing a network topology for a large university with two campuses situated 20 miles apart. The university serves students and staff across four faculties: **Health and Sciences**, **Business**, **Engineering/Computing**, and **Art/Design**. Each staff member has a dedicated PC, while students access PCs in designated labs.

---

## **University Location and Network Layout**

### **Main Campus**
1. **Building A**:
   - Administrative staff in **management**, **HR**, and **finance** departments. PCs for administrative staff are distributed across offices and share networking equipment (**VLANs implemented** here).
   - Houses the **Faculty of Business**.

2. **Building B**:
   - Home to the **Faculty of Engineering and Computing** and the **Faculty of Art and Design**.

3. **Building C**:
   - Contains **student labs** and the **IT department**.
   - The IT department hosts the **University Web Server** and other on-premises servers.
   - An **email server** is hosted externally on the cloud.

### **Smaller Campus**
- Dedicated to the **Faculty of Health and Sciences**, with:
  - Staff offices and student labs located on separate floors.

---

## **Network Requirements**
- Each **faculty/department** operates on its own **separate IP network**.
- Switches are configured with **VLANs** and **security settings** for traffic segmentation.
- **RIPv2** is implemented to route traffic within the internal network.
- **Static routing** is used for external server connectivity.
- Devices in **Building A** are configured to acquire **dynamic IP addresses** from a **router-based DHCP server**.
- The network is built and configured in **Cisco Packet Tracer**.

---

## **Technologies Implemented**
- **Network Topology Design** using Cisco Packet Tracer.
- **Hierarchical Network Design** principles.
- Proper **cabling and device connectivity**.
- **VLAN Configuration** and assigning ports to VLANs.
- **Subnetting and IP Addressing** to optimize network performance.
- **Inter-VLAN Routing** using the **router-on-a-stick** method.
- **DHCP Server Configuration** (router as DHCP server).
- **SSH Configuration** for secure remote access to network devices.
- **RIPv2 Configuration** as the dynamic routing protocol.
- **Switchport Security** for enhanced port-level protection.
- **Host Device Configurations** (PCs, servers, etc.).
- **Testing and Verifying Network Communication** to ensure functionality.

---

## **Network Design Summary**
The designed network topology meets all the specified requirements:
1. **Faculty and department-level segmentation** using VLANs.
2. Dynamic IP address allocation for devices in **Building A**.
3. Secure communication through **SSH**.
4. Routing within the network handled by **RIPv2**.
5. Reliable connectivity to external servers using **static routes**.

---

## **Deliverables**
- **Network Topology**: The network has been designed, verified, and tested successfully in **Cisco Packet Tracer**.
- **Source File**: Access the Packet Tracer file for the complete network configuration.
- **Demo Video**: Watch a step-by-step walkthrough of the setup.
