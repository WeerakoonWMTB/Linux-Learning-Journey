# Day 2 - Network Connectivity & ICMP

## Objective

Understand how Linux tests network connectivity using ICMP and learn how to troubleshoot basic network communication.

---

## Topics Covered

- ICMP
- Ping
- TTL
- Latency
- Packet Loss
- Tracepath

---

## Commands Learned

```bash
ping -c 4 8.8.8.8
ping -c 4 google.com
ping -c 4 localhost
tracepath google.com
hostname -I
```

## Key Concepts

- ICMP is used for network diagnostics.
- Ping sends ICMP Echo Requests.
- TTL limits packet lifetime.
- Latency measures round-trip time.
- Packet Loss indicates network reliability.

## Networking Connection

These concepts are essential for troubleshooting enterprise networks and understanding packet delivery across routers.

## Cloud Connection

Cloud Engineers use ping and tracepath to verify EC2 instance connectivity and diagnose routing issues.

## Security Connection

Security teams use ICMP for connectivity testing while understanding that some firewalls block ICMP traffic.

## What I Learned

Today I learned how Linux checks connectivity using ICMP, how to interpret ping results, and how latency, TTL, and packet loss affect network communication.

## Goal Achieved

✅ Understand network connectivity testing and basic troubleshooting using Linux.
