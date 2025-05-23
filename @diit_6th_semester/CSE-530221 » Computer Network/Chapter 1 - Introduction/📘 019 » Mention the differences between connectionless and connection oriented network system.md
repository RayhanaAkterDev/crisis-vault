# Differences Between Connectionless and Connection-Oriented Network Systems

| Feature            | Connection-Oriented                                                                     | Connectionless                                                        |
| ------------------ | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| **Definition**     | A communication system that first establishes a connection before data transfer begins. | A system where data is sent without establishing a connection.        |
| **Setup**          | Requires a connection setup phase before data is sent.                                  | No setup phase; data is sent immediately.                             |
| **Reliability**    | Reliable – ensures data is delivered in order and without errors.                       | Less reliable – data may be lost, duplicated, or arrive out of order. |
| **Protocols Used** | TCP (Transmission Control Protocol)                                                     | UDP (User Datagram Protocol), ICMP                                    |
| **Speed**          | Slower due to connection setup and error checking.                                      | Faster as there is no connection setup or confirmation.               |
| **Acknowledgment** | Acknowledges received data with confirmation messages.                                  | No acknowledgment – sender doesn’t know if data was received.         |
| **Use Cases**      | File transfer, web browsing, email (e.g., FTP, HTTP, SMTP)                              | Live video/audio streaming, online gaming, VoIP                       |
| **Example**        | Like a phone call – connection is established before talking.                           | Like sending a letter – no confirmation if the receiver got it.       |



---

tag:: #board_2022 #board_2021 #board_2019 #mid_term 