# Cybersecurity Incident Report: ICMP Flood DoS Attack Mitigation
## Utilizing the NIST Cybersecurity Framework (CSF)

## 📌 Project Overview
As a Cybersecurity Analyst at a multimedia company specializing in web design, graphic design, and social media marketing solutions, I analyzed and documented a recent Network Security Incident. The organization experienced a **Denial of Service (DoS)** attack that disrupted internal network services for two hours. 

This project demonstrates the application of the **NIST Cybersecurity Framework (CSF)** to analyze the incident, contain the threat, implement defensive hardening measures, and establish a strategic security improvement plan.

---

## 🏛️ Incident Analysis Workflow (NIST CSF Alignment)

### 1. Identify
* **Incident Type:** Denial of Service (DoS) / ICMP Flood Attack.
* **Root Cause:** An unconfigured perimeter firewall permitted unrestricted inbound ICMP traffic.
* **Systems Impacted:** Internal network infrastructure and core network services were completely overwhelmed, rendering internal network resources inaccessible to normal users for 2 hours.
* **Target:** Company's internal network availability.

### 2. Protect
To minimize the network's **Attack Surface** and mitigate future DoS threats, the network security team implemented the following immediate hardening controls:
* **Firewall Rate Limiting:** Enforced a new firewall rule to limit the rate of incoming ICMP packets.
* **IP Source Verification:** Configured strict anti-spoofing checks on the firewall to validate source IP addresses and filter out spoofed ICMP packets.

### 3. Detect
To ensure continuous visibility and early detection of anomalous network traffic patterns:
* **Network Monitoring Software:** Deployed monitoring solutions to log, track, and alert on abnormal traffic volume spikes or unusual communication patterns.
* **IDS/IPS Deployment:** Integrated an Intrusion Detection/Prevention System to scan and drop malicious ICMP traffic based on predefined signatures and suspicious characteristics.

### 4. Respond
An efficient Incident Response (IR) plan was executed to contain and neutralize the event:
* **Containment & Isolation:** The IR team immediately blocked all unauthorized inbound ICMP traffic at the perimeter.
* **Service Management:** Non-critical network services were temporarily suspended to preserve bandwidth and system resources for critical business functions.
* **Evidence Collection:** Network logs, firewall traffic data, and packet captures were archived to analyze attack vectors and refine threat intelligence signatures.

### 5. Recover
Strategies executed to ensure business continuity and quick restoration of operations:
* **Service Restoration:** Critical network resources were progressively brought back online and verified for integrity once the malicious traffic subsided.
* **Post-Incident Review:** Conducted a comprehensive audit of all network assets, configuration baselines, and access privileges to ensure no secondary vulnerabilities were exploited during the downtime.

---

## 🛠️ Technical Skills Demonstrated
* **Network Security & Hardening:** Implementation of Firewall Rules, Rate Limiting, and Anti-Spoofing controls.
* **Threat Detection:** IDS/IPS Configuration and Network Traffic Analysis.
* **Framework Proficiency:** Practical application of the **NIST CSF** lifecycle.
* **Incident Documentation:** Creating professional, executive-ready incident response reports.
