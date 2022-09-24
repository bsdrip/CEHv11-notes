# aLTEr
Virtual communication tower (4G cell tower) between 2 authentic endpoints.  MiTM

---
# KRACK attack
Key Reinstallation Attack is a replay attack on the Wi-Fi protected access protocol that secures Wi-Fi connections.

---
# Cross-Site Request Forgery (CSRF)
And innocent end-user is tricked by attacker into submitting a web request without their consent.

---
# Server-side request forgery
The attacker abuses functionality on the server to read or update internal resources.

---
# Command Injection Attacks
Execution of arbitrary  commands on the host operating system via a vulnerable application.

---
# File Inclusion Attack
An application builds a path to an executable code using and attacker-controlled variable in a way that allows the attacker to control which file is executed at run time.

---
# Hidden Field Manipulation Attack
Exploits a weakness in the server's trust of client-side processing by modifying data on the client-side, such as price information, and then submitting this data to the server, which processes the modified data.

---
# Web Parameter Tampering
Manipulating parameters exchanged between client and server to modify application data, such as user credentials and permissions.

---
# Cookie Tampering
Used for attacks such as session hijacking, where cookies with session identification information are stolen or modified by an attacker.

---
# XSS Reflection
XSS (Cross Site Scripting) is a web application vulnerability that permits an attacker to inject code into an outside website's contents.

---
# SQLi
Code injection technique, used to attack data-driven applications in which malicious SQL statements are inserted into an entry field for execution.

## Blind SQLi
Attacker sends payloads to the server and observes the response and behavior of the server to learn more about its structure. Attacker cannot see information about the attack in-band.
#### Boolean blind SQLi
The result will vary depending on whether the query is true or false.
#### Time based blind SQLi
The attacker can see from the time the database takes to respond whether the query is true or false.

## Error based SQLi
Attacker gets information about the database from the error message.

## UNION SQLi
UNION keyword can be used to retrieve data from other tables within the database.

## Out-of-band SQLi
Used when the attacker cannot use the same channel to launch the attack and gather information , or when a server is too slow or unstable for these actions. These techniques count on the capacity of the server to create DNS or HTTP requests to transfer data to an attacker.

# Compound SQLi
Using SQLi alongside cross-side scripting, DDoS, DNS hijacking.

# Tautology
Extract data using OR clause so WHERE will always be true.

# End-of-Line comment
SELECT * FROM user WHERE name = 'x' AND userid IS NULL; --';

---
# Sybil attack
A reputation system is subverted by creating multiple identities.

--- 
# Exploit kits
Collection of exploits, one-in-all tool for managing a variety of exploits altogether.

---
# Wrapping
Injecting a faked element into a message structure so that a valid signature covers the unmodified element while the faked one is processed by the application logic. Attacker can perform an arbitrary Web Service request while authenticating as a legitimate user.

---
# Cloudborne
Allowing an attacker to implant persistent backdoors for data theft into bare-metal cloud servers, which would be able to remain intact as the cloud infrastructure moves from customer to customer.

---

# Side channel attack
Based on information gained from the implementation of a computer system, rather than weaknesses in the implemented algorithm itself.

---
# Adaptive chosen-plaintext attack
Choosing subsequent plaintexts based on the information from the previous encryption.

---
# Known plaintext attack
Attacker has access to both the plaintext and its encrypted version.

---
# Bluejacking
Used to send messages to users without the recipient's consent.

---
# Bluesmacking
Variation of a common attack against networks, devices, and applications known as DDoS.

---
# Bluesnarfing
Unauthorized access of information from a wireless device through a Bluetooth connection.

---
# Bluebugging
Caused by lack of awareness. Similar to Bluesnarfing.

---
# Footprinting
Part of reconnaissance process used to gather information about a target computer system or network.
Used for obtaining:
- Domain names
- IP Addresses
- Namespaces
- Employee information
- Phone numbers
- E-mails
- Job information

---
# Enumeration
Process that establishes an active connection to the target hosts to discover potential attack vectors in the system.
Used for obtaining:
- Usernames, group names
- Hostnames
- Network shares and services
- IP tables and routing tables
- Service settings and Audit configurations
- Application and banners
- SNMP and DNS Details

---
# Scanning
Scanning a website's security, web-based program, network or filesystem for either vulnerabilities or unwanted file changes. Active collection of information associated with a direct impact on the target.

---
# Firewalking
Method of determining the movement of a data packet from an untrusted external host to a protected internal host through a firewall.

---
# Trickery and deceit
It involves the use of social engineering techniques to extract cryptographic keys.

---
# One-Time Pad
Contains many non-repeating groups of letters or number keys, which are chosen randomly

---
# Frequency Analysis
The study of the frequency or letters or groups of letters in a cipher text.

---
# Meet-in-the-middle attack
Generic space-time tradeoff cryptographic attack agains encryption schemes that rely on performing multiple encryption operations in a sequence.

