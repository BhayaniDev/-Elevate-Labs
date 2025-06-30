Network Traffic Capture and Analysis using Wireshark

📋 Task Overview

   Objective:    Capture live network traffic using Wireshark and identify key protocols and traffic types.

   Tools Used:     
- Wireshark (Free and open-source packet analyzer)

   Deliverables:     
- `.pcap` packet capture file  
- Summary report (`.docx`) analyzing captured network traffic and identified protocols

---

    🛠️ Steps Followed

1.    Installed Wireshark    on the system.
2.    Selected active network interface    (Wi-Fi).
3.    Started live capture    using Wireshark.
4.    Generated traffic    by browsing websites and pinging servers.
5.    Stopped capture    after 1 minute.
6.    Applied protocol filters    (DNS, HTTP, TCP, ICMP).
7.    Saved capture as    `network_traffic_sample.pcap`.
8.    Analyzed protocols    and summarized findings in a report.

---

    🔍 Protocols Identified

-    DNS:    Domain name resolution for accessed websites.
-    HTTP:    Web browsing (unencrypted traffic).
-    TCP:    Transport-level protocol, visible handshakes and termination.
-    ICMP:    Echo requests/replies from `ping`.

---

    📄 Files Included

| Filename                         | Description                                      |
|----------------------------------|--------------------------------------------------|
| `network_traffic_sample.pcap`    | Packet capture file from Wireshark              |
| `Detailed_Packet_Capture_Report.docx` | Detailed protocol and traffic analysis report   |
| `README.md`                      | This instruction and summary guide              |

---

    ✅ Outcome

Gained practical experience in:
- Capturing live network traffic
- Identifying protocol behaviors
- Using filters to analyze specific types of traffic
- Understanding packet-level communication patterns
