📅 Day 10 - CIDR notation,Subnet mask conversions,Masking math

Topics

• CIDR notation (/24, /25, /26)
• Subnet mask conversions
• Masking math

----------

1.CIDR notation (/24, /25, /26)

Answer:

CIDR (Classless Inter-Domain Routing)** is a short way to write a subnet mask. It tells the computer which part of an IP address is the Network and which part is the Host (Device).

Example

192.168.1.25/24

Here:

Network = 192.168.1
Host = 25

The /24 means the first 24 bits are used for the Network, and the remaining 8 bits are used for Hosts (devices).

---

Common CIDR Notations

/24 = 1 Network
Subnet Mask = 255.255.255.0

/25 = 2 Networks
Subnet Mask = 255.255.255.128

/26 = 4 Networks
Subnet Mask = 255.255.255.192
```

Easy Memory Trick

/24 → 1 Network
/25 → 2 Networks
/26 → 4 Networks
/27 → 8 Networks
```

As the CIDR number increases, the network is divided into more smaller networks, and each network can have fewer devices.

---

Example of /25

A normal `/24` network is:

192.168.1.0 - 192.168.1.255

When it becomes /25, it is divided into 2 networks.

192.168.1.0/25

0 -------------------127 | 128----------------255
      Network 1               Network 2
```

Examples:

192.168.1.20  → Network 1

192.168.1.50  → Network 1

192.168.1.150 → Network 2

192.168.1.200 → Network 2
```

If two devices are in the same network, they can communicate directly.

Example:

192.168.1.20/25
192.168.1.50/25

✔ Same Network
✔ No Router Needed
```

If two devices are in different networks, they need a Router.

Example:

192.168.1.20/25
192.168.1.150/25

✘ Different Networks
✔ Router Needed

---

Q) Why do we use CIDR?

Answer:

* Divide one big network into smaller networks.
* Reduce unnecessary network traffic.
* Improve network security.
* Make the network easier to manage.

---

Key Points to Remembe:

CIDR = Short way to write a subnet mask.

/24 = 255.255.255.0 = 1 Network

/25 = 255.255.255.128 = 2 Networks

/26 = 255.255.255.192 = 4 Networks

Same Network → Direct Communication

Different Network → Router Needed
```

🧠 Final Memory Trick

Think of a pizza 🍕

/24 = One whole pizza = 1 Network

/25 = Cut once = 2 Networks

/26 = Cut again = 4 Networks

/27 = Cut again = 8 Networks
```
