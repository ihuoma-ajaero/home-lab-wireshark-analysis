
🧠 Wireshark Recap: Cybersecurity Home Lab Project #1

🔹 Project Title:
Network Traffic Analysis with Wireshark


🔹 Purpose:
To understand how data moves across a network and practice inspecting real-time traffic using Wireshark, a network protocol analyzer. This skill is foundational for threat detection, packet analysis, and security monitoring.


🔹 Tools Used:
Wireshark (installed on Windows 11 VM via Parallels Desktop on Mac)


🔹 Key Activities Completed:
Installed Wireshark with proper Npcap configurations

Ran packet capture while browsing the internet

Filtered traffic using expressions like:

- tcp contains "admin123"

- tcp

- ip.addr == <your IP>

- tcp.analysis.flags

Identified unencrypted traffic and understood what kind of data could be visible in plain text

Observed different protocols: TCP, DNS, HTTP, etc.


🔹 Screenshots Included:
Wireshark open with captured traffic

Applied filters (e.g., TCP, tcp.analysis.flags tcp contains "admin123")

Sample packets showing unencrypted data


🔹 What I Learned:
Not all traffic is encrypted; HTTP reveals data like URLs in plain text

Packet filters are powerful for narrowing down network events

Wireshark is a strong entry tool for learning how attackers might sniff sensitive data in a network


🔹 Next Steps:
Begin Project #2: SIEM Log Analysis with Splunk

Continue building my cybersecurity home lab with more tools and documentation