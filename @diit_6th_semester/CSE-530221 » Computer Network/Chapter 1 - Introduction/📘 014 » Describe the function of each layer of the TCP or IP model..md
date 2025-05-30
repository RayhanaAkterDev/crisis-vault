> See the exam paper answer - page 160

The **TCP/IP model** (Transmission Control Protocol/Internet Protocol) is a foundational framework for how data is transmitted across the internet. It consists of **four layers**, each with a specific function that contributes to successful data communication between devices.

---

### 1. **Application Layer**

**Definition:**  
The Application Layer is the topmost layer of the TCP/IP model. It provides a direct interface between user applications and the network. This layer is responsible for delivering services such as web browsing, file transfers, and email by using various application-level protocols.

**Key Functions:**

- Provides services like HTTP, FTP, SMTP, DNS, and DHCP.    
- Facilitates communication between software applications and lower network layers.    
- Handles data formatting, user authentication, and session control.    
- Manages data encryption and compression where needed.    

---

### 2. **Transport Layer**

**Definition:**  
The Transport Layer ensures reliable or best-effort communication between devices. It establishes end-to-end connections, manages data delivery, and ensures that data is delivered accurately and in the correct sequence.

**Key Functions:**

- Uses TCP for reliable communication and UDP for faster, connectionless communication.    
- Breaks large messages into smaller segments and reassembles them at the destination.    
- Performs error detection, correction, and retransmission (TCP).    
- Uses port numbers to identify sending and receiving applications.    
- Controls data flow to prevent congestion or packet loss.    

---

### 3. **Internet Layer**

**Definition:**  
The Internet Layer is responsible for logical addressing and routing of data packets across multiple networks. It ensures that each packet reaches its correct destination, even if it has to pass through several intermediate routers.

**Key Functions:**

- Assigns IP addresses and ensures proper identification of devices.    
- Determines the best path for data transmission using routing protocols.    
- Handles packet fragmentation and reassembly for compatibility across networks.    
- Uses protocols such as IP, ICMP (for error reporting), and ARP (for address resolution).    
- Enables internetworking by connecting multiple networks together.    

---

### 4. **Network Access Layer (Link Layer)**

**Definition:**  
The Network Access Layer is the lowest layer in the TCP/IP model. It manages the physical transmission of data over the network medium. This includes both the hardware (like cables and network interface cards) and the software protocols that control access to the medium.

**Key Functions:**

- Encapsulates data into frames for transmission.    
- Uses MAC addresses to identify devices on the local network.    
- Handles access control to shared communication channels.    
- Performs error detection using techniques like checksums.    
- Supports transmission technologies such as Ethernet and Wi-Fi.

---

tag:: #board_2022 #board_2020 #mid_term 