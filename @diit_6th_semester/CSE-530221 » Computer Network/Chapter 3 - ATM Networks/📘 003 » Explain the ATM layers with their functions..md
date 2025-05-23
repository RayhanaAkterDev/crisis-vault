# ATM layers with their functions.

ATM (Asynchronous Transfer Mode) is a high-speed networking technology that organizes data into small fixed-size cells for fast and efficient transmission. The ATM architecture is divided into three main layers, each with a specific role.

The **Physical Layer** is responsible for transmitting the raw bits over the physical medium, such as fiber optic cables or copper wires. It defines the electrical, optical, and mechanical characteristics needed to send and receive ATM cells.

The **ATM Layer** manages the cell transmission across the network. It handles cell multiplexing, switching, and routing to ensure that cells reach their destination correctly and efficiently. This layer adds header information to cells, including virtual path and channel identifiers, which help direct the cells through the network.

The **ATM Adaptation Layer (AAL)** This layer adapts different types of user data (such as voice, video, and data) into the fixed-size ATM cells used for transmission. It is responsible for segmenting larger data packets into smaller ATM cells before sending and reassembling them back into the original data at the receiving end. The AAL adapts user data into ATM cells and supports different types of services. It is divided into different classes to handle various kinds of traffic:

- **AAL1**: Used for constant bit rate (CBR) services like voice and video where timing is critical. It supports synchronous, real-time data transmission with strict timing and error correction.
- **AAL2**: Designed for variable bit rate (VBR) services, such as compressed voice and video, where timing is important but data rate can vary. It efficiently handles bursty and low-delay traffic.
- **AAL3/4**: Used for connection-oriented and connectionless data services like file transfer or email. It provides error detection, segmentation, and reassembly but is less strict about timing compared to AAL1 and AAL2.

---

tag:: #board_2022 #board_2020 

