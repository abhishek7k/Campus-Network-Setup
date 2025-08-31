# Cisco Campus Network with VLANs & Inter-VLAN Routing
📝 Project Overview
This project is a comprehensive simulation of a multi-VLAN campus network built using Cisco Packet Tracer. The primary goal was to design and configure a scalable and secure network infrastructure that segments traffic for different user groups (e.g., Students, Faculty, Servers) and provides essential network services.

This project demonstrates a solid understanding of fundamental networking principles that are critical for network management and cybersecurity. As an aspiring SOC Analyst and System Administrator, building this network was a practical exercise in creating the very environments I aim to protect and manage.

#Topology
(This is a placeholder. You should replace this text with a screenshot of your network diagram from Packet Tracer. A visual guide is extremely helpful!)

#✨ Key Features & Technologies
VLAN Segmentation:

The network is logically segmented into multiple VLANs to isolate broadcast domains.

This enhances security by preventing hosts in one VLAN from directly communicating with hosts in another without passing through a routing device, and it improves network performance by reducing broadcast traffic.

Inter-VLAN Routing:

A Layer 3 device (Router-on-a-Stick or Multilayer Switch) is configured to allow controlled communication between different VLANs. This is essential for resources that need to be accessible across departments.

DHCP Server:

A centralized DHCP server is configured to dynamically assign IP addresses to endpoints within each VLAN. This simplifies IP address management and prevents configuration errors.

DNS Server:

A DNS server is implemented to resolve domain names to IP addresses, making the network more user-friendly.

Static & Dynamic Routing:

The network utilizes a combination of static routing for predictable paths (like a default route to the internet) and a dynamic routing protocol (e.g., OSPF or EIGRP) for scalable and automatic route discovery between routers.

Basic Security:

Standard Access Control Lists (ACLs) can be implemented to filter traffic between VLANs, providing a basic layer of security by permitting or denying specific communication flows.

🚀 How to Use
Prerequisites: You need Cisco Packet Tracer version 8.0 or higher installed.

Launch: Download the .pkt file from this repository and open it using Cisco Packet Tracer.

Explore: The network is fully configured. You can enter simulation mode to view data flow or inspect the running configurations on routers, switches, and servers.

Example Test Cases:
Ping from a PC in the Student VLAN to a PC in the Faculty VLAN to test inter-VLAN routing.

Ping the DNS server from any host PC.

Observe a PC obtaining its IP address from the DHCP server upon startup.

🧠 Learning Outcomes & Relevance to Cybersecurity
This project was more than just a configuration exercise; it was an opportunity to strengthen skills directly applicable to my target roles:

For a SOC Analyst: Understanding a properly segmented network is crucial. It helps in analyzing traffic logs, identifying anomalous cross-VLAN communication, and recognizing how attackers might try to pivot across a network. This knowledge forms the baseline for identifying deviations from normal network behavior.

For a System/Network Administrator: This project is a direct demonstration of the skills required to build, manage, and troubleshoot a corporate network. The ability to configure VLANs, routing, and core services like DHCP/DNS is fundamental to the role.

CompTIA Security+: The concepts implemented here, such as VLANs, ACLs, and network segmentation, are core topics within the "Network Security" and "Threats, Attacks, and Vulnerabilities" domains of the Security+ certification.

This project solidifies my understanding of how a secure and efficient network is built from the ground up.
