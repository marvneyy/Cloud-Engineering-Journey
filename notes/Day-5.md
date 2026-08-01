📅 Day 5 - Subnetting Basics

Topics

• Subnetting
• Why We Use Subnetting
• How Subnetting Works
• Network ID
• Host ID
• CIDR Notation
• Default Subnet Masks

---

1. What is Subnetting?

Answer:

Subnetting is the process of dividing one large network into smaller networks called subnets.

It helps organize devices and makes network management easier.

Real-life Example:

Imagine a school with one large building.

Instead of putting every student in one classroom, the school divides them into separate classrooms.

Each classroom is like a subnet.

---

2. Why do we use Subnetting?

Answer:

Subnetting is used to:

• Organize large networks.
• Reduce unnecessary network traffic.
• Improve network performance.
• Increase security.
• Make troubleshooting easier.

Example:

Instead of putting 500 computers in one network, we can divide them into smaller networks for different departments.

---

3. How does Subnetting work?

Answer:

Subnetting works by dividing an IP address into two parts:

• Network ID
• Host ID

The subnet mask or CIDR notation tells us where the Network ID ends and where the Host ID begins.

Example:

IP Address:

192.168.1.25

Subnet Mask:

255.255.255.0

Network ID:

192.168.1

Host ID:

25

---

4. What is a Network ID?

Answer:

The Network ID identifies the network a device belongs to.

All devices on the same network have the same Network ID.

Example:

IP Address:

192.168.1.50

Subnet Mask:

255.255.255.0

Network ID:

192.168.1

Every device beginning with 192.168.1 belongs to the same network.

---

5. What is a Host ID?

Answer:

The Host ID identifies an individual device within a network.

Every device must have a unique Host ID.

Example:

192.168.1.10

192.168.1.20

192.168.1.30

Network ID:

192.168.1

Host IDs:

10

20

30

---

6. What is CIDR?

Answer:

CIDR (Classless Inter-Domain Routing) is a shorter way of writing a subnet mask.

Examples:

/8 = 255.0.0.0

/16 = 255.255.0.0

/24 = 255.255.255.0

The number after "/" tells us how many bits belong to the Network ID.

Example:

192.168.1.25/24

Network ID:

192.168.1

Host ID:

25

---

7. Default Subnet Masks

Class A

Subnet Mask:

255.0.0.0

CIDR:

/8

Network:

First 8 bits

Host:

Last 24 bits

---

Class B

Subnet Mask:

255.255.0.0

CIDR:

/16

Network:

First 16 bits

Host:

Last 16 bits

---

Class C

Subnet Mask:

255.255.255.0

CIDR:

/24

Network:

First 24 bits

Host:

Last 8 bits

---

Summary

✅ Subnetting divides one large network into smaller networks.

✅ Network ID identifies the network.

✅ Host ID identifies the device.

✅ CIDR is a shorter way to write a subnet mask.

✅ /8 = 255.0.0.0

✅ /16 = 255.255.0.0

✅ /24 = 255.255.255.0

---

🛠️ Hands-On Lab

Identify the Network ID and Host ID.

1.

IP Address:

192.168.1.50/24

Network ID:

192.168.1

Host ID:

50

---

2.

IP Address:

172.16.10.50/16

Network ID:

172.16

Host ID:

10.50

---

3.

IP Address:

10.20.30.40/8

Network ID:

10

Host ID:

20.30.40
