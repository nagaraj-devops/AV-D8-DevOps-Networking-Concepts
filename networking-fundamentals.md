🌐 Networking Fundamentals
1. IP Address (Internet Protocol Address)

- An IP address is a unique identifier assigned to each device on a network.

- Two main versions:

  - IPv4 → 32-bit (e.g., 192.168.1.1) → about 4.3 billion addresses.

  - IPv6 → 128-bit (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334) → designed to replace IPv4 due to address shortage.

📌 Example: If your laptop connects to WiFi, it gets an IP (say 192.168.1.10) so the router knows how to send/receive data to it.

2. CIDR (Classless Inter-Domain Routing)

- CIDR is a way to define IP ranges more efficiently using a suffix (called a prefix length).

- Format: <IP>/<prefix>

  -  Example: 192.168.1.0/24 → means first 24 bits are fixed (network part), last 8 bits are available for hosts.

  - This gives 2^8 = 256 addresses (from 192.168.1.0 to 192.168.1.255).

👉 /24 means 255.255.255.0 subnet mask.
👉 /16 means 255.255.0.0 (bigger network).

3. Subnet

- A subnet (subnetwork) is a smaller network created from a larger network by dividing IP ranges.
  
- Helps organize and optimize traffic.
  
- Example:

  - Main network: 192.168.0.0/16 (65,536 addresses).

  - Can be split into:

  - 192.168.1.0/24

  - 192.168.2.0/24

Each with 256 addresses.

📌 Why? → Improves security, reduces congestion, and allows efficient IP allocation.

4. Ports

A port is a number that identifies a specific service/application on a device.

Think of an IP address like a building’s address, and ports like the doors to different rooms.

🔑 Common Ports:

80 → HTTP (websites)

443 → HTTPS (secure websites)

22 → SSH (remote login)

25 → SMTP (email sending)

3306 → MySQL database

8080 → Alternate web service port

📌 A device can have one IP but many services running on different ports.

5. Basics of Networking

LAN (Local Area Network): Small, local (e.g., home WiFi).

WAN (Wide Area Network): Larger, across cities/countries (e.g., Internet).

Router: Connects different networks (e.g., your home to the Internet).

Switch: Connects multiple devices inside the same network.

Firewall: Controls traffic based on rules (security).

DNS (Domain Name System): Translates domain names → IP addresses (e.g., google.com → 142.250.182.206).

⚡ Quick Analogy:

IP → House address

Subnet → Neighborhood inside a city

CIDR → Postal code system defining range of houses

Port → Door numbers in the house

Router → The post office routing letters

DNS → Phonebook for finding addresses
