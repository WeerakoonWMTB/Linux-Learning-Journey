# Day 1 - Linux Networking Fundamentals

## Objective

Learn how Linux connects to a network and understand the basic networking components required for communication.

---

## Topics Covered

- Network Interface
- Interface Naming
- MAC Address
- IP Address
- Loopback Interface
- MTU
- Gateway
- DNS (Introduction)

---

## Commands Learned

```bash
ip link
ip -br addr
cat /sys/class/net/ens33/address
cat /sys/class/net/ens33/operstate
cat /sys/class/net/ens33/mtu
```

## Key Concepts

- ens33 is the network interface.
- MAC Address uniquely identifies a network interface.
- MTU defines the maximum packet size.
- Loopback Interface (lo) is used for internal communication.
- DNS translates domain names into IP addresses.

## Networking Connection

These concepts form the foundation of Ethernet, Switching, ARP, and TCP/IP networking.

## What I Learned

Today I learned how Linux identifies network interfaces, assigns MAC addresses, manages interface states, and uses MTU for packet transmission. I also understood the role of DNS in resolving domain names.

## Goal Achieved

✅ Understand Linux network interfaces and basic networking components.
