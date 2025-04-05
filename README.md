
#Cybersecurity Home Lab Project 1

##🔹 Project Title:
Network Traffic Analysis with WIRESHARK

##🔹 Purpose:
To understand how data moves across a network and practice inspecting real-time traffic using Wireshark, a network protocol analyzer. This skill is foundational for threat detection, packet analysis, and security monitoring.

##🔹 Tools Used:
Wireshark (installed on Windows 11 VM via Parallels Desktop on Mac)

![Desktop without security tool](https://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/Blank%20Desktop%20without%20security%20tools.png)

##🔹 Key Activities Completed:
Installed Wireshark with proper Npcap configurations

![Installing Wireshark](https://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/Installing%20wireshark.png)

Ran packet capture while browsing the internet
Filtered traffic using expressions like:
- tcp
  
![Filtering by Protocol](https://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/filtering%20by%20protocol.png)

- ip.addr == <your IP>

![Filtering by IP address](http://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/Filtering%20by%20ip%20address)

- tcp.analysis.flags
  
![Filtering to detect and analyze possible flags](https://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/filtering%20for%20flagged%20traffic.png)
  
- tcp contains "admin123"
  
![Filtering for specific strings](https://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/unsecure%20traffic.png)

Identified unencrypted traffic and understood what kind of data could be visible in plain text

![Unsecure https webpage](https://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/filtering%20unsecure%20traffic.png)

![Unencrypted tcp packet](https://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/tcp%20filter%20revealing%20password%20from%20unencrypted%20traffic.png)

![Unencrypted tcp packet revealing username and password](https://github.com/ihuoma-ajaero/home-lab-wireshark-analysis/blob/main/unsecure%20traffic.png)


Observed different protocols: TCP, DNS, HTTP, etc.

🔹 What I Learned:
-Not all traffic is encrypted; HTTP reveals data like URLs in plain text

-Packet filters are powerful for narrowing down network events

-Wireshark is a strong entry tool for learning how attackers might sniff sensitive data in a network


🔹 Next Steps:
Begin Project #2: SIEM Log Analysis with Splunk

Continue building my cybersecurity home lab with more tools and proper documentation
