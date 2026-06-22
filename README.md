# CompTIA-Network-Learn-6.1.7-Lab-Explore-Three-Way-Handshake-in-Wireshark
## CompTIA CertMaster Learn v9.1

In this lab, your task is to:

* Use Wireshark to capture packets from the enp2s0 interface (about 5 seconds).
* Use a Wireshark filter to isolate and examine only TCP packets sent or received by the computer at 192.168.0.45. Use the command tcp and host 192.168.0.45
* Examine a [SYN] packet and then answer Questions 1 and 2.
* Examine an [ACK, SYN] Packet, then answer Questions 3 and 4.
* Examine an [ACK] Packet, then answer Questions 5 and 6.

![ACK](/Screenshot_1.png)  
![ACK/SYN](/Screenshot_2.png)  
![SYN](/Screenshot_3.png)  
![QnA](/Screenshot_4.png)

Explanation

Complete this lab as follows:

1. Begin a Wireshark capture.  
  a. From the Favorites bar, select Wireshark.  
  b. Maximize the window for easier viewing.  
  c. Under Capture, select enp2s0.  
  d. Select the blue fin to begin a Wireshark capture.  
  e. Wait about 5 seconds, then select the red square to stop the Wireshark capture.  
2. Apply a filter for tcp traffic from the computer at 192.168.0.45 and examine a [SYN] packet.  
  a. In the Apply a display filter field, type tcp and host 192.168.0.45 and press Enter.  
  b. Look at the source and destination addresses of the filtered packets.  
3. Examine a [SYN] packet  
  a. Select a packet that includes [SYN] in the Info column.  
  b. In the center pane, expand Internet Protocol Version 4 and Transmission Control Protocol.  
  c. Select Questions, then answer Questions 1 and 2.  
  d. Minimize the Lab Questions dialog.  
4. Examine an [ACK, SYN] Packet.  
  a. Select a packet that includes [ACK, SYN] in the Info column.  
  b. Select Questions, then answer Questions 3 and 4.  
  c. Minimize the Lab Questions dialog.  
5. Examine an [ACK] Packet.  
  a. Select a packet that includes [ACK] in the Info column.  
  b. Select Questions, then answer Questions 5 and 6.
