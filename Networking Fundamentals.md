Choose the connectionless protocols? (Choose three)
1. - [x] TFTP
2.  SSH
3.  - [x] DNS
4. Telnet
5. - [x] DHCP
---

How many usable hosts are available in a /22 network?
- $2^{32-22}-2 = 1022$

---
Which of these fields are found in an Ethernet frame header? (Choose two)
1. - [x] checksum 
2. - [x] type
3. flags
4. TTL

![image](https://user-images.githubusercontent.com/57877290/203236762-cd25a8e5-7718-49d6-80c8-160ea291ad42.png)
---

Which of these happens when two devices send frames at the same time resulting in a collision? (Choose two)
1. - [x] Both devices stop transmitting, wait for a random period of time, verify that the wire is idle, and re-transmit
2. - [x] Both devies send a jam signal to notify all other devices of the collision 
3. The device with the lowest MAC address is allowed to re-transmit first
4. The device with the highest MAC address is allowed to re-transmit first 
---

The format of IPv6
- An IPv6 address consists of 128 bits grouped into **eight** 16-bit hexadecimal sections separated by colons.
---

What are the benefits of IPv6?
- IPv6 reduces admistrative overhead using stateless address autoconfiguration for hosts
- IPv6 supports a greater level of security by integrating features that were optional add-ons in IPv4
---

What are the usable hosts on the **192.168.1.24/29** network?
- $2^{32-29}-2 =6$
- `192.168.1.25, 192.168.1.26, 192.168.1.27, 192.168.1.28, 192.168.1.29, 192.168.1.30`
---

Which of these are true? (choose three)
1. UDP is connection-oriented 
2. UDP is a reliable protocol
3. - [x] UDP communication is best-effort 
4. - [x] UDP and TCP operate at the Transport layer
5. - [x] UDP is faster than TCP
---

Which layer of the OSI Model converts frames into bits?
- Physical layer
---

How many usable host addresses are available in 181.74.94.235/21?
- $2^{32-21}-2 = 2046$
--- 

What is the last usable IP address in 200.10.10.0/26 ?
- $2^{32-26}-2 = 62$ 
- $200.10.10.0+62 = 200.10.10.62$
--- 

**Which of these are true about Layer 2 broadcast frames? (choose two)**
1. - [x] layer 2 broadcast frames are processed by all devices on the same VLAN
2. layer 2 broadcast frames are relayed by routers to all connected VLANs 
3. layer 2 broadcast frames are discarded by routers that connect to multipl VLANs
4. - [x] layer 2 broadcast frames are relayed by switches to devices on the same VLAN

`same VLAN is the key, as layer 2 dont deal with cross VLANs, hint: Broadcast MAC address`

---

which IP protocol number is assigned to TCP?
- 6
---

Some protocols use UDP as a transport protocol by default
- SNMP (Simple Network Management Protocol)
- NTP (Network Time Protocol)
---

In the MAC address ac:bc:32:a3:4b:7b, what represents the Organizationally Unique Identifier (OUI)?
- ac:bc:32
---

**Which of these about optical networks are true? (choose two)**
1. - [x] SONET and SDH both use TDM 
2. SONET and SDH both use WDM 
3. - [x] Optical transport network uses WDM 
4. Optical transport network uses TDM

`A SONET/SDH stream can consist of discrete lower-rate traffic flows that have been combined using time-division multiplexing (TDM) techniques.`

`WDM stands for wavelength-division multiplexing`

---

Collision Domains for Hub and Switch
- On a hub, the collision domain includes all devices connected to the hub
- On a switch, the collision domain is limited to each device and the switch 
---

**Which three statements are true about IPv6 link local address? (Choose three)**
1. - [x] they can be assigned manually or dynamically
2. - [x] they begin with prefix `fe8-::/64`
3. they provide reachabilty to the internet 
4. they are optional addresses
5. - [x] they are not guaranteed to be unique outside of the network segment  
---

Which of these are true about subnet masks? (choose two)
1. - [x] A subnet mask specifies the portion of an IP address that represents a network prefix 
2. - [x] A subnet mask specifies the portion of an IP address that represents network hosts.
3. A subnet mask specifies the portion of an IP address that is in a decimal format
4. A subnet mask specifies the portion of an IP address that is in a binary format
--- 

SONET network elements that are used for troubleshooting
- path
- line
- section
---

Which CIDR notation is the equivalent of the subnet mask of 255.255.192.0?
- 11111111.11111111.11000000.00000000
- 18 ones
- /18












