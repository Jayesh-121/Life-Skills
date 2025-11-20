# Firewall in Computer Networks

A firewall is a network security system that monitors and controls incoming and outgoing network traffic based on predefined security rules. It acts as an intermediary between trusted internal network and external networks, preventing unauthorized access and filtering harmful data.

## Hardware and Software Firewalls

### Hardware Firewalls

Hardware firewalls are physical devices placed between the network and the gateway. They provide dedicated processing for traffic filtering and are commonly used in enterprise environments. They offer high performance, centralized protection, and operate independently of host systems.

### Software Firewalls

Software firewalls are installed on individual devices. They monitor and control traffic at the application or OS level. These firewalls are flexible and easy to configure, making them suitable for personal systems and small networks, though they consume host resources.

## Types of Firewall

### Packet-Filtering Firewall
Packet filtering analyzes packets based on header information such as IP addresses, ports, and protocols. Rules are defined to allow or block packets based on these parameters.

### Stateful Inspection Firewall
Maintains context of active connections and makes filtering decisions based on connection state as well as packet header information.

### Application Layer (Proxy) Firewall
Operates at Layer 7 of the OSI model. It inspects full packet payloads and can enforce application-specific rules. Provides strong security but may introduce latency.

### Next-Generation Firewall
Combines traditional firewall features with advanced capabilities such as intrusion prevention (IPS), deep packet inspection, TLS/SSL inspection, and application awareness.

### Unified Threat Management Firewall
An all-in-one security device that integrates firewall with antivirus, VPN, intrusion detection, and content filtering. Suited for small to medium businesses needing simplified management.

## References

1.  GeeksforGeeks –  https://www.geeksforgeeks.org/firewalls-in-computer-network/
2. Fortinet – [https://www.fortinet.com/resources/cyberglossary/firewall](https://www.fortinet.com/resources/cyberglossary/firewall)
3. Cisco – https://www.cisco.com/c/en/us/products/security/firewalls/what-is-a-firewall.html
4. Cloudflare –[https://www.cloudflare.com/learning/security/what-is-a-firewall/](https://www.cloudflare.com/learning/security/what-is-a-firewall/)


    
