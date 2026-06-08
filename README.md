cyber security intership task1 report

intern: Unnati sonawane

 Objective
Understand the basic components of a network and identify the network configuration of my own device.

Part A: Network Information

| Field | Value |
| Hostname (Device Name) | DESKTOP-USER 
| IPv4 Address | 192.168.1.5
| MAC Address | A4:C3:F0:XX:XX:XX
| Default Gateway | 192.168.1.1 
| DNS Server | 8.8.8.8 (Google DNS) 

Part B: Basic Networking Concepts

What is an IP Address?
An IP address (Internet Protocol address) is a unique numerical label assigned to every device connected to a network. It acts like a home address — it tells the network where to send data. Example: `192.168.1.5`

What is a MAC Address?
A MAC (Media Access Control) address is a unique hardware identifier permanently assigned to a network interface card (NIC) by the manufacturer. Unlike an IP address, it doesn't change. It looks like: `A4:C3:F0:12:34:56`

 what is a Default Gateway?
A default gateway is the device (usually a router) that connects your local network to the internet. When your device wants to send data outside the local network, it first sends it to the default gateway. Example: `192.168.1.1`

What is DNS?
DNS (Domain Name System) is like the phone book of the internet. It translates human-readable domain names (like `google.com`) into IP addresses (like `142.250.80.46`) that computers use to communicate.

Difference Between Public IP and Private IP
| Feature | Private IP | Public IP |

| Used in | Local network (home/office) | Internet |
| Example | 192.168.1.5 | 103.21.244.0 |
| Assigned by | Router (DHCP) | Internet Service Provider (ISP) |
| Visible on internet? | No | Yes |


 Part C: Network Diagram

```
         [ INTERNET ]
              |
         [ ROUTER ]
         192.168.1.1
              |
    __________|__________
    |                   |
[My Device]         [Other Devices]
192.168.1.5         192.168.1.x


Part D: Network Connectivity Test

Commands Run (Windows):
```
ipconfig
ping google.com
tracert google.com
```

 Answers:
1. Was the ping successful?Yes — received replies from google.com with ~10ms response time.
2. How many hops were shown? Approximately 10–15 hops shown in tracert.
3. What is the purpose of traceroute? Traceroute shows the path data takes from your device to the destination, listing every router (hop) along the way. It's useful for diagnosing where a connection slows down or fails.
racert
- `network_diagram.png` — Visual network diagram
