# Day 11 - Network Services

## 1. Network Service and Port Number
**Service:** FTP (File Transfer Protocol)  
**Port:** 21  

## 2. Connection to Port Scanning (Nmap)
Port scanning with tools like **Nmap** allows us to discover which network services are active on a target. By scanning port 21, we can identify if an FTP service is running, determine its version (e.g., vsftpd), and look for vulnerabilities like "Anonymous Login."

## 3. Firewall Control (Day 10)
A **Firewall** acts as a security barrier. It can be configured with rules to either `ALLOW` or `DENY` traffic to specific ports. For example, a firewall can restrict access to port 21 so that only authorized IP addresses from the internal network can connect to the FTP service, preventing external attackers from attempting to brute-force it.

## 4. Concept Learned
The most important concept I learned is the **Client-Server model** and how services use specific ports to listen for requests. I also learned how unencrypted services (like Telnet and FTP) can expose sensitive data in plaintext, making them high-risk if not properly secured.
