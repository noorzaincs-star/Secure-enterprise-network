# Secure Enterprise Network with Site-to-Site VPN, ACLs and Firewall Policies

A multi-site enterprise network design that connects branch offices to a head office over a secure WAN. The project focuses on encrypted site-to-site connectivity and controlled access between departments.

## Features
- Multi-site topology: branch offices connected to a head office over a WAN
- Site-to-site **IPsec VPN** tunnel to encrypt traffic between remote sites
- **Standard and extended ACLs** to restrict traffic between departments and protect critical resources
- **Firewall policies** to filter inbound and outbound traffic
- IP addressing and **subnetting** plan (IPv4)
- Routing and switching configuration, tested end to end

## Tools Used
- [Cisco Packet Tracer / GNS3 / other tool you used]
- Cisco IOS (CLI)

## Network Topology
![Network Topology](images/topology.png)

## How to Run
1. Download or clone this repository.
2. Open the `[project-file-name].pkt` file in [Cisco Packet Tracer].
3. Use the configuration files in the `configs/` folder to review the device settings.
4. Test connectivity between sites (ping) and verify the VPN tunnel and ACL behavior.

## Folder Structure
- `images/`: topology diagram and screenshots
- `configs/`: router and switch configurations
- `[project-file-name].pkt`: simulation file

## What I Learned
- Designing and planning a multi-site network
- Configuring IPsec site-to-site VPNs
- Writing and applying ACLs and firewall rules
- Subnetting, routing and switching
- Testing and troubleshooting network connectivity

## Author
**Noorzan Ullah**
Computer Science graduate | CCNA trained | Cisco Networking
LinkedIn: https://www.linkedin.com/in/noorzan-ullah-092075374
