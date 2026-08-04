📅 Day 8 - Broadcast Domain, NAT & Binary

Topics

• Broadcast Domain
• Why We Use Broadcast Domains
• NAT (Network Address Translation)
• Private IP Address Ranges
• Binary Conversion (IP to Binary)

---

1. What is a Broadcast Domain?

Answer:

A Broadcast Domain is a group of devices that receive the same broadcast message.

When one device sends a broadcast, every device in the same broadcast domain receives it.

Real-life Example:

Imagine a classroom.

One student shouts,

"Who has my notebook?"

Everyone in the classroom hears it.

A Broadcast Domain works the same way.

---

2. Why do we use Broadcast Domains?

Answer:

Broadcast Domains help organize networks and reduce unnecessary broadcast traffic.

Smaller broadcast domains improve:

• Network performance.
• Network security.
• Less network congestion.

Example:

Instead of putting 2,000 computers in one network,

divide them into smaller networks.

This reduces unnecessary broadcasts.

---

3. What is NAT (Network Address Translation)?

Answer:

NAT is a process where a router converts private IP addresses into one public IP address.

It allows many devices to share a single public IP address when accessing the Internet.

Real-life Example:

A family has one home address.

The postman delivers mail to that address,

and each family member receives their own mail inside the house.

The router works the same way.

---

4. Why do we use NAT?

Answer:

NAT is used to:

• Save IPv4 addresses.
• Allow multiple devices to share one Internet connection.
• Hide private IP addresses from the public Internet.
• Improve basic security.

Example:

Laptop → 192.168.1.10

Phone → 192.168.1.20

TV → 192.168.1.30

↓

Router (NAT)

↓

Public IP → Internet

---

5. What is Binary Conversion?

Answer:

Binary Conversion means converting decimal numbers into binary (0s and 1s).

Computers understand only binary.

Example:

192

↓

11000000

168

↓

10101000

---

6. Why do we use Binary?

Answer:

Computers use electricity.

Electricity has only two states:

ON = 1

OFF = 0

Therefore, computers understand only binary.

---

7. Private IP Address Ranges

Answer:

Class A

10.0.0.0 → 10.255.255.255

Class B

172.16.0.0 → 172.31.255.255

Class C

192.168.0.0 → 192.168.255.255

Memory Trick:

Private stays inside.

Public goes to the Internet.

---

Summary

✅ Broadcast Domain = One broadcast reaches all devices in the same network.

✅ Smaller Broadcast Domains improve performance and security.

✅ NAT allows many private IP addresses to share one public IP.

✅ NAT helps save IPv4 addresses.

✅ Computers understand only binary (0 and 1).

✅ Private IP addresses are used inside home and office networks.

---

🛠️ Hands-On Lab

Tasks

Write these 5 IP addresses and convert them to binary by hand:

192.168.1.10

172.16.50.20

10.20.30.40

192.168.10.5

172.20.100.1

Write the private IP ranges:

Class A → 10.0.0.0 – 10.255.255.255

Class B → 172.16.0.0 – 172.31.255.255

Class C → 192.168.0.0 – 192.168.255.255

---

Results

• Understood what a Broadcast Domain is.

• Learned why large Broadcast Domains reduce performance and security.

• Learned how NAT allows multiple devices to share one public IP.

• Memorized the three private IPv4 address ranges.

• Practiced converting IPv4 addresses into binary by hand.
