
# PENETRATION TESTING REPORT
## Footprinting & Network Scanning Phases

**W2-PM-FINAL | Cybersecurity | Networkwalks**

---

## 1. Project Information

| Details | Information |
|---|---|
| Pentester Name | Hafsa Fathima |
| Program/Batch | B084 – Networkwalks |
| Date | 12 November 2026 |
| Modules Completed | W2-PM1, W2-PM5 |
| Client/Target | Networkwalks and own local LAN |
| Permission | Written permission secured |
| Phases Covered | Reconnaissance, Footprinting and Network Discovery |

---

## 2. Liability Disclaimer

All activities were performed only on systems and devices for which appropriate written permission was secured or which I own. This project is for educational and research purposes only. Unauthorized access to computer systems is illegal. All testing must be conducted within an authorized scope.

---

## 3. Introduction

This report covers two practical activities completed during Week 2 of my Cybersecurity Internship at Networkwalks.

- Footprinting the networkwalks.com domain using Kali Linux tools.
- Scanning my own local network using Zenmap.

The activities demonstrate how reconnaissance collects information about a target and how network scanning identifies live hosts and network devices.

---

## 4. Tools Used

| Tool | Purpose |
|---|---|
| WHOIS | Domain registration information |
| WhatWeb | Website technology identification |
| NSLookup | DNS resolution |
| Curl | HTTP response header inspection |
| Wafw00f | Web Application Firewall detection |
| DNSRecon | DNS record enumeration |
| Zenmap | Network scanning and topology |
| Windows CMD | Local IP and MAC identification |

---

## 5. Activities Performed

### 5.1 Footprinting and Reconnaissance

I performed reconnaissance against the networkwalks.com domain using six Kali Linux tools.

**WHOIS**

Used to obtain publicly available domain registration information and identify name servers.

**WhatWeb**

Used to identify website technologies. The recorded results identified WordPress 7.0.4 and WP Download Manager 3.3.58.

**NSLookup**

Used to resolve the domain name to its IP address.

**Curl**

Used the `-I` option to inspect HTTP response headers and identify the exposed WordPress REST API endpoint.

**Wafw00f**

Used to identify the Web Application Firewall. The recorded result identified ModSecurity (SpiderLabs).

**DNSRecon**

Used to enumerate DNS records, including NS, MX, SPF, TXT and SRV records.

### 5.2 Network Scanning with Zenmap

I used Zenmap to perform network discovery on my local network.

The activities included:

- Identifying the local IP address and subnet.
- Discovering active hosts.
- Identifying IP and MAC addresses.
- Generating a network topology.

**Example network addresses recorded in the practical:**

| Device | IP Address 

**Ping Scan Command:**

```bash
nmap -sn 
```

**Quick Scan Command:**

```bash
nmap -T4 -F 
```

The topology view was used to visualize the discovered network devices.

*Note: These IP addresses are illustrative examples and must not be treated as verified scan results.*

---

## 6. Risk Analysis and Impact

| No. | Finding | Potential Impact | Risk |
|---|---|---|---|
| 1 | Web technology information exposed | Helps identify software requiring security review | Medium |
| 2 | Server IP address identifiable | Provides network location information | Low |
| 3 | HTTP technical information exposed | May assist technology fingerprinting | Low |
| 4 | WAF technology identifiable | Reveals security architecture information | Low |
| 5 | DNS infrastructure information exposed | Helps build an infrastructure profile | Medium |
| 6 | Multiple live hosts visible | Unknown devices may require investigation | Medium |

The risks are observations from reconnaissance and scanning, not confirmed vulnerabilities.

No exploitation or vulnerability validation was performed during these activities.

---

## 7. Recommendations

1. Regularly review publicly exposed website technology information.
2. Keep CMS platforms, plugins and software updated.
3. Review HTTP response headers.
4. Review DNS records periodically.
5. Properly configure and monitor the WAF.
6. Perform regular internal network discovery.
7. Investigate unknown devices.
8. Maintain updated network documentation.
9. Perform security testing only with proper authorization.

---

## 8. Learning Outcomes

Through this project, I gained practical knowledge of:

- Network reconnaissance techniques.
- Host discovery and network scanning.
- Port scanning fundamentals.
- Network topology visualization.
- DNS reconnaissance.
- Website technology identification.
- Basic network security assessment.
- Technical documentation and reporting.

---

## 9. Conclusion

During Week 2 of my Cybersecurity and Ethical Hacking internship, I completed practical activities covering footprinting, reconnaissance and network scanning.

I learned how WHOIS, WhatWeb, NSLookup, Curl, Wafw00f and DNSRecon help collect information about a target.

I also gained hands-on experience using Zenmap to discover active hosts, identify network devices and visualize network topology.

This project strengthened my understanding of cybersecurity fundamentals, responsible testing and technical documentation.

---

## 10. Evidence and Screenshots
 Complete Penetration Testing Report

📄 **Download / View My Report**

[Click here to view the PDF Report](W2-PM-FINAL%20-%20HF-B084_.pdf)
---
**END**
## Project Information
  
**👤 Author:
Waqas Karim CCIE

Cybersecurity Professional B084
LinkedIn: https://www.linkedin.com/in/waqaskarim/**

**📌 Project Information
Program Name: Cybersecurity program at Networkwalks | Week: 02 
LinkedIn : https://www.linkedin.com/in/hafsa-fathima-45799b2ba/**

