
# COMPUTER NETWORKS
# Table of Contents

0. What is Internet?

1. Introduction to Computer Networks

2. Networking Models

3. OSI Model

4. TCP/IP Model

5. Physical Layer

6. Data Link Layer

7. Network Layer

8. Transport Layer

9. Session Layer

10. Presentation Layer

11. Application Layer

12. Network Devices and Hardware

13. Network Security


## CHAPTER 1: What is the Internet?
The **Internet** is a vast, global network of interconnected computer networks that communicate using standardized protocols, primarily the Internet Protocol Suite (TCP/IP). It allows devices and systems around the world to exchange data and share resources, enabling various services and applications. 

**The Internet** is a worldwide network of networks that uses standardized communication protocols to link millions of private, public, academic, business, and government networks, enabling the exchange of information and services such as the World Wide Web, email, and file transfers.

### What is the Internet?

The Internet is a vast, global network of interconnected computers and servers that communicate with each other using standardized protocols. It enables the exchange of information and resources across different networks and devices worldwide. The Internet supports various services, including web browsing, email, file sharing, and online applications, making it an integral part of modern life.

## 1. Overview

### Definition

The Internet is a decentralized network of networks that allows computers and other devices to communicate with each other over a vast range of distances. It provides a wide array of services and resources, including the World Wide Web (WWW), email, file transfers, and online gaming.

### Key Features

- **Global Reach**: Connects devices and networks across the globe.
- **Decentralized Architecture**: Operates without a central authority, relying on multiple interconnected networks.
- **Standardized Protocols**: Uses standardized protocols to ensure interoperability between different systems and networks.
- **Scalability**: Designed to scale and accommodate an increasing number of devices and users.

## 2. Historical Background

### Origins

- **ARPANET**: The precursor to the Internet, ARPANET (Advanced Research Projects Agency Network), was developed in the late 1960s by the U.S. Department of Defense. It aimed to enable communication between research institutions.
- **TCP/IP**: In the 1970s and 1980s, the development of the TCP/IP (Transmission Control Protocol/Internet Protocol) suite by Vint Cerf and Bob Kahn provided a standardized method for data transmission, which became the foundation for the modern Internet.
- **Expansion**: Throughout the 1980s and 1990s, the Internet expanded rapidly, transitioning from a research tool to a public and commercial network. The introduction of the World Wide Web by Tim Berners-Lee in 1991 revolutionized access to information and services on the Internet.

## 3. Architecture and Components

### Internet Protocol Suite (TCP/IP)

The Internet relies on the TCP/IP protocol suite, which defines how data is transmitted and routed. The suite consists of four layers:

1. **Link Layer**: Handles communication between devices on the same network segment. Includes protocols like Ethernet and Wi-Fi.
2. **Internet Layer**: Manages logical addressing and routing of packets. Includes the Internet Protocol (IP) and Internet Control Message Protocol (ICMP).
3. **Transport Layer**: Ensures reliable end-to-end communication. Includes Transmission Control Protocol (TCP) and User Datagram Protocol (UDP).
4. **Application Layer**: Provides network services to applications. Includes protocols like HTTP, FTP, SMTP, and DNS.

### Domain Name System (DNS)

The DNS translates human-readable domain names (e.g., www.example.com) into IP addresses (e.g., 192.0.2.1). This system allows users to access websites using easy-to-remember names rather than numerical IP addresses.

### Internet Service Providers (ISPs)

ISPs are organizations that provide access to the Internet. They offer various types of connections, including broadband, fiber-optic, DSL, and satellite. ISPs manage the infrastructure and provide services to individuals and businesses.


### Routers and Switches

- **Routers**: Devices that forward data packets between different networks, enabling communication across the Internet.
- **Switches**: Devices that connect devices within the same network, managing local data traffic.

## 4. Services and Applications

### World Wide Web (WWW)

The WWW is a system of interlinked hypertext documents accessed via web browsers. It uses the HTTP (Hypertext Transfer Protocol) to request and deliver web pages, making information available through websites and web applications.

### Email

Email (electronic mail) is a system for sending and receiving messages over the Internet. It uses protocols like SMTP (Simple Mail Transfer Protocol) for sending and IMAP (Internet Message Access Protocol) or POP3 (Post Office Protocol) for retrieving messages.

### File Transfer

File Transfer Protocol (FTP) and its secure version, SFTP (Secure File Transfer Protocol), are used to transfer files between computers over the Internet. These protocols facilitate uploading and downloading files to and from servers.

