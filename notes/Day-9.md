📅 Day 9 - Private IP Addresses & NAT

Topics

• Private IP Addresses
• Public IP Addresses
• NAT (Network Address Translation)
• Masking Logic
• Binary Practice

---

1. What is a Private IP Address?

Answer:

A Private IP Address is an IP address used inside a local network such as a home, school, or office.

It cannot be accessed directly from the Internet.

Real-life Example:

Your laptop, phone, and smart TV are connected to your home Wi-Fi.

Each device has its own private IP address to communicate within the home network.

---

2. Why do we use Private IP Addresses?

Answer:

Private IP Addresses are used to:

• Save Public IP addresses.
• Allow communication inside a local network.
• Improve security because they are not directly accessible from the Internet.

Example:

A company has 500 computers.

Instead of buying 500 Public IPs, it uses Private IPs internally.

---

3. What is a Public IP Address?

Answer:

A Public IP Address is an IP address assigned by an Internet Service Provider (ISP).

It is visible on the Internet and allows communication with websites and online services.

Real-life Example:

Your home router has one Public IP address that connects your entire home network to the Internet.

---

4. What is NAT (Network Address Translation)?

Answer:

NAT is a process performed by a router that translates Private IP Addresses into a Public IP Address and vice versa.

It allows multiple devices to share a single Public IP Address.

Real-life Example:

Many devices in your home use Private IP Addresses.

When they access YouTube or Google, the router uses its Public IP to communicate with the Internet.

---

5. Why do we use NAT?

Answer:

NAT is used to:

• Save Public IPv4 addresses.
• Allow many devices to share one Public IP.
• Hide internal network addresses from the Internet.

---

6. What is Masking Logic?

Answer:

Masking Logic is the basic idea of using a subnet mask to separate the Network portion and Host portion of an IP address.

The subnet mask helps devices identify which part of an IP Address represents the network.

---

7. Binary Practice

Answer:

Practice converting these Private IP Addresses into binary by hand.

• 192.168.10.45
• 172.16.20.100
• 10.0.5.25
• 192.168.1.200
• 172.31.255.1

Do not use a calculator.

---

Summary

✅ Private IP = Used inside local networks.

✅ Public IP = Used on the Internet.

✅ NAT allows multiple Private IPs to share one Public IP.

✅ Masking Logic separates the Network ID and Host ID.

✅ Practice binary conversions by hand.

---

🛠️ Hands-On Lab

Task

• Convert five Private IP Addresses into binary by hand.
• Memorize the three Private IP ranges.

---

💻 GitHub Task

Create a file named:

private_ip_cheat_sheet.md

Include:

• Class A Private IP Range
• Class B Private IP Range
• Class C Private IP Range
• NAT explanation
• Binary conversion practice

---

🚀 Deliverable

• Complete Binary Conversion Practice.
• Create private_ip_cheat_sheet.md.
• Memorize all Private IP ranges.
