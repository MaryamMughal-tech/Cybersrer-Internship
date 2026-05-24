# 🛡️ 6-Week SOC & Defensive Cybersecurity Lab (Cyberster Internship)

A comprehensive, hands-on enterprise SOC (Security Operations Center) lab architecture simulated over a 6-week intensive engineering track. This repository documents the deployment of SIEM pipelines, network intrusion detection systems, malware analysis workflows, and incident response operations.

---

## 💻 Lab Infrastructure Architecture
* **Attacker Machine:** Kali Linux
* **SIEM / Core Hub:** Ubuntu Server (Wazuh Architecture)
* **Victim Endpoint:** Windows Enterprise Client
* **Hypervisor Layer:** Oracle VirtualBox (Isolated Host-Only & NAT Topologies)

---

## 📅 Weekly Engineering Breakdowns

### 🚀 Week 1: Network Baseline Auditing & Lab Deployment
* **Packet Architecture:** Analyzed network packet streams using **Wireshark** to decode core headers across HTTP, DNS, TCP, UDP, and ICMP.
* **Network Topology:** Provisioned virtual routing infrastructure with network interface adapters to guarantee zero host-leakage during active staging.
* **SIEM Bootstrapping:** Initialized automated server setup pipelines for centralized event ingestion.

### 🛡️ Week 2: Configuration & Detection Engineering (Wazuh SIEM)
* **File Integrity Monitoring (FIM):** Configured real-time system monitoring hooks over sensitive operating system keys and system vectors.
* **Custom Rules Deployment:** Authored custom detection decoders to log local user generation hooks and detect active SSH brute-force actions.
* **SOAR Automation:** Programmed an operational active-response infrastructure utilizing **Firewall-Drop automated shell routines** to isolate attacker endpoints at the network perimeter.

### 🌐 Week 3: Layered Network Defense & NIDS Integration
* **Intrusion Detection:** Engineered and structured **Suricata IDS engine deployments** over live kernel packet captures.
* **Attack Footprint Signatures:** Developed strict rule conditions to alert against automated vulnerability scanning (Nmap arrays) and Layer 4 Flooding (ICMP Floods).
* **SIEM Log Aggregation:** Bound Suricata engine alert formats into the backend Wazuh pipeline to correlate multi-tier application events.

### 🧠 Week 4: Threat Intelligence & MITRE ATT&CK Mapping
* **API Ingestion Frameworks:** Embedded active **VirusTotal API connections** within the system core to evaluate dropped file hash signatures on execution.
* **IOC Threat Feeds:** Integrated malicious endpoint directories (URLhaus feeds) to parse outbound requests for known operational tracking command networks.
* **Tactics Framework:** Mapped active detection profiles back to the structural **MITRE ATT&CK matrix** inside dashboard views.

### 🦠 Week 5: Malware Analysis & NIST Incident Response
* **Static Malware Extraction:** Audited file payloads, signature hashes, and entropy patterns of live samples including **WannaCry Ransomware** and **Zeus Banking Trojan**.
* **Dynamic Behavior Auditing:** Monitored system state mutations, process trees, and registry overrides utilizing cloud sandboxes (Hybrid Analysis).
* **NIST Incident Lifecycles:** Authored a production-grade response template defining standard procedures for containment, mitigation, and system recovery.

### 🕵️‍♂️ Week 6: Insider Threat Staging & Forensics Simulation
* **Attack Reconstruction:** Audited internal lateral-movement steps including data staging, base64 encoding mutations, exfiltration vectors, and anti-forensic log wiping.
* **Data Decoding:** Analyzed encrypted exfiltrated payload fragments through custom **CyberChef recipes** to reconstruct internal documentation.
* **Detection Engineering:** Hardened rulesets to flags recursive string encodings inside transient storage targets.

---

## 🛠️ Security Technology Stack
* **SIEM Infrastructure:** Wazuh SIEM Framework
* **Network Security Engines:** Suricata IDS, Wireshark Packet Analyzer
* **Perimeter Policy Controls:** Netfilter `iptables`, `ipset` configurations
* **Forensic Toolkits:** CyberChef Engine, Hybrid Analysis API, VirusTotal Sandbox
