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
--- 

What is the network address for host 72.36.142.14/11?
- subnet mask binary: 11111111 11100000 00000000 00000000
- increment is 2^5 = 32
- 72.0.0.0
- 72.32.0.0
- 72.64.0.0 
- Ans: **72.32.0.0**
--- 

Which set of IP addresses is in the same subnet?
1. 185.114.16.91/28 and 186.114.16.96/28
2. 185.114.16.59/28 and 185.114.16.64/28
3. 185.114.16.77/28 and 185.114.16.82/28
4. - [x] 185.114.16.40/28 and 185.114.16.45/28

```
/28 in binary 11111111 11111111 11111111 11110000
increment is 2^4 = 16
185.114.16.0
185.114.16.16
185.114.16.32
...

1) 91 / 16 = 5.x, 96 / 16 = 6
2) 59 / 16 = 3.x, 64 / 16 = 4
3) 77 / 16 = 4.x, 82 / 16 = 5.x
4) 40 / 16 = 2.x, 45 / 16 = 2.x
```
--- 

Consider the host IP Address is - 192.168.100.60 and the network mask is - 255.255.255.224 (or /27). Which of the following address represents the correct network address for the referenced host?
- 32-27=5  11100000， increment = 2^5= 32 
- 60/32 = 1.x
- then, **192.168.100.32**
---

![image](https://user-images.githubusercontent.com/57877290/203381208-f3c005ef-9de1-4c5d-aaa7-4ec7f4af770f.png)
![image](https://user-images.githubusercontent.com/57877290/203381282-b242e9a7-8e7b-4a30-9da7-b5deb500573c.png)
![image](https://user-images.githubusercontent.com/57877290/203381339-3cc6455f-5e0b-4ea2-a51d-5d129ba2a2fa.png)
![image](https://user-images.githubusercontent.com/57877290/203381376-351d7e90-60b7-4bd5-acb8-1e8243b4cb79.png)
![image](https://user-images.githubusercontent.com/57877290/203381443-364901ed-2e7b-4cd5-8aec-fd7e7ba8dccc.png)
![image](https://user-images.githubusercontent.com/57877290/203381467-2eda03d3-81f1-464c-a8bb-26cdd5e5fe8d.png)
![image](https://user-images.githubusercontent.com/57877290/203381503-f8e60ae3-dade-40b4-aabb-c9f22dcc0d2b.png)
![image](https://user-images.githubusercontent.com/57877290/203381532-8300863f-e0e4-452b-80c0-72a9f9b09ead.png)
![image](https://user-images.githubusercontent.com/57877290/203381564-c9dfc081-fc24-4ccc-8347-28a6334e7b30.png)
![image](https://user-images.githubusercontent.com/57877290/203381607-0979395a-c6d3-4903-b0e7-9e3b19ed783b.png)
![image](https://user-images.githubusercontent.com/57877290/203381645-24e7fb05-5ac6-4bd5-b5ce-314e68eeeca7.png)
![image](https://user-images.githubusercontent.com/57877290/203381672-647e16f8-fdb0-499c-abdf-a387b29046d2.png)
![image](https://user-images.githubusercontent.com/57877290/203381731-e7c1dce7-8580-4d03-8745-d6152227555f.png)
![image](https://user-images.githubusercontent.com/57877290/203381771-8b17f2a5-4808-4208-912d-45fbe930f2b4.png)
![image](https://user-images.githubusercontent.com/57877290/203381806-0113e090-7074-4c40-967f-53fdbdb71658.png)
![image](https://user-images.githubusercontent.com/57877290/203381826-aac124d7-41e3-4b66-bf43-d0d5f4480868.png)
![image](https://user-images.githubusercontent.com/57877290/203381887-46584769-58ee-4ab5-8da1-f558f92a10eb.png)












