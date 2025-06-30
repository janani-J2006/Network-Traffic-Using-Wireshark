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

✅ **1. Updated Kali Linux and installed Wireshark:**
```bash
sudo apt update
sudo apt install wireshark -y
✅ 2. Started Wireshark and began packet capture:

Selected my network interface (e.g., eth0 or enp0s3).

Clicked the shark fin icon to start capturing.

✅ 3. Generated ICMP traffic:

bash
Copy
Edit
ping google.com
Observed and filtered icmp packets in Wireshark.

Took a screenshot of ICMP traffic.

✅ 4. Observed DNS traffic:

DNS packets appeared automatically during ping or curl since domain resolution triggers DNS queries.

Applied filter dns in Wireshark.

Took a screenshot of DNS traffic.

✅ 5. Generated TCP traffic:

bash
Copy
Edit
curl http://google.com
Observed and filtered tcp packets in Wireshark.

Took a screenshot of TCP traffic.

✅ 6. Saved the captured packets:

Saved the capture as network-capture.pcap.
