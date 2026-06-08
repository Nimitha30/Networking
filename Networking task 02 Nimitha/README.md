Networking Task 02: Network Devices & IP Addressing

Objective

The purpose of this task is to understand common network devices, IP addressing concepts, and how data travels within a network.

---

Part A: Network Devices Research

Router

Purpose
Connects different networks and provides internet access.

How it Works
Forwards packets based on IP addresses.

Real-World Usage
Home Wi-Fi routers.

---

Switch

Purpose
Connects devices within a LAN.

How it Works
Uses MAC addresses to forward data to the correct device.

Real-World Usage
Office and college networks.

---

## Hub

### Purpose
Connects multiple devices.

How it Works
Broadcasts incoming data to all connected devices.

Real-World Usage
Older Ethernet networks.

---

 Access Point

Purpose
Provides wireless network access.

How it Works
Connects wireless devices to a wired network.

Real-World Usage
Wi-Fi hotspots in homes and colleges.

---

Firewall

Purpose
Protects networks from unauthorized access.

How it Works
Filters incoming and outgoing traffic based on security rules.

Real-World Usage
Windows Firewall, enterprise firewalls.

---

Modem

Purpose
Connects a network to an ISP.

How it Works
Converts digital signals for transmission over communication lines.

Real-World Usage
Broadband internet connections.

---

Part B: IP Address Classification

| IP Address | Type | Reason |
|------------|------|---------|
| 192.168.1.10 | Private | Reserved private range |
| 10.0.0.5 | Private | Reserved private range |
| 172.16.5.20 | Private | Reserved private range |
| 8.8.8.8 | Public | Google DNS |
| 1.1.1.1 | Public | Cloudflare DNS |
| 192.168.100.1 | Private | Reserved private range |

---

Part C: Understanding Your Network

Network Information

| Item | Value |
|--------|--------|
| IPv4 Address | 172.21.11.65 |
| Default Gateway | 172.21.11.1 |
| DNS Server | 172.21.3.100 |

Which IP range does your device belong to?

My device belongs to the 172.16.0.0 – 172.31.255.255 private IP range.

Is it Public or Private?

It is a private IP address.

What role does your router play in your network?

The router acts as a gateway between my local network and the internet.

What would happen if the DNS server stopped working?

Domain names would not resolve into IP addresses, making websites inaccessible by name.

---

Part D: Network Communication Flow

Network Diagram

```text
Your Device (172.21.11.65)
        ↓
Router (172.21.11.1)
        ↓
DNS Server (172.21.3.100)
        ↓
Google Server (142.251.220.46)
        ↓
Response Back to Device

Communication Flow

1. User enters www.google.com in a browser.
2. The request is sent to the router.
3. The router forwards the DNS query to the DNS server.
4. DNS returns Google's IP address.
5. The device communicates with Google's server.
6. Google sends the requested webpage back to the device.

---

Part E: Practical Command Exercise

Commands Used

```cmd
ipconfig /all
nslookup google.com
ping google.com
```

What IP address did DNS return for Google?

IPv4: 142.251.220.46

IPv6: 2404:6800:4009:808::200e

Was the ping successful?

Yes.

- Packets Sent: 4
- Packets Received: 4
- Packet Loss: 0%

How many hops were shown?

8 hops.

Why is DNS important before communication begins?

DNS translates domain names into IP addresses so devices can locate and communicate with servers.

---

Screenshots

Network Configuration

[Network Configuration](network_config.png)

DNS Lookup

[DNS Lookup](nslookup.png)

Ping Test

[Ping Test](ping_test.png)

Traceroute

[Traceroute](tracert.png)

---

Conclusion

This task improved my understanding of networking devices, IP addressing, DNS resolution, and network communication using practical networking commands.