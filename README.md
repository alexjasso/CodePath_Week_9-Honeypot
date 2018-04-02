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

**Summary of Data Collected**
- Number of attacks: 
   - 12080
- Number of malware samples and/or payloads:
   - 2000
   
**Kippo/Cowrie Honeypot Charts (Bruteforcing data)**
- Top Users:
   - admin, root, pi, butter, mining, guest, minera, miner, DUP, oracle
- Top Passwords: 
   - password, admin1234, admin, 11111, 1234, default, changeme, admin123, manager, xmhdipc

**Conclusion**

The data collected and analyzed using the dafault MHN Server metrics gave good insight 
into the intensity of attacks happening out in the wild. However, I think it would have been
helpful to use some other tools besides MHN's dashboard to analyze the data collected in more detail. 
The information on the main dashboard was useful. Unfortunately it only provides details on the last 24 hours
and I did not find a way to analyze the entire data collected at the end of my assignment, 
besides the Kippo/Cowrie Charts for bruteforcing data. 

Next time I think it would be a good idea to set up Splunk with the MHN Splunk App 
as shown in this [tutorial.](https://medium.com/@himynamesdave/splunking-the-modern-honey-network-getting-value-from-your-honeypots-data-part-1-d05f13cb9411)

