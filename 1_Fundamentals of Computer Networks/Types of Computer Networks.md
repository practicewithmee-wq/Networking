# Computer Networking

## Types of Computer Networks

A computer network is a group of two or more independent computers and devices connected to share data, resources, and services.    
These connections can be established using wired media or wireless technologies.    

**Types of Computer Networks are classified based on several factors:**
1. Geographical area
2. Transmission medium
3. Ownership and access control

## Classification Based on Geographical Area
Categorizing computer networks according to the physical distance or area they cover, ranging from small personal spaces to large global regions.   
Based on geographical area, computer networks are mainly divided into five types:

- Personal Area Netwotk (PAN)   
This connects personal devices within a very short range around a single user.  

    * Coverage Range: 1–10 meters
    * Key Technologies: Bluetooth, NFC, Infrared
    * Real-World Example: Smartphone connected to wireless earbuds
    * When It Is Used: For short-range communication between personal devices

![image](/Images/Personal_Area_Network.png)

- Local Area Network (LAN)  
This connects computers and devices within a limited area such as a home, office, or building.

    * Coverage Range: One room, building, or small campus
    * Key Technologies: Ethernet, Wi-Fi
    * Real-World Example: Home or office Wi-Fi network
    * When It Is Used: For fast and secure communication within a local location

![LAN image](/Images/Local_Area_Network.png)

- Metropolitan Area Network (MAN)   
A MAN connects multiple networks within a city or metropolitan region.

    * Coverage Range: City or large town
    * Key Technologies: Fiber Optics, Microwave, Metro Ethernet
    * Real-World Example: City-wide ISP network
    * When It Is Used: To provide high-speed connectivity across a city

![Man image](/Images/MAN.png)

- Wide Area Network (WAN)
A WAN connects networks over large geographical areas such as countries or continents.

    * Coverage Range: Country, continent, or global
    * Key Technologies: Leased lines, Satellite links, Internet
    * Real-World Example: The Internet
    * When It Is Used: To enable long-distance and global communication

![Wan image](/Images/WAN.png)

- Campus Area Network (CAN)
A CAN connects multiple LANs within a campus or a group of nearby buildings.
    
    * Coverage Range: University or corporate campus
    * Key Technologies: Ethernet, Fiber Optics
    * Real-World Example: College or corporate campus network
    * When It Is Used: To interconnect LANs across a campus under one organization

![Can image](/Images/CAN.png)

## Classification Based on Transmission Medium

Computer networks can also be classified based on how data is transmitted between devices. Transmission technology refers to the method or medium used to send data signals from one device to another.

1. **Broadcast Network**    
This used a shared communication medium among all connected devices.

- Data transmitted by one node is received by all other nodes in the network.
- Each data packet contains a destination address, and only the intended device processes it.
- Communication follows a one-to-many model.    
- No dedicated physical path exists between sender and receiver.    

**Examples:**           

- Ethernet (bus-based)
- Wireless LAN (Wi-Fi)

2. **Point-to-Point Network**   
This uses dedicated links between communicating devices.

- Data is transmitted directly from one node to another.
- Communication follows a one-to-one model.
- Data may pass through intermediate devices (routers or switches).
- Requires routing algorithms to determine the best path.

**Examples:**

- Internet
- Leased line networks
- Telephone networks

## Classification Based on Ownership and Access Control
This classification focuses on administrative control and accessibility, rather than transmission medium, size, or technology. Based on transmission technology, computer networks are mainly divided into three types:

### 1. **Private Network**
A Private Network is a network that is restricted to authorized users only. It is more secure because access is controlled.     
This type of network is owned and managed by an individual, organization, or institution

- Access is restricted to authorized users only
- Requires authentication such as usernames, passwords, VPNs, or access tokens
- Used mainly for internal communication
- Offers higher security, privacy, and control
- Commonly used in homes, schools, offices, and organizations.

### **Examples:**

- Corporate intranet
- Office or Company LAN
- Private cloud network
- School computer network
- Bank's internal network

### 2. **Public Network**   
A Public Network is a network that is open for anyone to access. It is not trusted because many unknown users can connect to it.    
This type of network is owned by service providers or government authorities   


- Open to the public.
- Requires little or no authorization to connect
- Less secure than a private network.
- Used by many unknown users.
- Can operate over both wired and wireless media
- Use a VPN and avoid sharing sensitive information on public networks.

### **Examples:**

- Internet
- Public Wi-Fi networks
- Mobile cellular networks

### 3. **Hybrid Network**   
This type of network is combination of private and public networks

- Some parts of the network are restricted, while others are publicly accessible
- Allows organizations to maintain internal security while providing external connectivity
- Common in modern enterprise and cloud-based systems

### **Examples:**

- Corporate network connected to the Internet
- Enterprise cloud networks
- Online banking systems

## Internetwork
An internetwork is a collection of two or more independent networks connected together to function as a single logical network.

- It enables communication between devices across different networks.
- The Internet itself is the largest example of an internetwork.
- Consists of multiple networks, not just individual computers.
- Uses networking devices to interconnect networks
 
![intranet](/Images/intranet.png)

### 1. **Intranet**     
An Intranet is a private network used within an organization to share information, files, and resources among authorized employees.

- Private network used inside an organization.
- Accessible only to authorized users.
- Helps employees communicate and share information.
- Provides secure access to company resources.
- Uses internet technologies such as web browsers and websites.

### Uses of Intranet
- Sharing company documents and files.
- Internal communication between employees.
- Announcements and notices.
- Managing employee records and attendance.
- Team collaboration and project management.

### Examples
- A company's employee portal.
- A school's internal website for teachers and staff.
- A hospital's internal information system.
- A bank's internal employee network.

### 2. **Extranet** 
An Extranet is a private network that allows authorized external users (such as customers, suppliers, or business partners) to securely access selected information from an organization's intranet.

- Extends an intranet to authorized external users.
- Secure and password-protected access.
- Used for communication and collaboration with outside organizations.
- Shares only selected information, not the entire internal network.
- Improves business efficiency and data sharing.

### Uses of Extranet
- Sharing information with suppliers and vendors.
- Customer portals for orders and support.
- Collaboration with business partners.
- Tracking orders and deliveries.
- Secure document sharing between organizations.

### Examples
- An online supplier portal.
- A customer login portal for order tracking.
- A bank's secure portal for corporate clients.
- A university portal for affiliated colleges.