# Day 7 - Networking Basics (Theory)

## What I learned

Today I learned how networking works in Linux and how to diagnose connectivity issues using basic commands.

------------------------------------------------------------------------

## What is networking in Linux

Networking allows a system to communicate with other systems over a network.

Key elements:
- IP address → identifies a device
- DNS → translates domain names to IP addresses
- Ports → communication endpoints

------------------------------------------------------------------------

## Network interfaces and IP addresses

Command:
```bash
ip a
```

- displays all network interfaces
- shows assigned IP addresses
- identifies active/inactive connections

Key fields:
- `inet` → IPv4 address
- `lo` → loopback (127.0.0.1)

------------------------------------------------------------------------

## Connectivity testing (ICMP)

Command:
```bash
ping google.com
```

- tests if a host is reachable
- verifies DNS resolution
- measures latency

Limited test:
```bash
ping -c 4 google.com
```

- sends a fixed number of packets

------------------------------------------------------------------------

## Data retrieval (HTTP requests)

Command:
```bash
curl example.com
```

- fetches raw HTML from a website
- useful for testing web services

Public IP check:
```bash
curl ifconfig.me
```

- returns your external IP address

------------------------------------------------------------------------

## Ports and connections

Command:
```bash
ss -tuln
```

- lists listening ports and active connections
- shows which services are running

Flags:
- `t` → TCP
- `u` → UDP
- `l` → listening
- `n` → numeric (no DNS)

------------------------------------------------------------------------

## Basic troubleshooting logic

1. Check IP:
```bash
ip a
```

2. Test connection:
```bash
ping google.com
```

3. Test HTTP:
```bash
curl example.com
```

4. Check ports:
```bash
ss -tuln
```

------------------------------------------------------------------------

## Summary

Day 7 introduced networking fundamentals in Linux, including IP addressing, connectivity testing, data retrieval, and port inspection.
