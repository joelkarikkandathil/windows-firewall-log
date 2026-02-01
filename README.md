## Evidence & Validation

### Port Scan Simulation
An Nmap scan was executed from Kali Linux (WSL2) against the Windows host to simulate reconnaissance activity.

![Nmap Scan](screenshots/nmap-scan.png)

### Firewall Detection & Blocking
Windows Firewall successfully blocked inbound scan attempts and logged dropped packets.

![Firewall Logs](screenshots/firewall-log.png)

Sample log entries are included in `logs/blocked_scan.log`.
