# Understanding Network Communication

## Learning Objectives

- Explain the process of encapsulation and Ethernet framing
- Describe the function at each layer of the 3-layer network design model
- Analyze methods to improve network communication at the access layer

## 3-Layer Network Design Model

- **Core Layer** : Responsible for high-speed data transfer and routing
- **Distribution Layer** : connects the core to the Access Layer and offers policy-based connectivity.
- **Access Layer** : provides end-user connectivity, allowing device to connect to the network.

  - Can use **switches** to manage data traffic effectively.
  - Implement **VLANs** to segment network traffic and improve security.
  - Apply **Quality of Service (QOS)** techniques to prioritize critical network traffic.
  - Reducing **collisions** to enhance data transmission efficiency.
  - Enhancing **bandwidth** to accommodate more users and devices.

## Questions & Answers

### 1st Set

1. What is the primary purpose of Ethernet framing?
    - To encapsulate data for transmission over a network
2. Which of the following is included in an Ethernet frame?
    - Destination MAC address
3. What does the term 'encapsulation' refer to in networking?
    - Wrapping data with protocol information
4. What is the maximum payload size of an Ethernet frame?
    - 1500 bytes
5. True or False: The Frame Check Sequence (FCS) is used for error detection in Ethernet frames.
    - True
6. What happens if an Ethernet frame is too large?
    - It will be dropped
7. What role does the destination MAC address play in an Ethernet frame?
    - It specifies the intended recipient of the frame

### 2nd Set

1. What is the primary purpose of a 3-layer network design?
    - To improve scalability and manageability.
2. Which layer of the 3-layer network design is responsible for routing and forwarding data?
    - Distribution layer
3. What role does the distribution layer play in a 3-layer network design?
    - It aggregates and forwards data.
4. What is a key benefit of using a 3-layer network design?
    - Easier troubleshooting and maintenance.
5. What is the main function of the access layer in a 3-layer network design?
    - To provide connectivity to end-user devices.

### 3rd Set

1. What role does the access layer play in a network?
    - It connects end devices to the network.
2. What is a key characteristic of the routing layer?
    - It uses routing protocols to determine the best path for data.
3. True or False: The access layer can also be referred to as the edge layer of the network.
    - True
4. What type of devices are typically found at the access layer?
    - Switches and access points.

### 4th Set

1. What is a broadcast in a network?
    - A method of sending data to all devices on a network.
2. Which of the following is a common broadcast address in IPv4 networks?
    - 192.168.1.255
3. Which of the following is a disadvantage of broadcasting?
    - It can create unnecessary traffic.
4. True or False: Broadcasting can lead to network congestion if too many broadcasts are sent.
    - True.
5. What is a potential solution to reduce broadcast traffic in a network?
    - Implementing VLANs.
6. True or False: Broadcasting is only used in wired networks.
    - False
7. Which device can help manage broadcast traffic in a network?
    - Router
8. Why is it important to reduce broadcasts in a network?
    - To improve network performance.
9. What is a broadcast storm?
    - A situation with excessive broadcast traffic
10. Which of the following is a common use of network broadcasting?
    - Sending messages to all users in a LAN.
11. True or False: A broadcast address is used to send data to all devices in a network segment.
    - True
12. What is the primary advantage of using network broadcasting?
    - Efficiency in communication.
13. What happens when a device sends a broadcast message?
    - It is sent to all devices in the broadcast domain.
14. True or False: Broadcast messages can be filtered by routers.
    - True.