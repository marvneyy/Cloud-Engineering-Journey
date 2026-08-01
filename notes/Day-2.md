📅 Day 2 - Switch, Router & MAC Address

Topics

• Switch
• Router
• MAC Address
• Switch vs Hub
• Router vs Switch
• Layer 2 vs Layer 3
• MAC vs IP
• ARP

────────────────────────────

1. What is a Switch?

Answer:
A switch is a networking device that connects multiple devices within the same Local Area Network (LAN). It allows devices to communicate with each other efficiently.

Real-life Example:

Laptop
   │
Phone ─── Switch ─── Printer
   │
PC

All the devices are connected to the same switch and can share files, print documents, and communicate with each other.

────────────────────────────

2. Why do we use a Switch?

Answer:
A switch helps connect multiple devices in a LAN and sends data only to the intended device. This makes the network faster and reduces unnecessary traffic.

Example:
In an office, one switch can connect computers, printers, and IP phones so they can communicate efficiently.

────────────────────────────

3. How does a Switch work?

Answer:
A switch learns the MAC address of every connected device. It stores these addresses in a MAC Address Table. When data arrives, the switch checks the destination MAC address and forwards the data to the correct device.

────────────────────────────

4. How does a Switch send data?

Answer:
When Device A sends data to Device B:

Device A → Switch → Device B

The switch checks the destination MAC address and sends the data only to Device B. Other devices do not receive that data.

────────────────────────────

5. Switch vs Hub (Basics)

Switch

• Sends data only to the correct device.
• Faster and more efficient.
• Uses MAC addresses.

Hub

• Sends data to every connected device.
• Slower because every device receives the data.
• Does not use MAC addresses.

────────────────────────────

6. What is a Router? Router vs Switch

Answer:
A router connects different networks together, such as your home network and the Internet.

Example:

Home Network → Router → Internet

Difference:

Switch
• Connects devices within the same network.
• Uses MAC addresses.
• Works at Layer 2.

Router
• Connects different networks.
• Uses IP addresses.
• Works at Layer 3.

────────────────────────────

7. MAC Address vs IP Address

MAC Address

• Physical address of a device.
• Assigned by the manufacturer.
• Usually does not change.
• Used inside a local network.

Example:
00:1A:2B:3C:4D:5E

IP Address

• Logical address of a device.
• Assigned by a router or network administrator.
• Can change.
• Used for communication between networks.

Example:
192.168.1.10

────────────────────────────

8. Layer 2 vs Layer 3

Layer 2 (Data Link Layer)

• Uses MAC addresses.
• Switches operate here.
• Communication happens within the same LAN.

Layer 3 (Network Layer)

• Uses IP addresses.
• Routers operate here.
• Communication happens between different networks.

────────────────────────────

9. What is ARP?

Answer:
ARP (Address Resolution Protocol) is used to find the MAC address of a device when its IP address is known.

Example:

PC wants to send data to 192.168.1.20.

The PC first uses ARP to find the MAC address of 192.168.1.20.

Once it gets the MAC address, it sends the data through the switch.

────────────────────────────

Summary

✅ Switch = Connects devices in the same LAN

✅ Router = Connects different networks

✅ MAC Address = Physical address

✅ IP Address = Logical address

✅ Layer 2 = MAC Address

✅ Layer 3 = IP Address

✅ ARP = Finds MAC address using an IP address

────────────────────────────

🛠️ Hands-On Lab

Commands Used

ipconfig /all

arp -a

getmac

Results

• Checked my IP configuration.
• Viewed my device's MAC address.
• Displayed the ARP table.
