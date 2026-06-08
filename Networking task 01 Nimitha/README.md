Networking Task 01: Understanding Your Network Environment

Objective

The purpose of this task is to understand the basic components of a network and identify the network configuration of my own device.

---

 Part A: Network Information

System Network Details

| Detail | Value |
|----------|----------|
| Hostname (Device Name) | E3 |
| IPv4 Address | 172.21.11.65 |
| MAC Address | 08-8F-C3-B5-7E-CC |
| Default Gateway | 172.21.11.1 |
| DNS Server | 172.21.3.100 |

---

Part B: Basic Networking Concepts

What is an IP Address?

An IP (Internet Protocol) Address is a unique numerical identifier assigned to a device connected to a network. It allows devices to communicate with each other and exchange data over a network.

What is a MAC Address?

A MAC (Media Access Control) Address is a unique hardware address assigned to a network interface card by the manufacturer. It is used to identify devices on a local network.

 What is a Default Gateway?

A Default Gateway is a networking device, usually a router, that connects a local network to other networks such as the internet. It acts as the exit point for network traffic.

What is DNS?

DNS (Domain Name System) translates human-readable domain names such as google.com into IP addresses that computers use to locate servers.

 Difference Between Public IP and Private IP

| Public IP | Private IP |
|------------|------------|
| Assigned by ISP | Assigned within a local network |
| Accessible from the internet | Not directly accessible from the internet |
| Must be globally unique | Can be reused in private networks |
| Used for internet communication | Used within local networks |

---

Part C: Network Diagram

 Network Topology

```text
Internet
    ↓
Router / Gateway (172.21.11.1)
    ↓
Device (E3)
IP Address: 172.21.11.65
```

![Network Diagram](Network_Diagram.png)

---

Part D: Network Connectivity Test

Commands Used

```cmd
ipconfig
ping google.com
tracert google.com
```

Results

Was the ping successful?

Yes. All 4 packets were sent and received successfully with 0% packet loss.

How many hops were shown?

8 hops were shown before reaching Google's server.

 What is the purpose of traceroute?

Traceroute is used to trace the path taken by packets from a source device to a destination server. It helps identify routing paths, delays, and network issues.

---

Screenshots

Network Configuration

[Network Configuration](network_config.png)

Ping Test

[Ping Test](ping_test.png)

Traceroute Test

[Traceroute](tracert.png)

---

Conclusion

This task helped me understand networking basics, identify my device's network configuration, and perform connectivity testing using ping and traceroute commands.