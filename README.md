# Network-Traffic-Using-Wireshark
## 📌 Overview
This project involves capturing and analyzing network packets on a Kali Linux virtual machine using Wireshark. The goal is to observe ICMP, DNS, and TCP protocols through specific network activities.

---

## 🖥️ Environment
- **OS:** Kali Linux (running in VirtualBox VM)
- **Tools Used:**  
  - Wireshark (for packet capture and analysis)  
  - Terminal commands: `ping`, `curl`

---

## 🔎 Steps Performed

 1. Updated Kali Linux and installed Wireshark:

sudo apt update
sudo apt install wireshark -y

---
2. Opened Wireshark and started capturing packets

Selected my network interface (e.g., eth0 or enp0s3).

Clicked the blue shark fin icon to start capture.

---

3. Checked for ICMP packets

In the terminal, I ran:

ping google.com

In Wireshark, I typed icmp in the filter box to see ICMP packets.

Took a screenshot.

---
4. Checked for DNS packets

When I pinged or used curl, DNS packets were automatically generated (because the system had to resolve google.com).

In Wireshark, I used the filter dns.

Took a screenshot.

---
5. Checked for TCP packets

In the terminal, I ran:

curl http://google.com

In Wireshark, I used the filter tcp to see TCP packets.

Took a screenshot.

---
6. Saved my Wireshark capture

Saved the capture file as network-capture.pcap.

Files Included
network-capture.pcap — The saved Wireshark capture.

networkcap.pcap — The saved Wireshark capture.

icmp.png — Screenshot of ICMP packets.

dns.png — Screenshot of DNS packets.

tcp.png — Screenshot of TCP packets.

