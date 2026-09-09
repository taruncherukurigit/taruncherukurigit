### Tarun Cherukuri
Network Engineer pursuing CCNA & CWNA · M.Eng Cybersecurity, University of Maryland (3.9 GPA)

I build networks on real hardware, not simulators — FortiGate, Cisco IOS, and whatever breaks along the way gets documented, not hidden. Currently open to Network Engineer, NOC, Wireless Engineer, and Network Analyst roles.

Portfolio: [taruncherukurigit.github.io/portfolio-page](https://taruncherukurigit.github.io/portfolio-page) · LinkedIn: [dsstaruncherukuri](https://www.linkedin.com/in/dsstaruncherukuri)

---

### Cherwood Corporation — a multi-division network engineering portfolio
A fictional parent company, real hardware. Four divisions live so far, each one built end-to-end and documented honestly, including the bugs.

**[Cherwood Health](https://cherwood.tarunc.com)** — [GitHub](https://github.com/taruncherukurigit/cherwood-health) · [Pages mirror](https://taruncherukurigit.github.io/cherwood-health/)
Segmented enterprise network — FortiGate 60E, Cisco 3560E/1921, 4 VLANs, SSL-VPN, RIPv2 branch routing, Prometheus/Grafana monitoring, a live-tested attack simulation. 21/21 build parts complete.

**[Cherwood Network Solutions](https://networksolutions.tarunc.com)** — [GitHub](https://github.com/taruncherukurigit/network-automation-toolkit) · [Pages mirror](https://taruncherukurigit.github.io/network-automation-toolkit/) · [Live topology map](https://netmap.tarunc.com)
Unattended Python/Netmiko automation — nightly config backup, Git version history, drift detection, and LLDP-based topology discovery across every managed Cherwood device, reconciling Cisco IOS and FortiOS's completely different neighbor-discovery formats. Includes root-causing a 12-year-old, still-open Paramiko/Cisco IOS SSH bug, plus a fixed-width CLI parsing bug found later when a new switch's longer hostname silently broke a column-based parser.

**[Cherwood Financial](https://failover.tarunc.com)** — [GitHub](https://github.com/taruncherukurigit/hsrp-failover-lab) · [Pages mirror](https://taruncherukurigit.github.io/hsrp-failover-lab/)
A real two-switch HSRP failover pair on physical Cisco 3560E hardware, verified against an actual power-pull failure test — not a config toggle. Explicit priorities, tuned timers, and Spanning Tree deliberately aligned to the HSRP-active switch. Measured failover: originally ~2 seconds by stopwatch, later re-measured at 3.33 seconds from raw packet timestamps (see Packet Capture Casebook below).

**[Packetgeist](https://packetgeist.tarunc.com)** — [GitHub](https://github.com/taruncherukurigit/plainsboro-library-survey) · [Pages mirror](https://taruncherukurigit.github.io/plainsboro-library-survey/)
Passive 802.11 site survey of a three-storey public library — 67 measurement points, 1,523 observations, 8 access points characterized. Coverage was never the problem; channel planning was.

---

### Cross-division evidence

**[Packet Capture Casebook](https://github.com/taruncherukurigit/packet-capture-casebook)**
Four real packet captures tied to specific bugs and design decisions across the divisions above — not a tutorial series, evidence that packets can actually be read, not just described. SSL-VPN TLS 1.3 negotiation (plus an unsolicited internet scanner caught mid-handshake against the intentionally exposed portal), HSRP failover re-measured at 3.33s from raw timestamps, LLDP discovery frames matched against `topology.py`'s own parser, and a blocked DMZ→Trusted reconnaissance attempt proven at the packet level. Every capture rides on traffic already in motion elsewhere in the portfolio — no infrastructure built just to generate it.

---

### Stack
FortiGate · Cisco IOS · HSRP · Wireshark · Python · Netmiko · Git · Flask · Prometheus · Grafana · Proxmox · nginx · Cloudflare Tunnel

### Certifications
CompTIA Network+ · CompTIA Security+ · AWS Certified Cloud Practitioner · CCNA (in progress) · CWNA (in progress)

---

Every project above ships with a real troubleshooting log — actual bugs, root causes, and dead ends, not a cleaned-up highlight reel.
