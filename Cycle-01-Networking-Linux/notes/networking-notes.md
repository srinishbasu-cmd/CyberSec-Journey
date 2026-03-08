OSI Model
1. Application Layer:
  Main layer where users interact with it.
  FTP (File Transfer Protocol) can communicate here to transfer files between client and server on a network, it also connects computers.
2. Presentation Layer:
  Presentation Layer converts data to Binary, Machine readable format. 
  It uses SSL Protocol (Secure Socket Protocol)
  It provides abstraction, compresses and encripts a data.
3. Session Layer:
  Helps setting eup and managing the connections and it enables sending and recieving of data followed by termination of the connected session.
4. Transport Layer:
  Segmentation: Data recieved from Session layer will be divided into small data units called Segments. Every Segment contains the source and the destination port number and a sequence number. Sequence number helps to reassemble the segments in correct order.
  Error control: It adds CheckSum to every dataset to see if data recieved was good or not.
  Flow control: Controls the amount of data that is being transferred.
  It uses UDP(User Datagram Protocol) and TCP(Transmission Control Protocol).
5. Network Layer:
  Works for the transmission of the recieved data segments from one computer to another that is located in a different network.
  Logical addressing: IP addressing is done in Network Layer.
  Network layer assigns the senders and recievers IP address to every segments and it forms a IP packet.
  It does Routing, which is moving one Data Packet from source to destination.
  Load balancing also happens here.
6. Data Link Layer:
  Used to directly communicate with the computers and hosts.
  Physical addressing: Mac addresses of sender and reciever are assigned to the data packet to form a frame.
  Frame is the data unit of the Data Link Layer.
  2 Functions of Data Link Layer:
    (i) Allows upper layers of the OSI model to access these frames.
    (ii) It controls how the data is placed and recieved from the media using media access control, basically techniques used to get \the frame on and off media and like Error Detection(checks if data was corrupted while transmission).
7. Physical Layer:
  It transmits bits ti electrical signals. It is the hardware section.
  Gets data from top in the form of zeroes and ones and it converts them into wires, electrical signals or light signal, optical fibre cable or radio signal.
  During recieving signal, Physical layer converts electrical signal to bits and sends it to Data link layer.

UDP vs TCP
| UDP | TCP |
|-------|---------|
| UDP(User Datagram Protocol) does not ask for feedback. It is fast. Data might be lost here. | TCP(Transmission Control Protocol) asks for feedback. It is slow. Data is not lost here. |
| UDP used when speed is more important than reliability. Foe example in video streaming, online gaming. | TCP is used when reliable delivery of Data is required. For example in web browsing, emails. |
