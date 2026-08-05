## Physical Layer in OSI Model
The Physical Layer is the lowest OSI layer responsible for transmitting raw data bits through physical network hardware.

- Handles physical and electrical data transmission
- Includes cables, connectors, plugs, and receivers
- Transfers raw bits between devices
- Defines hardware standards and signal types

## Functions of Physical Layer

### 1. **Bit-by-Bit Transmission**      
Bit-by-bit transmission means the Physical Layer transmits data one bit (0 or 1) at a time through the communication medium from the sender to the receiver.

![Bit-by-Bit Transmission Image](/Images/bybT.webp)

### 2. **Encoding And Decoding**        
- **Encoding** is the process of converting binary data (0s and 1s) into electrical, optical, or radio signals so it can be transmitted over the communication medium.    
- **Decoding** is the process of converting the received signals back into binary data (0s and 1s) so the receiving device can understand it.

![Encoding And Decoding image](/Images/EandD_4.jpg)

### 3. Signal Transmission

It is responsible for converting data into signals (analog or digital) for transmission and decoding these signals at the receiver's end.

![Signal Transmission Image](/Images/signal%20transmission_3.jpg)

### Modulation And Demodulation (Modulator And Demodulator)

Modulation is the process of modifying a carrie signal's properties (amplitude, frequency, or phase) for transmission over a communication medium.

![Modulator And Demodulator Image](/Images/Frequency-Modulation_2.jpg)

### Transmission Modes 

Transmission mode is the direction in which data is transmitted between two devices.

![Transmission Modes Image](/Images/types-transmission-mode3.jpg)

### Data Rate Control

Physcial layer is Controls the speed of data transmission between devices (measured in bps) same data rate.

![Data Rate Control Image](/Images/data%20rate%20control_2.jpg)

- Prevents buffer overflow
- Reduces data loss
- Keeps transmission smooth

## Physical Topology

Physical topology is the physical arrangement or layout of devices and cables in a network. Below are the different topologies used in Computer Networks

### Types of Line Configuration:

- **Point-to-Point Configuration**: One device is directly connected to another device.
- **Multipoint Configuration**: Multiple devices share the same communication link.

## Protocols in Physical Layer

The Physical Layer does not have many protocols like the upper layers. Instead, it defines standards for transmitting data over the physical medium.

**Common Physical Layer Protocols/Standards:**

- Ethernet (IEEE 802.3)
- Wi-Fi (IEEE 802.11)
- Bluetooth (IEEE 802.15.1)
- USB (Universal Serial Bus)
- RS-232 (Serial communication standard)