### Social Media

Social media platforms (e.g., Facebook, Twitter, Instagram) enable users to create, share, and interact with content online. They rely on Internet infrastructure to deliver real-time updates and facilitate global communication.

### Streaming Services

Streaming services (e.g., Netflix, YouTube, Spotify) deliver multimedia content, such as videos and music, over the Internet. They use protocols like HTTP Live Streaming (HLS) and Dynamic Adaptive Streaming over HTTP (DASH) to provide continuous playback.

## 5. Security and Privacy

### Cybersecurity

Cybersecurity measures protect the Internet and its users from various threats, including malware, phishing, and hacking. Techniques include encryption, firewalls, and intrusion detection systems (IDS).

### Encryption

Encryption secures data transmitted over the Internet by converting it into unreadable code. Common encryption methods include Secure Sockets Layer (SSL) and Transport Layer Security (TLS), which protect data during transmission.

### Privacy

Privacy concerns on the Internet involve protecting personal information from unauthorized access and misuse. Users should be aware of data collection practices, manage their privacy settings, and use secure connections to safeguard their information.

##

## CHAPTER 2: Introduction to Networking

### 1.2 Client-server architecture

It is a model used in networked computing where tasks and workloads are divided between providers of a resource or service (servers) and requesters of a service (clients). This architecture helps organize how data is shared and accessed across a network. Here’s an overview:

### Key Components:

1. **Client**:
   - **Definition**: A client is any device or software application that requests and uses services or resources from a server.
   - **Examples**: Web browsers, email clients, and mobile apps.
   - **Function**: Clients initiate requests for data or services. For example, a web browser (client) requests a webpage from a web server.

2. **Server**:
   - **Definition**: A server is a specialized computer or program that provides resources, services, or data to clients.
   - **Examples**: Web servers, database servers, and file servers.
   - **Function**: Servers respond to client requests by providing the requested data or performing tasks. For instance, a web server delivers web pages to a client’s browser.

### How It Works:

1. **Request and Response**:
   - **Request**: The client sends a request to the server for a specific service or resource. This request is typically in the form of a network message.
   - **Response**: The server processes the request and sends back the appropriate response or data to the client. 

2. **Communication**:
   - **Protocols**: Communication between clients and servers often uses standardized protocols, such as HTTP (Hypertext Transfer Protocol) for web services or FTP (File Transfer Protocol) for file transfers.
   - **Ports**: Servers often listen for requests on specific ports, which are numerical identifiers used in network communication.

### Types of Client-Server Models:

1. **Two-Tier Architecture**: Involves a client directly communicating with a server. For example, a desktop application connecting to a database server.
2. **Three-Tier Architecture**: Adds an intermediate layer (application server) between the client and the server. For example, a web application with a client browser, application server (handling business logic), and database server (storing data).
##

### Definition of Computer Networks

A computer network is a collection of interconnected devices that communicate with each other to share resources and exchange information. These devices, which include computers, servers, routers, switches, and other network-enabled hardware, are connected via various communication mediums such as cables, fiber optics, and wireless technologies.

**Key Functions of Computer Networks:**
1. **Resource Sharing**: Networks allow multiple devices to share resources like printers, files, and internet connections.
2. **Communication**: Facilitates communication between devices through email, messaging, and other forms of digital interaction.
3. **Data Management**: Centralizes data storage and management, making it easier to access and backup information.
4. **Scalability**: Networks can be expanded by adding new devices and components without significant changes to existing infrastructure.

### Importance and Applications

Computer networks have transformed the way we work, communicate, and access information. Their importance spans various domains:

1. **Business Operations**: Networks enable companies to connect multiple locations, share resources, and improve collaboration.
2. **Internet Access**: Provides access to the World Wide Web, facilitating communication, information retrieval, and online services.
3. **Education**: Networks support online learning platforms, virtual classrooms, and educational resource sharing.
4. **Healthcare**: Enables telemedicine, electronic health records (EHR), and real-time communication between healthcare professionals.
5. **Entertainment**: Supports streaming services, online gaming, and digital media distribution.

#### **Types of Networks**

Networks are categorized based on their geographic scope, size, and purpose. Here are the main types:

1. **Local Area Network (LAN)**:
   - **Description**: A network confined to a small geographic area, such as a single building or campus.
   - **Purpose**: Connects devices within a limited area to share resources and facilitate communication.
   - **Examples**: Office networks, home networks, and school networks.

