### 🛡️ IDS Fundamentals

**Room:** [IDS Fundamentals — TryHackMe](https://tryhackme.com/room/idsfundamentals)  
**Status:** ✅ Completed  
**Date:** *11 June 2025* 

---

### 🎯 Objective  
Learn what Intrusion Detection Systems (IDS) are, the types of IDS and detection modes, and gain hands-on experience with Snort including analysing live traffic and PCAP files using default and custom rules.

---

### 🗝️ Key Concepts  
- **Intrusion Detection System (IDS)** — Monitors network or host activity for signs of malicious behaviour and generates alerts.  
- **HIDS (Host IDS)** — Monitors and detects threats on a specific device.  
- **NIDS (Network IDS)** — Monitors traffic across an entire network to detect threats.  
- **Signature-Based Detection** — Matches traffic against known patterns (signatures) of attacks.  
- **Anomaly-Based Detection** — Flags deviations from normal behaviour, helpful for detecting zero-day attacks.  
- **Hybrid IDS** — Combines both signature and anomaly-based techniques.  
- **Snort** — A powerful, open-source IDS that supports packet sniffing, packet logging, and real-time intrusion detection.  
- **Snort Rule Components** — Action, protocol, source/destination IPs and ports, message (msg), signature ID (sid), and revision (rev).

---

### 🛠️ Tools Used  
- **Snort** — Used to detect network intrusions in real-time and from PCAP files using both default and custom rules.  
- **nano** — Used to edit the `local.rules` file in Snort for custom rule creation.  
- **ping** — Used to generate ICMP traffic to test Snort rule functionality.

---

### ⚠️ Challenges Faced  
- Understanding the subtle differences between deployment modes (HIDS vs NIDS) and detection methods.  
- Getting familiar with the syntax and structure of Snort rules took some trial and error.  
- Ensuring Snort was running with the correct interface and configuration when testing rules.

---

### 🧠 What I Learned  
- The roles and differences between host-based and network-based IDS solutions.  
- How signature-based and anomaly-based detection work, along with their pros and cons.  
- How to write and test a custom Snort rule to detect specific traffic like ICMP (ping) to loopback.  
- How to run Snort on PCAP files for forensic analysis and extract useful detection data.

---

### 🌐 Real-World Application:  
> IDS tools like Snort help detect malicious activities that might bypass firewalls, including lateral movement, reconnaissance, or post-exploitation behaviour. Analysts use Snort in real environments for both live monitoring and post-incident forensics using saved PCAP files.

---

### 💭 Reflections:  
- Writing my own Snort rule and seeing it trigger on a ping felt satisfying and showed how precise IDS rules can be.  
- Running Snort against PCAPs gave me a taste of real-world forensic analysis workflows.  
