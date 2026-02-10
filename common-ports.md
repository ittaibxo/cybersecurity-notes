# Common Ports Cheat Sheet

## Well-Known Ports (0-1023)

### FTP - File Transfer Protocol
- **Port 21** - Control
- **Port 20** - Data transfer
- Used for: Uploading/downloading files to servers

### SSH - Secure Shell
- **Port 22**
- Used for: Secure remote login to systems
- Why important: Encrypted communication

### Telnet
- **Port 23**
- Used for: Remote login (INSECURE - sends passwords in plain text)
- Security note: Use SSH instead!

### SMTP - Simple Mail Transfer Protocol
- **Port 25**
- Used for: Sending emails

### HTTP - HyperText Transfer Protocol
- **Port 80**
- Used for: Web browsing (insecure)

### HTTPS - HTTP Secure
- **Port 443**
- Used for: Secure web browsing (encrypted)

### MySQL Database
- **Port 3306**
- Used for: Database connections

### RDP - Remote Desktop Protocol
- **Port 3389**
- Used for: Windows remote desktop

## My Notes
- Always use encrypted protocols (HTTPS, SSH) instead of plain text (HTTP, Telnet)
- Closed ports = good security practice
- Open only necessary ports