# TASK 1 Network Port Scanning
## Objective: Learn to discover open ports on devices in your local network to
  understand network exposure.
## Tools used :
   Nmap(Zenmap) 
   Wireshark (Optional)
## Steps Taken
1. Found my IP range using ipconfig - 192.168.1.0/24
2. Run Nmap TCP SYN scan using Zenmap
3. Saved scan resultc .. .txt" and ".html`.
4. Took screenshots of scan results.
5. Analyzed open ports and identified possible risks
6. 
## Open Ports Found
| Port | Service -     |Description
|------|---------------|----------------------------------------------------------|
| 135  | MSRPC         | windows RPC- internal use
| 139  | NetBioc -.    | File sharing (legacy)
| 445  | Microsoft-DS  | SMB file sharing 903 ISS Console Mgr Rare service-admin use?

7.
## Risk Analysis
| Port | Risk Level  | Recommendation
|------|-------------|----------------------------------------------------------------------------------------------------------|
| 135  |   Medium    | Block externally
| 139  |    High     | Disable if not in use N 
| 445  |    High     | Restrict to trusted devices

8.
## Screenshot ![Scan Result]
![Screenshot 2025-06-23 210854](https://github.com/user-attachments/assets/f3a4690b-a31f-4814-879c-8a21b6d21ad6)


 
## Conclusion
This task helped me understand port scanning, open port risks, and basic network security assessment.

  

