# Network-Forensics-Lab
This project is a forensic investigation into a simulated data breach using **Wireshark**.   The goal was to analyze captured network traffic, identify how an attacker stole a file, and reconstruct key evidence.


## Objectives
- Identify attacker and server IP addresses
- Determine the protocol used for exfiltration
- Extract compromised credentials
- Recover the stolen file and its original extension
- Analyze file contents and document findings

## Key Findings
- **Attacker IP:** `xxx.xxx.xxx.132`  
- **Server IP:** `xxx.xxx.xxx.133`  
- **Protocol Used:** FTP  
- **Compromised Credentials:** `irfan : vcu123`  
- **Stolen File:** `vcu.abc` → originally a `.png`  
- **File Contents:** Successfully reconstructed from packet capture (see PDF)

## Tools Used
- Wireshark (packet capture analysis, TCP stream reconstruction)

## Skills Demonstrated
- Packet capture and traffic analysis
- Identifying attacker/server communication
- Extracting credentials from network traffic
- File carving and reconstruction
- Incident reporting with supporting evidence

## Report
The full investigation write-up, including screenshots and evidence, is available in the Network Forensics Lab Folder.

