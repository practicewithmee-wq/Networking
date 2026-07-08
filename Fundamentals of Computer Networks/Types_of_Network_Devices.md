# Layer 1 Devices : Physical Layer
THese devices deal with raw electrical or optical signal (bits). These devices do not understand IP Address or MAC Address.

## HUB 

- HUB is a network devices that is used to connect multiple computer in a network.
- All the information send to the HUB is automatically send to each port to every device.
- A HUB is less expensive, less intelligence & less complicated.
- HUB generally used to connect computer in a LAN.
- Transmission node of HUB is half duplex.

image

### Advantage

- The HUB broadcast the message.
- It is less expensive that anyone can use it.
- Easy installation.
- Robust

### Disadvantage 

- If the HUB is failed the entire network will be failed.
- We Can't send private / personal data through HUB.
- HUB doesn't provide and security.
- HUB can't support full duplex transmission mode.

## Repeater 
Repeater is a network device through which we can "bootup the weak signals". When the signal travels in the network, after travelling some distance the intensity of the signal becomes low.    
It order to regenrate the weak signal we should use repeater device.

image

### Advantage

- It is used to regenerate the weak signal.
- It is cheaper than other hardware device.
- Repeaters has the ability to extend the length of signal.
- Increase / mentain the signal performance.

### Disadvantage

- It required no. of repeater after some distance
- Repeater also unable to connect dis-similar type of hardware.
- They can't reduse hardware traffic.

# Layer 2 Devices : Data Link Layer
These devices work with MAC Addresses (Physical Addresses). They are smarter than HUBs.

## Switch 

1. Switch is a network device that connects multiple computer together in the network.

2. It is mainly used to send the private message as well as their is no wasting as data.

3. Switch can easily identifie that which device is connected with which port by using MAC address, that why it delivered message on particular destination machine.

image

### Advantage

- It generally used to unicast the message.
- It provides more security than HUB.
- Switch support full duplex data transmission mode.
- It is used to send the data a packet based on MAC address.
- It is a node fails, there will be no effect in the entire network.

### Disadvantage

- It switch is failed then entire network will be failed.
- It is more expensive.
- Difficult to setup.

# Bridge
Bridge is a network device that is used to seperate LAN into no. of section.

image

It seperate both physical as well as data link layer of OSI Model.

### Advantage

- By using bridge device we can extends network.
- It broadcast the data to each node like HUB & Repeater.
- Collision can be reduced easily.
- It is more intellegent.

### Disadvantage

- It doesn't stablish connection between two different network.
- Once it broadcast the message than it is incapable to stop the messages.
- It is more expensive.
- The transmission rate of data is slower than reapeater.

# Modem

Modem stands for `Modulator` & `Demodulator`, it is a network device that is placed between the computer system and telephone line. 

It has two part Modulator & Demodultor.     

Modulator convert `digit signal` to `analog signal` were as Demoulator convert `analog signal` to `digital signal`.

image

It allow us to computer to connect internet.

# Layer 3 Devices : Network Layer
These devices work with IP Addresses (Logical Addresses) and connect different network together.

## Router
Router is a network device which works as a traffic controller A main work of router is to choose a congestion free path through which the data packet recieve data packets to the sender, analyze and forward those packets then giving to reciver.

image

Router use both LAN & WAN Network

### Advantage

- It provides connection between two dis-similar type of network.
- Transmission rate is very high 
- It internally user some algorithm to findout congestion free path.
- It provides both wire on wireless facility.

### Disadvantage

- Router is more expensive compare to other network device.
- Routers are complex to maintain.
- Security issues.
- It only work with routable protocol.

## Access Point (AP)

Access point (AP) is a networking device that creates a wireless local area network (WLAN). It acts a central HUB or Bridge allowing wifi device (like laptop, phones, and IOT) to connect to a wired network using radio signals.

### Advantage 

- **More user Access** :
    - Normally the wireless router allow 10-20 users or devices to access network. while the WAP allows 50-100 or more user or devices to access the network.
    - Which enables high usage,

- **Broder Transmission Range** :
    - Wireless router signals cover up to a dozen or 10-20 meter. However wireless access point cover more than 100-300 meters.
    - Board range is supermacy for the large cover offices or building for the bigger bussiness with this wireless AP, a user can easily roam that network.

- **Flexible Networking** :
    - It is known that wireless networking except in homes, often involves many wireless devices and different networking pattens implanted based on the environment and requirements of the commercial locations.

- **Mobility** :
    - users can more freely while still being connected to the network.

### Disadvantage

- **High Cost** :
    - A wireless AP is a little bit expensive because that scale of enterprises the wireless scale network is larger, the more WAPs are needed the most cost will increase. so the enterprise has the priority to control the cost which leads many users to be reluctant to use WAP but instead of this, they end up using home routors with the lowest performance.

- **Poor stability** :
    - The signal strength also depends upon the location where the wireless network is implanted.
    - wireless signals are blocked due to certain obstcles such as heavy rain, great walls, gates, storm, heavy wind, large gathering of human beings, etc.

- **Less secure** :
    - As compare to the wired network it is less secure because the user is using raidio waves for transmission and someone or a hacker on the network could sniff the traffic.


# Layer 4-7 Device : Advance Processing

## Firewall

A firewall is a network security system, available as hardware of software, the monitors and controls incoming and outgoing traffic based on predefined rules. It acts like a security guard, filtering data packet to either:
- **Access** : Allow the traffic.
- **Reject** : Block with an error response.
- **Drop** : Block silently without response.

image

firewall acting as a barrier between LAN and WAN

## Type of Firewall
Firewalls can be categarized based on their generation.

1. **Network Placement**

    - packet filtering firewall
    - Statefull inspection firewall
    - Proxy firewall (Application layer)
    - Circuit-level gateway
    - Web Application firewall (WAF)
    - Next Generation firewall (NGFW)

2. **System Protected**

    - Network firewall
    - Host-Based firewall

3. **Data Filtering Method** 

    - Perimeter firewall 
    - Internal firewall 
    - Distributed firewall

4. **Form Factors**

    - Hardware firewall
    - Software firewall

## Improtance

- **Prevent Unauthorized Access** : Like a locked door with a guard, only trusted users and traffic are allowed through.

- **Block Malicious Traffic** : Harmful data such as viruses, phishing attempts, or denial-of-services (DOS) attacks are stopped before reaching the system.

- **Protect Sensitive Information** : Safe gurads personal and bussiness data from theft or accidental leaks.

- **Control Network Usages** : Enforces polices such as parental control, workplace restrictions, or government filtering.

- **Mitigate Insider Risks** : Dectects suspicious applications or data exfitration attempts from within the network.

## Gateway

Gateway is a hardware device that is used to connect two dis-similar type of network.   
It allow us to send & receive data through the internet even it is LAN network.

image

It operates all 7 layer of OSI Model

### Advantage

- It Connects two network which has different protocol.
- It operate all 7 layer of protocol 
- we can't access the internet without a gateway.
- It provide some security.

### Disadvantage

- It is more expensive
- Data transmission rate is slower.
- Difficult to mentain as well as very complex.
- It is less intellegent.