# CodePath_Week_9-Honeypot

## Honeypot Report
>For this project 8 honeypots were deployed and managed using the Modern Honey Network server application and Google Cloud. Out of the 8 deployments, 6 ran successfully but only 4 collected attack information. 

<img src="https://github.com/jsska20/CodePath_Week_9-Honeypot/blob/master/Week_9-Honeypots-Attacks.gif">

**Honeypot #1: Ubuntu - Dionaea with HTTP**
- Dionaea is meant to be a nepenthes successor, embedding python as
scripting language, using libemu to detect shellcodes, supporting ipv6
and tls
- Its purpose is to trap malware exploiting vulnerabilities exposed
by services offerd to a network, the ultimate goal is gaining a copy of
the malware.
 
**Honeypot #2: Ubuntu - Suricata** 
- Suricata is "capable of real time intrusion detection (IDS), inline intrusion prevention (IPS), network security monitoring (NSM) and offline pcap processing."

**Honeypot #3: Ubuntu - Snort** 
- Snort is an "open source intrusion prevention system capable of real-time traffic analysis and packet logging."

**Honeypot #4-6: Ubuntu - cowrie**
- Cowrie is a medium interaction SSH and Telnet honeypot designed to log brute force attacks and the shell interaction performed by the attacker.

**Honeypot #7 Ubuntu - P0f**
-p0f is a "tool that utilizes an array of sophisticated, purely passive traffic fingerprinting mechanisms to identify the players behind any incidental TCP/IP communications (often as little as a single normal SYN) without interfering in any way."

**Honeypot #8 Ubuntu - Kippo**
- Kippo is a SSH honeypot tool writen in Python that can log brute force attacks and the shell interaction performed by the said attacker.

- Any issues you encountered
- A summary of the data collected: number of attacks, number of malware samples, etc.
- Any unresolved questions raised by the data collected

Additionally, include a json export of the data you collected in the repo
