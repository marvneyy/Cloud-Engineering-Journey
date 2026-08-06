📅 Day 3 - OSI Model

Topics

• OSI Model
• Why OSI Model was Created
• The 7 Layers
• Functions of Each Layer
• OSI Model vs TCP/IP Model

---

1. What is the OSI Model?

Answer:

The OSI (Open Systems Interconnection) Model is a networking model that explains how data travels from one device to another over a network.

It divides the communication process into seven layers, making networking easier to understand, troubleshoot, and design.

Real-life Example:

When you send a WhatsApp message, the data passes through all seven OSI layers before reaching the receiver.

---

2. Why was the OSI Model created?

Answer:

The OSI Model was created to provide a standard way for different networking devices and technologies to communicate with each other.

Before the OSI Model, different companies used their own networking methods, making communication difficult.

Benefits:

• Makes networking easier to understand.
• Helps troubleshoot network problems.
• Ensures devices from different manufacturers can communicate.
• Provides a standard for network communication.

---

3. What are the 7 Layers of the OSI Model?

1. Physical Layer
2. Data Link Layer
3. Network Layer
4. Transport Layer
5. Session Layer
6. Presentation Layer
7. Application Layer

Easy Memory Trick:

Please Do Not Throw Sausage Pizza Away

P = Physical
D = Data Link
N = Network
T = Transport
S = Session
P = Presentation
A = Application

---

4. What does each layer do?

| Layer | Main Function | Device / Example |
|-------|---------------|------------------|
| 7. Application | Provides network services to applications | Browser, WhatsApp |
| 6. Presentation | Formats, encrypts, and compresses data | SSL/TLS, Encryption |
| 5. Session | Starts, manages, and ends communication sessions | Login Session |
| 4. Transport | Reliable delivery and error checking | TCP, UDP |
| 3. Network | Finds the best path using IP addresses | Router |
| 2. Data Link | Uses MAC addresses and transfers frames | Switch |
| 1. Physical | Transmits bits through cables or Wi-Fi | Cable, Hub, Wi-Fi |

---

5. OSI Model vs TCP/IP Model

OSI Model

• Has 7 layers.
• Mainly used for learning and understanding networking.
• Reference model.

TCP/IP Model

• Has 4 layers.
• Used in real-world networking and on the Internet.
• Practical networking model.

Comparison

OSI → Learning Model

TCP/IP → Real Internet Model

---

Summary

✅ OSI Model = Explains how data travels through a network.

✅ It has 7 layers.

✅ Layer 2 uses MAC addresses.

✅ Layer 3 uses IP addresses.

✅ Layer 4 provides reliable communication using TCP or UDP.

✅ The Internet mainly uses the TCP/IP Model.

---

🛠️ Hands-On Lab

Commands Used

ping 8.8.8.8

tracert 8.8.8.8

ipconfig

Results

• Verified network connectivity.
• Observed the route packets take to reach a destination.
• Reviewed local IP configuration.
