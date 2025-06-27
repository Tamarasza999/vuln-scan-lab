## Network Analysis and Vulnerability Scanning

### Tools Extended  
- UTM: Hypervisor for lab network virtualization  
- Kali Linux: Attacker system for offensive security tasks  
- Metasploitable2: Vulnerable virtual machine for exploitation practice  
- traceroute: Network route analysis tool for hop tracing  
- ping: ICMP utility for connectivity validation  
- ip / route: Network configuration and routing inspection commands  
- Wireshark: Traffic sniffer for protocol-level packet capture  
- Nessus Essentials: Vulnerability scanner for host discovery and auditing

---

## Traceroute and Wireshark Network Diagnostics

**Security Overview**
- Two virtual machines (Kali and Metasploitable2) deployed on a shared NAT network  
- End-to-end connectivity validated via ICMP and traceroute  
- Network troubleshooting using route analysis and adapter verification  
- Traffic capture and analysis via Wireshark  

**Implementation Summary**

1. UTM Network Configuration
<img src="image2.png" width="400" alt="VirtualBox NAT Network Configuration"/>

2. Connectivity Validation 
<img src="screenshots/image04.png" width="400" alt="Traceroute Output"/>

3. Troubleshooting Procedures  
<img src="screenshots/image33.png" width="400" alt="Wireshark Capture Session"/>

4. Wireshark Traffic Capture
<img src="screenshots/image10.png" width="400" alt="Wireshark Capture Session"/>

5. Apply Filters

<img src="screenshots/image12.png" width="400" alt="Captured Packet Details"/>

6. Packet Inspection

<img src="screenshots/image13.png" width="400" alt="Captured Packet Details"/>

7. Statistics Summary
<img src="screenshots/image15.png" width="400" alt="Traffic Statistics in Wireshark"/>

---

## Nessus Vulnerability Scanning

**Security Overview**
- Target machine scanned for active services and known vulnerabilities  
- Host Discovery followed by in-depth Basic Network Scan  
- Results highlight critical issues including remote backdoors and deprecated SSL/TLS protocols  

**Implementation Summary**
1. Nessus Service Initialization
<img src="screenshots/image4.png" width="400" alt="Wireshark Capture Session"/>

2. Host Discovery Scan
<img src="screenshots/image7.png" width="400" alt="Nessus Host Discovery"/>

3. Basic Network Scan
<img src="screenshots/image9.png" width="400" alt="Nessus Basic Network Scan"/>

---

## Notes  
- All testing performed in an isolated lab environment
