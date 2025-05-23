# ATM layers with their functions.

ATM (Asynchronous Transfer Mode) is a high-speed networking technology that organizes data into small fixed-size cells for fast and efficient transmission. The ATM architecture is divided into three main layers, each with a specific role.

The **Physical Layer** is responsible for transmitting the raw bits over the physical medium, such as fiber optic cables or copper wires. It defines the electrical, optical, and mechanical characteristics needed to send and receive ATM cells.

The **ATM Layer** manages the cell transmission across the network. It handles cell multiplexing, switching, and routing to ensure that cells reach their destination correctly and efficiently. This layer adds header information to cells, including virtual path and channel identifiers, which help direct the cells through the network.

The **ATM Adaptation Layer (AAL)** sits on top and adapts various types of user data (like voice, video, or data) into ATM cells. The AAL segments larger packets into fixed-size cells at the sender side and reassembles them at the receiver side. It also manages error detection and timing to support different service types, ensuring data integrity and proper timing for real-time communication.

---

tag:: #board_2022 #board_2020 

