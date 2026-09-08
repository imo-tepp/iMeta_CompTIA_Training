# Understanding Subnetting in Modern Networks

## Learning Objectives

- Explain the necessity of subnetting in modern networks.
- Perform basic subnetting calculations accurately.
- Identify the components of an IP address and subnet mask.
- Describe how subnetting enhances network efficiency and security
- Apply subnetting concepts to real-world scenarios.

### Subnetting

Subnetting is the process of dividing a large network into smaller, manageable parts.

- Enhances security by isolating different parts of a network
- Improves performance by reducing traffic
- Simplifies management by organizing devices

Subnetting uses subnet mask to define which part of the IP address identifies the network and which part is the host

Example: In the IP address 192.168.1.0/24, the /24 indicates the subnet mask, which determines how many IP addresses are available in this subnet

### Classful Addressing

Classful addressing divides networks into different classes, each with it's own default subnet mask. This helps determining the size of the network

- Class A has a default subnet mask of 255.0.0.0. supporting large networks.
- Class B has a default subnet mask of 255.255.0.0. supporting medium size networks.
- Class C has a default subnet mask of 255.255.255.0, supporting small networks.

### Subnetting Steps

1. Determine the number of subnets needed for your network.
2. Calculate the subnet mask based on the number of subnet.
    - Use the formula: 2^n = number of subnets needed
    - n is the number of bits borrowed
    - This calculation helps in network design
3. Assign Subnets, the IP address are distributed to each subnet based on the calculation, making sure each subnet has unique range of IP address.

**Example**:
A /26 subnet mask can be used for 4 subnets. IP addresses work in 32 bits, 2 bits are used network and broadcast addresses. so the remainder is 30, /26 means 26 bits is already in use, so 4 bits are left, those 4 bits are the host bits and be used to make 4 subnets.Each subnet can accommodate 64 addresses.

## Questions & Answers

### 1st Set

1. What is Subnetting?
    - Dividing a network into smaller sub-networks
2. Why is Subnetting used in networking?
    - To improve network performance and organization
3. What is subnet mask?
    - A number that defines the network and host portions of an IP address
4. How does Subnetting enhance security?
    - By isolating network segments and controlling traffic
5. What is the significance of the first and last IP address in a subnet?
    - They are reserved for network and broadcast addresses
6. What is a private IP address?
    - An IP address used within a private network

### 2nd Set

1. What is the first step in the subnetting process?
    - Identify the network address
2. When subnetting, why is it important to determine the number of required subnets?
    - To ensure that the network can accommodate all necessary subnets.
3. What is a subnet mask used for in subnetting?
    - To define the network and host portions of an IP address.
4. How many subnets can be created with 3 bits of subnetting?
    - 8
5. What is the maximum number of hosts that can be supported with 6 bits?
    - 62
6. If a subnet has 8 bits for the host part, how many bits are left for the network part?
    - 24
7. True or False: The number of bits for a subnet directly affects the number of available IP addresses
    - True
8. What is the minimum number of bits required to create 16 subnets?
    - 4
9. If a network has a subnet mask of /22, how many bits are used for the host part?
    - 10

### 3rd Set

1. What is one benefit of subnetting in a network?
    - Improved IP address management
2. How does subnetting enhance network security?
    - It isolates network segments
3. Which of the following is a reason for implementing subnetting?
    - Optimizing network performance
4. What is a key benefit of subnetting for large organizations?
    - Efficient IP address allocation
5. What advantage does subnetting provide for network troubleshooting?
    - Simplifies troubleshooting
6. How does subnetting affect broadcast traffic?
    - Reduces broadcast traffic
7. Why is subnetting important for network scalability?
    - Facilitates network growth
8. How can subnetting improve overall network performance?
    - Enhances overall network performance
9. What is one of the primary reasons for using subnetting in modern networks?
    - Creates organized network structure
