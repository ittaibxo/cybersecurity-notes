# Networking Basics

## IP Addresses

### IPv4
- Format: `192.168.1.1`
- 4 numbers separated by dots
- Each number: 0-255

### Private IP Ranges
- `10.0.0.0` to `10.255.255.255`
- `172.16.0.0` to `172.31.255.255`
- `192.168.0.0` to `192.168.255.255`

**Why care?** These are used internally in homes/offices, not on the internet.

## Common Commands

### Check your IP address
```bash
# Mac/Linux
ifconfig

# Windows
ipconfig
```

### Ping a website
```bash
ping google.com
```
**What it does:** Tests if you can reach a server.

### Trace route
```bash
# Mac/Linux
traceroute google.com

# Windows
tracert google.com
```
**What it does:** Shows the path your data takes to reach a server.

## My Practice Notes
- Practiced pinging my router
- Tried traceroute to see internet hops