---
# Man-in-the-middle attack
Attacker alters the communication between two parties who believe they are directly communicating with each other.

- [ ] ---
# Stealth virus
Changes the code that can be used to detect it.

---
# Tunneling virus
Attempts to bypass detection by antivirus scanner by installing itself in the interrupt handler chain.

---
# Cavity virus
Infects files without changing the size or damaging the file by overwriting the unused areas of executable files.

---
# Polymorphic virus
Infects files with an encrypted copy of itself, which is decoded by a decryption module.

---
# Multipartite virus
Can attack both the boot sector and executable files.

---
# Insertion attack
IDS evasion technique that depends on the TTL fields of a TCP/IP header.

---
# Obfuscation 
The process of concealing something important, valuable, or critical. An IDS can be evaded by obfuscating or encoding the attack payload in a way that the target computer will reverse but the IDS will not.

---
# Unicode invasion
Using Unicode representation, where each character has a unique value regardless of the platform to evade IDS.

---
# Collision attack
Tries to find two inputs that generate the same hash value.

---
# Baiting
Exploits human curiosity, like leaving an infected pendrive in a parking lot waiting for someone to plug it in their computer.

---
# Quid Pro Quo
"Something for something" attack. Hacker impersonates IT staff. Contacts the target and offers to upgrade or install software.

---
# Reverse social engineering
Attacker convinces the target that they have a problem that the attacker can solve.

---
# CRLF injection
Web app attack injecting Carriage Return and Line Feed into the user's input to trick the server that the current object is terminated and a new object has been initialized.

---
# Slowloris
DDoS attack which allows a single machine to take down another machine's web server with minimal bandwidth. Layer 7.

---
# Untethered jailbreaking
Devices is jailbroken after reboot.

---
# Tethered jailbreaking
Requires a computer to keep the device jailbroken.

---
# Semi-tethered jailbreaking
After reboot the device stays jailbroken but needs a computer to enable the jailbrake features.

---
# Semi-untethered jailbreaking
After reboot the device stays jailbroken with features off, but they can be enabled without a computer.

---
# Session donation
Attacker creates an account and sends authenticated link to the victim. Convincing the victim to provide more information about their account.

---
# Cryptanalysis attack
Study of ciphertext to understand how they work and finding and improving techniques for defeating or weakening them.

---
# Replay attack
Attacker eavesdrops on a secure network communication, intercepts it, and fraudulently delays or resends it to misdirect the receiver into doing what the hacker wants.

---
# STP attack
LAN-switches network protocol.

---
# Diversion theft
Attacker persuades delivery and transport companies that their deliveries and services are requested elsewhere.

---
# DROWN attack
Attacks servers supporting modern SSLv3/TLS protocol suites by using their support for the obsolete, insecure SSLv2 protocol to leverage an attack on connections using up-to-date protocols that would otherwise be secure.

---
# Agent Smith attack
Malicious application from a third party app store.

---
# Fileless malware
Malicious software that uses legitimate programs to infect the computer. It does not rely on files and leaves no footprint.

---
# Skimming
Capturing and stealing cardholder's personal payment information.

---
# Rainbow table attack
A rainbow table is a precomputed table for caching the output of cryptographic hash functions, usually for cracking password hashes.

---
# Brute force attack
Consists of an attacker submitting many passwords or passphrases with the hope of eventually guessing a combination correctly.

---
# Dictionary attack
A form of brute force attack technique for defeating a cipher or authentication mechanism by trying to determine its decryption key or passphrase by trying thousands or millions of likely possibilities, such as words in a dictionary or previously used passwords, often from lists obtained from past security breaches.

---
# Hybrid attack
Attacker blends two or more kinds of tools to carry out the assault.

---
# Daisy chaining
Gaining access to a network or a computer and using the same information to gain access to multiple networks and computers that contains desirable information.

---
# Netbios enumeration
Used to get shared resources on individual hosts on the network and the list of computers belonging to the domain.

---
# Corporate espionage 
A practice of using espionage techniques for commercial or financial purposes.
e.g.:
- Trespassing onto a competitor's property or accessing their files without permission
- Posing as a competitor's employee in order to learn company trade secrets or other confidential information
- Wiretapping a competitor
- Hacking into a competitor's computer
- Attacking a competitor's website with malware

---
# Markov Chain
Uses an analysis to calculate the probability of placing characters in a quasi-brute force attack.

---
# Toggle Case
Creates every possible case combination for each word in a dictionary. The password candidate 'do' would also generate 'Do', 'dO' and 'DO'.

---
# MAC flooding
Tries to overflow the CAM table.

---
# Internal monologue attack
Allows NTLMv1 challenge-response hashes to be obtained from the victim's system, without injecting code in the memory or interacting with protected services such as the LSASS.

---
# WS-Address spoofing
Scenario:
_An attacker sends a SOAP message containing WS-Address information to a web service server. The `<ReplyTo>` element doesn't contain the address of the attacker but instead the web server client which the attacker chosen to receive the message._

---
