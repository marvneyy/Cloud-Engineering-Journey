📅 Day 4 - IPv4 & Binary Basics

Topics

• Binary Numbering System
• Binary to Decimal Conversion
• IPv4 Structure
• Why We Use IP Addresses
• Subnet Mask
• Decimal to Binary Conversion

---

1. What is the Binary Numbering System?

Answer:

The binary numbering system is a number system that uses only two digits:

0 and 1

Computers understand only binary because electronic circuits have only two states:

• OFF = 0
• ON = 1

Every piece of data inside a computer is stored and processed in binary.

Example:

Decimal 5 = Binary 00000101

---

2. How do you convert Binary to Decimal?

Answer:

Each binary digit (bit) has a value.

128 | 64 | 32 | 16 | 8 | 4 | 2 | 1

Example:

11000000

= 128 + 64

= 192

Another Example:

10101000

= 128 + 32 + 8

= 168

---

3. What is the IPv4 Structure?

Answer:

An IPv4 address is a 32-bit address divided into four parts called octets.

Each octet contains 8 bits.

Example:

192.168.1.10

192 | 168 | 1 | 10

Each number can range from:

0 to 255

Example in Binary:

11000000.10101000.00000001.00001010

---

4. Why do we use an IP Address?

Answer:

An IP address is a unique logical address assigned to every device on a network.

It helps devices find and communicate with each other.

Real-life Example:

Just like your house has an address for receiving letters, every device needs an IP address to send and receive data on a network.

Without an IP address, devices cannot communicate.

---

5. What is a Subnet Mask?

Answer:

A subnet mask tells us which part of an IP address represents the Network ID and which part represents the Host ID.

Example:

IP Address:

192.168.1.25

Subnet Mask:

255.255.255.0

Network ID:

192.168.1

Host ID:

25

The subnet mask helps devices determine whether another device is on the same network or a different network.

---

6. How do you convert Decimal to Binary?

Answer:

Find the decimal number in the value table.

128 | 64 | 32 | 16 | 8 | 4 | 2 | 1

Example:

Decimal:

172

Binary:

10101100

Because:

128 + 32 + 8 + 4 = 172

Another Example:

50

32 + 16 + 2

Binary:

00110010

---

Summary

✅ Binary uses only 0 and 1.

✅ Every IPv4 address has 32 bits.

✅ IPv4 has 4 octets.

✅ Every octet contains 8 bits.

✅ IP Address identifies a device on a network.

✅ Subnet Mask separates the Network ID and Host ID.

✅ Binary and Decimal conversion is a fundamental networking skill.

---

🛠️ Hands-On Lab

Practice Questions

Convert Binary to Decimal

11000000

10101000

00000001

00000001

Answer:

192.168.1.1

Convert Decimal to Binary

172.16.10.50

Answer:

10101100.00010000.00001010.00110010

Convert Decimal to Binary

10.0.0.25

Answer:

00001010.00000000.00000000.00011001
