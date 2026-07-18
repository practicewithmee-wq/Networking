# TCP/IP Model
The TCP/IP model is a networking model that explains how data is transmitted over the internet. It has 4 layers, each with a specific function.

## Why was TCP/IP chosen Over the OSI Model
TCP/IP is preferred over the OSI model because it is simpler, practical, and widely implemented in real-world networks and the Internet. Unlike OSI, which is mostly theoretical, TCP/IP is protocol-driven and focuses on actual communication needs.

![vs](/Images/tcp-ip-model-vs-osi.png)

- **Simpler Structure:** TCP/IP has only 4 layers, compared to 7 in OSI, making it easier to implement and understand in real systems.
- **Protocol-Driven Design:** TCP/IP was designed based on working protocols, while OSI is mostly a theoretical framework.
- **Flexibility and Robustness:** TCP/IP adapts well to different hardware and networks and includes error handling, routing, and congestion control.
- **Open Standard:** TCP/IP is open, free to use, and not controlled by any single organization, which helped it gain universal acceptance.
- **Actual Use vs Conceptual Model:** OSI is great for learning and design principles, but TCP/IP is the model actually used in real-world networking.

## Layers of TCP/IP Model

### **1. Application Layer**
This is the top layer of the TCP/IP model, where applications like web browsers, email clients, and file-sharing tools interact with the network.

![AL](/Images/AL.png)

- Acts as a bridge between user applications and lower network layers.
- Supports protocols such as HTTP, FTP, SMTP, and DNS.
- Handles data formatting so information is correctly understood by both sender and receiver.
- Provides encryption for secure communication.
- Manages sessions to track ongoing connections.

### Common Protocols
- HTTP – Web browsing
- HTTPS – Secure web browsing
- FTP – File transfer
- SMTP – Sending emails
- POP3 / IMAP – Receiving emails
- DNS – Converts domain names into IP addresses
- SSH – Secure remote login


### Example

When you open www.google.com, your browser uses:

- DNS to find Google's IP address.
- HTTP/HTTPS to request the webpage.

### **2. Transport Layer**
The Transport Layer provides end-to-end communication between devices. It ensures data is delivered correctly and efficiently.

![TL](/Images/TL.png)

- Breaks large messages into packets and reassembles them at the destination.
- TCP checks for errors, resends lost data, and ensures correct order.
- UDP provides low-latency, connectionless delivery without error checking.
- Prevents the receiver from being overwhelmed by regulating data flow.
- Uses port numbers to allow multiple applications to share the network simultaneously.

### TCP (Transmission Control Protocol)
- Connection-oriented.
- Reliable communication.
- Error checking.
- Data arrives in the correct order.
- Used for websites, emails, and file downloads.
### UDP (User Datagram Protocol)
- Connectionless.
- Faster than TCP.
- No guarantee of delivery.
- Used for online gaming, video streaming, and voice calls.

![transport layer](/Images/Transport-Layer-Protocols.jpg)

### **3. Internet Layer**
The Internet Layer is responsible for logical addressing and routing. It determines the best path for data to travel from source to destination.

![il](/Images/internet_layer.png)

- Assigns IP addresses to identify source and destination devices.
- Determines the best path for data to travel across networks.
- Breaks large packets into smaller ones for transmission and reassembles them at the destination.
- Primarily uses IP (Internet Protocol), along with supporting protocols like ICMP for error reporting and ARP for address resolution.

### Common Protocols
- IP (Internet Protocol) – Provides logical addressing.
- ICMP – Error reporting (used by Ping).
- ARP – Converts IP addresses to MAC addresses.
- IGMP – Manages multicast communication.



### Example

When data travels from Delhi to Mumbai, the Internet Layer chooses the best route through routers.


### **4. Network Access (Link) Layer**

The Network Access Layer sends and receives data over the physical network.

![na](/Images/network%20access.png)

### Responsibilities
- Converts packets into frames.
- Uses MAC addresses.
- Detects transmission errors.
- Controls access to the network medium.
- Sends bits over cables or wireless signals.
### Technologies / Protocols
- Ethernet
- Wi-Fi (IEEE 802.11)
- PPP (Point-to-Point Protocol)
- Frame Relay
### Devices
- Network Interface Card (NIC)
- Switch
- Hub

![netacc](/Images/network%20access%20link.png)

### Example

When your laptop sends data through Wi-Fi to a router, this layer handles the transmission.


# Advantages and Disadvantages of TCP/IP

### **Advantages of TCP/IP**

- Global Standard – Used worldwide for Internet communication.
- Reliable Data Transfer – TCP ensures data reaches the destination correctly.
- Scalable – Supports networks of all sizes, from small LANs to the Internet.
- Platform Independent – Works with different operating systems and devices.
- Supports Routing – IP enables data to travel through multiple networks.
- Flexible – Supports both wired and wireless networks.
- Open Standard – Freely available and supported by many vendors.
- Supports Multiple Applications – Works with web browsing, email, file transfer, streaming, and more.

### **Disadvantages of TCP/IP**

- Complex Configuration – Can be difficult to configure for beginners.
- No Clear Layer Separation – Some layers have overlapping functions.
- Security Not Built-in – Basic TCP/IP does not provide encryption or authentication.
- Overhead – TCP headers and acknowledgments can reduce performance.
- Congestion Issues – Heavy traffic can slow down communication.
- IP Is Connectionless – IP alone does not guarantee packet delivery or order.
- Troubleshooting Can Be Difficult – Problems across multiple layers may be hard to identify.
- Performance Depends on Network Quality – Slow or unstable networks affect communication speed.