2. **Wide Area Network (WAN)**:
   - **Description**: Covers a broad geographic area, often spanning cities, countries, or continents.
   - **Purpose**: Connects multiple LANs and other networks over long distances.
   - **Examples**: The Internet, corporate networks connecting multiple branch offices.

3. **Metropolitan Area Network (MAN)**:
   - **Description**: A network that covers a city or large campus.
   - **Purpose**: Provides connectivity within a metropolitan area, often used by organizations to link multiple buildings.
   - **Examples**: City-wide Wi-Fi networks, university campuses.

4. **Personal Area Network (PAN)**:
   - **Description**: A small network designed for personal use, typically within a few meters.
   - **Purpose**: Connects devices such as smartphones, tablets, and computers for personal use.
   - **Examples**: Bluetooth connections between a smartphone and a wireless headset.

### Network Topologies

Network topology refers to the physical or logical arrangement of devices and connections in a network. Common topologies include:

1. **Star Topology**:
   - **Description**: All devices are connected to a central hub or switch.
   - **Advantages**: Easy to install and manage; failure of one device doesn’t affect others.
   - **Disadvantages**: Central hub is a single point of failure; may require more cabling.

2. **Ring Topology**:
   - **Description**: Devices are connected in a circular fashion, with each device having exactly two neighbors.
   - **Advantages**: Data packets travel in one direction, reducing collisions; predictable performance.
   - **Disadvantages**: A failure in any single connection can disrupt the entire network.

3. **Bus Topology**:
   - **Description**: All devices are connected to a single central cable (the bus).
   - **Advantages**: Simple and cost-effective for small networks.
   - **Disadvantages**: Limited scalability; failure of the central cable affects the entire network.

4. **Mesh Topology**:
   - **Description**: Devices are interconnected, with each device connected to every other device.
   - **Advantages**: High redundancy and reliability; failure of one device doesn’t impact others.
   - **Disadvantages**: Expensive and complex to install and maintain.

5. **Hybrid Topology**:
   - **Description**: Combines two or more different topologies.
   - **Advantages**: Flexible and scalable; can be tailored to meet specific needs.
   - **Disadvantages**: More complex to design and manage.

### Basic Networking Concepts

1. **IP Addressing**:
   - **Definition**: A unique identifier assigned to each device on a network.
   - **Types**: IPv4 (e.g., 192.168.0.1) and IPv6 (e.g., 2001:db8::1).
   - **Purpose**: Facilitates communication between devices by providing a logical address.

2. **Subnetting**:
   - **Definition**: Dividing a larger network into smaller, manageable subnetworks.
   - **Purpose**: Improves network performance and security by segmenting traffic.

3. **Network Protocols**:
   - **Definition**: Rules and conventions for communication between devices.
   - **Examples**: TCP/IP, HTTP, FTP, DNS.

4. **Network Devices**:
   - **Routers**: Direct data packets between networks.
   - **Switches**: Connect devices within a network and manage data traffic.
   - **Modems**: Convert digital data to analog signals for transmission over phone lines.

## Networking Models

The two primary networking models are the OSI (Open Systems Interconnection) Model and the TCP/IP (Transmission Control Protocol/Internet Protocol) Model. Here’s a detailed explanation of both:

### OSI Model

The **OSI (Open Systems Interconnection) Model** is a conceptual framework that divides network communication into seven distinct layers. Each layer has specific responsibilities and interacts with the layers directly above and below it. The OSI model provides a way to understand and design network protocols and services.

### 1. Physical Layer (Layer 1)

- **Function**: Handles the transmission and reception of raw data bits over a physical medium. It deals with the hardware aspects of network communication.
- **Key Components**: Cables (e.g., Ethernet cables, fiber optics), connectors, network interface cards (NICs), and physical signaling.
- **Protocols and Standards**: Ethernet (IEEE 802.3), USB, DSL, and physical aspects of wireless communication.

### 2. Data Link Layer (Layer 2)

- **Function**: Provides node-to-node data transfer and handles error detection and correction that occurred at the physical layer. It formats data into frames and manages physical addressing.
- **Key Components**: MAC addresses, switches, and bridges.
- **Protocols and Standards**: Ethernet (IEEE 802.3), Wi-Fi (IEEE 802.11), Point-to-Point Protocol (PPP), and Frame Relay.
- **Error Detection and Correction**: Uses techniques such as Cyclic Redundancy Check (CRC) and Automatic Repeat reQuest (ARQ).

