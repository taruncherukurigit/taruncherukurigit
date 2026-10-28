### Tarun Cherukuri
Network engineer · M.Eng Cybersecurity, University of Maryland (3.9 GPA) · CompTIA Network+ and Security+ · AWS Cloud Practitioner · CCNA in progress

I build and break networks on physical hardware in my own lab, then document what actually happened, bugs included. At UMD I designed and maintained a Cisco and Ubiquiti teaching lab network (OSPF, BGP, dual-stack IPv4 and IPv6) as a Graduate Course Assistant and led sessions of a graduate networking course as a Graduate Teaching Assistant.

Open to Network Engineer, NOC, Wireless Engineer and Network Analyst roles.

**Portfolio:** [taruncherukurigit.github.io/portfolio-page](https://taruncherukurigit.github.io/portfolio-page) · **LinkedIn:** [dsstaruncherukuri](https://www.linkedin.com/in/dsstaruncherukuri) · **Email:** taruncheru@gmail.com

---

### Home lab projects
Personal lab projects on real FortiGate, Cisco and Proxmox hardware. Each repo has the build notes and a troubleshooting log.

**[Segmented Enterprise Network](https://github.com/taruncherukurigit/cherwood-health)**
FortiGate 60E, Cisco Catalyst 3560E and 1921 ISR, 4 VLANs, SSL-VPN remote access, a RIPv2 link to a branch router and Prometheus and Grafana monitoring over SNMP. Segmentation verified with a live reconnaissance test.

**[Python Network Automation and ServiceNow Integration](https://github.com/taruncherukurigit/network-automation-toolkit)**
Nightly Python and Netmiko config backup, Git version history, drift detection and LLDP topology discovery across Cisco and FortiGate devices. Root-caused a 12-year-old open Paramiko and Cisco IOS SSH bug. Config drift opens a ServiceNow Incident through the Table REST API, tested against a full Change Request approval workflow.

**[HSRP High-Availability Lab](https://github.com/taruncherukurigit/hsrp-failover-lab)**
Two physical Cisco 3560E switches sharing one virtual gateway, with tuned priorities and timers and Spanning Tree aligned to the active switch. Failover proven with a real power-pull test and measured at 3.33 seconds from packet timestamps.

**[Active Directory, 802.1X and RADIUS](https://github.com/taruncherukurigit/activedirectory-cherwood)**
AD DS and DNS, an Enterprise CA and NPS acting as RADIUS for a Cisco access point and a FortiGate SSL-VPN, plus an enforced Group Policy. Valid and invalid logins tested on Wi-Fi and VPN with server-side log evidence.

**[Suricata IDS and SIEM-lite Dashboard](https://github.com/taruncherukurigit/suricata-siem-lite-lab)**
A Suricata sensor on a dedicated VLAN running the Emerging Threats Open ruleset (52,713 signatures) plus two custom rules I wrote after the stock rules missed both cases. Two live detections verified and shown in a Flask and SQLite dashboard.

**[Wireless Site Survey, Plainsboro Public Library](https://github.com/taruncherukurigit/plainsboro-library-survey)**
Passive 802.11 survey of two floors, 67 measurement points and 1,523 observations. Coverage met the -67 dBm threshold everywhere. The real issue was airtime contention between 8 access points, so the remediation is a channel and power plan, not more hardware.

**[Packet Capture Casebook](https://github.com/taruncherukurigit/packet-capture-casebook)**
Four real captures tied to bugs in the projects above: an SSL-VPN TLS 1.3 handshake, the HSRP failover cutover, LLDP discovery frames and a blocked DMZ to Trusted reconnaissance attempt.

**[Kindle Daily Digest Pipeline](https://github.com/taruncherukurigit/kindle-daily-digest)** · **[Homelab RSS Digest Pipeline](https://github.com/taruncherukurigit/homelab-rss-digest-pipeline)**
Self-hosted automation on Proxmox LXC: FreshRSS, n8n, a Flask receiver and pandoc turn 18 categories of RSS feeds into a Kindle EPUB twice a day. A Docker Compose stack with ntfy pushes digests to a phone over Tailscale.

---

### Stack
FortiGate · Cisco IOS · Ubiquiti EdgeRouter and UniFi · OSPF · BGP · HSRP · VLANs · SSL-VPN · Active Directory · NPS/RADIUS · 802.1X · Suricata · Wireshark · Python · Netmiko · Git · Flask · SQLite · Prometheus · Grafana · Proxmox · Debian · Docker · n8n · Tailscale · nginx · ServiceNow

### Certifications
CompTIA Network+ · CompTIA Security+ · AWS Certified Cloud Practitioner · CCNA (in progress)
