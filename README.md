# Task 5: Capturing Network Traffic and Analysis with Wireshark

# Goal:
Capturing network traffic in real-time using Wireshark, inspecting various protocols, and learning elementary packet filtering techniques.

---

# Tools Utilized:
- Wireshark (Free Network Protocol Analyzer)
- Command Prompt (used to create ping requests)

---

 # Steps Carried Out:

1. Installed and launched Wireshark on my Windows computer.
2. Initiated packet capturing on the currently active network interface (Wi-Fi).
3. Visited several websites and activated the `ping` command to create traffic.
4. Halted the capture after approximately 1 minute.
5. Applied filters to examine protocols:
   - `http` – for web traffic
   - `dns` – for domain resolution
   - `tcp` – for transport-level communication
6. Saved the capture in a `.pcap` file format.
7. Generated a report detailing seen protocols and packet information.
8. Capture a screenshot revealing filtered packets by protocol.

---

# Protocols Identified:

- HTTP – Reveals browser to web server communication.
- DNS – Identifies domain name resolution queries.
- TCP – Data transmission protocol underlying.

---

# Files Included:

- `capture.pcap` – Packet capture file from Wireshark.
- `report.txt` – Overview of protocols seen and what was learned.
- `screenshot.png` – Wireshark filtered protocol view.

---

# Learnings:

- Familiarized myself with starting and ending a packet capture session in Wireshark.
- Learned the process of filtering based on protocol.
- Developed understanding about how packets move across various layers of a network.

---

# Notes:

This exercise gave excellent hands-on practice with packet analysis and protocol detection in real-time, which are critical skills in the field of cybersecurity.

