# Wireshark Network Traffic Analysis & Protocol Verification

## 🎯 Project Objective
The main objective of this project is to capture, filter, and analyze live network traffic using Wireshark. This helps in understanding how data packet structures work, verifying network protocols, and identifying baseline anomalies or potential security risks.

## 🛠️ Tools & Technologies Used
* **Network Analyzer:** Wireshark
* **Protocols Analyzed:** TCP, UDP, DNS, HTTP, ICMP
* **Environment:** Local Network (Wi-Fi/Ethernet)

## 🚀 Key Learning & Practical Steps Done
* **Live Packet Capture:** Initiated live traffic capture on the active network interface card (NIC) to record real-time data packets.
* **Protocol Verification:** Filtered and inspected core network protocols:
  * **DNS (Domain Name System):** Analyzed standard queries and responses to see how domain names resolve to IP addresses.
  * **HTTP (Hypertext Transfer Protocol):** Inspected unencrypted web traffic, request methods (GET/POST), and status codes.
* **TCP 3-Way Handshake Analysis:** Successfully isolated and analyzed the complete connection establishment process:
  * `SYN` ➔ `SYN-ACK` ➔ `ACK`
* **Packet Filtering:** Utilized advanced Wireshark display filters (e.g., `ip.addr == X.X.X.X`, `tcp.flags.syn == 1`, `dns`) to quickly isolate specific traffic and troubleshoot logs.
* **Security Inspection:** Checked packet headers and payloads to understand how to spot unusual patterns, clear-text data leaks, or unauthorized communication attempts.

## 📈 Key Outcomes
* Gained hands-on experience in analyzing the OSI model layers from actual live traffic.
* Developed the ability to differentiate between normal network behavior and anomalous packet patterns.