### 3. Network Layer (Layer 3)

- **Function**: Manages packet forwarding and routing through logical addressing. It determines the best path for data to travel from source to destination.
- **Key Components**: Routers, logical addressing (IP addresses).
- **Protocols**: Internet Protocol (IP), Internet Control Message Protocol (ICMP), and routing protocols like RIP (Routing Information Protocol), OSPF (Open Shortest Path First), and BGP (Border Gateway Protocol).
- **Addressing and Routing**: Includes IP addressing, subnetting, and packet routing.

### 4. Transport Layer (Layer 4)

- **Function**: Ensures reliable data transfer between devices. It provides error detection, correction, and flow control. It is responsible for end-to-end communication and data integrity.
- **Key Components**: Segments, reassembly, flow control.
- **Protocols**: Transmission Control Protocol (TCP), User Datagram Protocol (UDP), Stream Control Transmission Protocol (SCTP).
- **Flow Control and Error Recovery**: Ensures that data is transferred accurately and in the correct sequence.

### 5. Session Layer (Layer 5)

- **Function**: Manages sessions between applications. It establishes, maintains, and terminates communication sessions.
- **Key Components**: Session management and control.
- **Protocols**: Network File System (NFS), Session Initiation Protocol (SIP), and remote procedure call (RPC).
- **Session Management**: Keeps track of multiple sessions and their states.

### 6. Presentation Layer (Layer 6)

- **Function**: Translates, encrypts, and compresses data. It ensures that data is presented in a readable format and handles data translation between different systems.
- **Key Components**: Data formats, encryption, and compression.
- **Protocols**: Secure Sockets Layer (SSL), Transport Layer Security (TLS), Multipurpose Internet Mail Extensions (MIME), and Extensible Markup Language (XML).
- **Data Translation**: Converts data into formats suitable for the application layer.

### 7. Application Layer (Layer 7)

- **Function**: Provides network services directly to end-user applications. It interfaces with software applications to perform network-related functions.
- **Key Components**: Application services and protocols.
- **Protocols**: Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).
- **User Interaction**: Facilitates communication between software applications and the network.


### TCP/IP Model

The **TCP/IP (Transmission Control Protocol/Internet Protocol) Model** is the foundational framework for the Internet and most modern networking. It simplifies the OSI model by consolidating it into four layers. The TCP/IP model is practical and closely aligned with real-world networking protocols.

### 1. Link Layer

- **Function**: Corresponds to the OSI Physical and Data Link layers. It handles the physical connection and data framing for local network communication.
- **Key Components**: Network interface cards (NICs), switches, and network cables.
- **Protocols**: Ethernet, Wi-Fi, and Point-to-Point Protocol (PPP).

### 2. Internet Layer

- **Function**: Manages logical addressing and routing of data packets. It corresponds to the OSI Network Layer.
- **Key Components**: IP addresses, routers.
- **Protocols**: Internet Protocol (IP), Internet Control Message Protocol (ICMP), and routing protocols like RIP, OSPF, and BGP.
- **Addressing and Routing**: Handles IP addressing and packet routing across networks.

### 3. Transport Layer

- **Function**: Ensures end-to-end communication and reliability. It corresponds to the OSI Transport Layer.
- **Key Components**: Segmentation and reassembly, flow control.
- **Protocols**: Transmission Control Protocol (TCP), User Datagram Protocol (UDP), and Stream Control Transmission Protocol (SCTP).
- **Flow Control and Error Recovery**: Manages data integrity and reliability.

### 4. Application Layer

- **Function**: Provides network services directly to applications. It combines the OSI Application, Presentation, and Session layers.
- **Key Components**: Application protocols and services.
- **Protocols**: HTTP, FTP, SMTP, DNS, and others.
- **User Interaction**: Facilitates interactions between end-user applications and the network.


### Comparison of OSI and TCP/IP Models

- **Layer Count**: OSI has seven layers, while TCP/IP has four layers.
- **Complexity**: OSI is more theoretical and detailed, whereas TCP/IP is more practical and streamlined.
- **Development**: OSI was developed as a comprehensive reference model, while TCP/IP was designed based on practical implementation and real-world use.

Both models are essential for understanding network communication, with OSI providing a detailed theoretical framework and TCP/IP serving as the practical basis for most modern networks.

---




