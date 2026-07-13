# OSI Model (Open Systems Interconnection Model)
The OSI (Open Systems Interconnection) Model is a 7-layer reference model that explains how data travels from one computer to another over a network.

![OSI Model](/Images/OSI_Model.png)

### **Layer-wise Explanation**

### 1. Physical Layer   
- Transmits raw bits (0s and 1s).
- Deals with cables, connectors, and signals.
- **Example:** Ethernet cable, Fiber optic cable.

### 2. Data Link Layer
- Transfers data between devices on the same network.
- Detects errors.
- Uses MAC addresses.
- **Example:** Switch.

### 3. Network Layer
- Routes data from source to destination.
- Uses IP addresses.
- **Example:** Router.

### 4. Transport Layer
- Ensures reliable and complete data delivery.
- Performs error checking and flow control.
- **Protocols:** TCP and UDP.

### 5. Session Layer
- Creates, maintains, and ends communication sessions.
- **Example:** Video conferencing, Login session.

### 6. Presentation Layer
- Converts data into a readable format.
- Performs encryption, decryption, and compression.
- **Example:** JPEG, MP3, SSL/TLS.

### 7. Application Layer
- Closest to the user.
- Provides services like web browsing, email, and file transfer.
- **Example:** HTTP, FTP, SMTP.

## Data Flow

**Sender:**     
Application → Presentation → Session → Transport → Network → Data Link → Physical

**Receiver:**       
Physical → Data Link → Network → Transport → Session → Presentation → Application

## Importance of the OSI Model
- Standardizes network communication.
- Makes troubleshooting easier.
- Helps different devices communicate.
- Simplifies learning and designing networks.