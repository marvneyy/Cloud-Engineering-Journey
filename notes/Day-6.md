📅 Day 6 - Ping & ICMP

Topics

• Ping
• Why We Use Ping
• ICMP
• Connectivity Troubleshooting
• Ping & ICMP Troubleshooting

---

1. What is Ping?

Answer:

Ping is a network tool used to check whether another device is reachable over a network.

It sends a small message to the destination device and waits for a reply.

Real-life Example:

Imagine you call your friend and ask,
"Are you there?"

If your friend replies,
"I'm here."

The connection is working.

Ping works in the same way.

---

2. Why do we use Ping?

Answer:

Ping is used to:

• Check if a device is reachable.
• Test network connectivity.
• Measure response time (latency).
• Help identify network problems.

Example:

You cannot open a website.

You ping the server.

If you receive replies, the network connection is working.

If you don't receive replies, there may be a network issue.

---

3. What is ICMP?

Answer:

ICMP (Internet Control Message Protocol) is a network protocol used to send error messages and network status information.

Ping uses ICMP to communicate.

Without ICMP, the ping command would not work.

Example:

PC → ICMP Echo Request → Server

Server → ICMP Echo Reply → PC

---

4. What is Connectivity Troubleshooting?

Answer:

Connectivity troubleshooting is the process of finding and fixing network connection problems.

It helps identify where communication is failing.

Example:

PC → Switch → Router → Internet → Google

If the PC cannot reach Google, check each device one by one to find where the problem exists.

---

5. Ping & ICMP Troubleshooting

Answer:

When ping fails, check the following:

• Is the network cable connected?
• Is Wi-Fi connected?
• Does the device have a valid IP address?
• Is the default gateway correct?
• Is the destination device powered on?
• Is a firewall blocking ICMP?
• Is the Internet connection working?

Common Ping Results

Reply from...

✅ The destination is reachable.

Request timed out

❌ No reply was received.

Destination host unreachable

❌ The destination cannot be reached.

---

Summary

✅ Ping checks whether a device is reachable.

✅ Ping uses ICMP.

✅ ICMP sends network status and error messages.

✅ Ping helps troubleshoot connectivity problems.

✅ Always check cables, IP address, gateway, and Internet connection when troubleshooting.

---

🛠️ Hands-On Lab

Commands Used

ipconfig

ping 127.0.0.1

ping <Default Gateway>

ping 8.8.8.8

ping google.com

Results

• Verified local IP configuration.
• Tested the local network (loopback).
• Tested connectivity to the router.
• Tested Internet connectivity.
• Tested DNS name resolution.
