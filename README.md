# Pine-li
Router1  
1. Router Identification and Basic Information:  
--  Router Model: cisco 4321
-- Version: Include the make, model, and software (IOS) version.  
-- Hostname: R1  
-- IP Address of the Router: 192.168.53.1  
-- Router Location: Server center
2. Interfaces and IP Addressing:  
-- Interface Names: GigabitEthernet0/0/0, GigabitEthernet0/0/1, Serial0/0.  
-- Interface IP Addresses: Document IP addresses assigned to each interface.  
   G0/0/0 192.168.53.1/24  Link to Switch 1  
   G0/0/1 DHCP Link to ISP  
-- Subnet Masks: The subnet mask used on each interface.  
-- VLAN Information: If VLANs are configured, document which interfaces belong to which VLAN.  
Interface Status: Indicate whether the interfaces are up or down.
3. Routing Configuration:  
-- Routing Protocols: Documentation of any routing protocols in use (e.g., RIP, OSPF, EIGRP, BGP).  
-- For OSPF, include the OSPF process ID, area IDs, and networks participating.  
-- For EIGRP, include the autonomous system (AS) number, and network statements.  
-- For BGP, include the AS numbers and relevant neighbors.  
-- Static Routes: Include any manually configured static routes.  
-- Default Routes: Document the default route (if configured).  
-- Routing Tables: Include any relevant routing table entries.  
4. Access Control Lists (ACLs):  
-- Standard and Extended ACLs: Document any ACLs configured on the router, detailing the rules that control traffic flow.  
-- Inbound/Outbound ACLs: Specify which interfaces and directions ACLs apply to.  
5. Network Address Translation (NAT):
NAT Configuration: Document any NAT rules (e.g., static, dynamic, or PAT).
Inside and Outside Networks: Clearly define the inside and outside networks involved in NAT.
6. Security and Authentication:
Passwords and Encryption: Document any encrypted or unencrypted passwords (e.g., enable password, line vty passwords).
SSH/Telnet Access: Include settings related to remote management access.
User Accounts: Documentation of user accounts and their privileges (e.g., username admin privilege 15).
Firewall Settings: Any security-related configurations (e.g., zone-based firewall or firewall rules).
VPN Configuration: If the router is part of a VPN, document the VPN protocols, keys, and tunnel configurations.
7. Quality of Service (QoS) Configuration:
Traffic Shaping and Policing: Document any QoS policies in place to manage network traffic.
Prioritization of Traffic: Include configurations for prioritizing certain types of traffic (e.g., VoIP or video).
8. High Availability and Redundancy:
HSRP/VRRP/GLBP: If using any of these redundancy protocols for router failover, document their configurations.
Hot Standby Configuration: Documentation of any secondary or backup routing devices.
Link Aggregation (EtherChannel): If interfaces are grouped, document the channel group settings.
9. Logging and Monitoring:
Syslog Servers: If configured, include syslog server details.
SNMP Configuration: Documentation of SNMP community strings and any monitoring systems in place.
NTP (Network Time Protocol): If configured, include the NTP server information.
10. Firewall and Security Policies:
Access Policies: Document firewall policies, port security settings, and any intrusion prevention/detection system configurations.
Security Protocols: Any VPN or IPsec configurations for secure communication between remote locations.
11. Time and Scheduling:
Time Zone Configuration: Document the time zone and daylight saving settings.
Scheduled Tasks: Document any cron jobs or scheduled tasks that the router performs automatically (e.g., backup or maintenance tasks).
12. Router Performance and Troubleshooting:
Interface Statistics: Include data related to traffic flow and interface errors.
Error Counters: Documentation of interface errors, drops, and other performance issues.
Diagnostic Commands: Include any custom troubleshooting or diagnostic commands regularly used on the router.
13. Backup and Recovery:
Configuration Backup Procedures: Document the process for backing up the router configuration.
Restore Process: Provide a clear recovery or restoration process in case of failure.
14. Software Updates and Patches:
IOS Version: Document the specific version of the IOS software running on the router.
Patch Management: Include information about any patches or software updates applied to the router.
