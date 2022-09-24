# nmap
flag|name|details|
---|---|---|
-sX|Xmas scan|Sets the FIN, PHS, URG flags. If port is closed then RST will be sent back to us.|
-sY|SCTP init scan|Stealthy, never completes SCTP associations.|
-sN|NULL scan|Doesn't set any bits (TCP header is 0)|
-sF|FIN scan|Sets only the TCP FIN bit|
-sP|Skip port scan|Doesn't do port scan after host discovery, and only prints available hosts that responded to the scan.|
-sA|TCP ACK scan|Used for mapping out firewall rulesets, determining if they're stateful or not, and which ports are filtered.|
-sV|Version detection|Enables version detection. Alternative: -A|
-T[0/1/2/3/4/5]|Time|lower number: slower, but reduced possibility of IDS detection; greater number: faster, but makes more noise| 
-sS|TCP Stealth scan|Fast, never completes a TCP connection.|
-sU|UDP scan|Sends UDP packets and finds services running on UDP ports.|
-sM|TCP Maimon scan|Same as NULL, FIN and Xmas scans except the probe is FIN/ACK. An RST packet is generated in response indicating whether the port is open or not (Stateful firewalls return no RST packet).|
-sT|TCP Connect scan|Sends TCP packets and finds services running on TCP ports.|
-F|Fast scan|Scans 100 ports instead of 1000.|
-oX|XML output|XML output|
-oG|Grep searchable output|Grep searchable output.|
-O|OS scan|Requires root privilege.|
-R|DNS resolution for all targets|Always reverses DNS resolution on the target IP addresses.|
-r|random|Randomize port scans.|
-PP|ICMP timestamp ping|ICMP timestamp ping|
-PU|UDP ping|UDP ping|
-PN|Don't ping|Don't ping|
-PY|SCTP init ping|SCTP init ping|
-D|Decoy|It appears to the remote host that the hosts you specify as decoys are scanning too.|
-f|fragment packets|Uses tiny fragmented IP packets.|
-S|Spoof source address|Spoof source address.|
-A|Aggressive|Enables advanced and aggressive options.|

---
# Other scans
## Banner Grabbing
Technique used to gain information about a computer's operating system on the network.

---
## IDLE/IPID Scanning
Consists of sending spoofed packets to a computer to find out what services are available. Accomplished by impersonating another computer (zombie) which network traffic is very slow or nonexistent.

---
## UDP Scanning
Sends UDP packets to various ports on the target host and evaluate the response packets to determine the availability of the service on the host.