
# Networking 

## Networking Types and Standards

The below sections explain the benefits and constraints of different network types and standards. The purpose of any network is to share resources.

### Peer to Peer

A Peer to Peer network is in essence a conglomerate of computers that distribute and partition tasks or workloads between eachother,sharing resources. The network is termed "Peer to Peer" due to the lenient restraints and permissive nature, distributing or giving equal access to all systems connected to the network.  Peers are inprinciple coequal, or equipotent nodes in a non-hierarchical network.

The network is acknowledged for its simplicity with regards to the ease of set up and flexability, a benefit in using the network as the autonomous aspect grants user's the option to join or leave a network. Whilst the resources required to set up a Peer to Peer encompass; at least two computers, a network adapter for each computer or a cross over cable (cables), network configuration, protocol stack.

In addition the network is robust in the sense that noone is in charge, P2P networks resources are usually distributed across multiple nodes of the network. Although consequently an issue is that some may out or abandon download,though others may still end up getting data download on rest of the nodes in the network.  

### Client server 

The Client-server is a centeralised distrubution network model that partitions tasks or workloads between the providers of a resource or service, called servers, and service requesters, called clients. The client server functions similairly to a request response messaging pattern.The client sends a request, and the server returns a response (exchange of messages is an example of  inter-process communication).

A benefit of a Client-server network is that the access, resources and integrity of the data are controlled by a dedicated server ensuring that  a program or unauthorised clients cannot damage the system. This centralization also facilitates task of updating data or other resources (better than the networks P2P). 

Whilst the server and clients capacity can be increased seperately, with any element enhanced at any time, or new nodes being added to the network (client or servers).The Client -server also heralds easy maintenance with the distribution of roles and responsibilities spread across several standalone computers. While it is plausable to replace, repair, upgrade, or move a server, during run time with customers minimally affected.This independence of the changes is also known as encapsulation.

Though a problem in the paradigm (model) Client-server is traffic congestion, simultaneous clients sending requests to the same server might cause many problems (to more customers, more problems for the server). On the contrary, P2P networks each node in the network server also makes more nodes, the better bandwidth you have (node - computer). 

Moreover the Client - server network due to the Classic centralisation, does not have the robustness of a network P2P.This is because as there is only one hub, when the hub is down, customer requests cannot be met.


### Cloud 

The Cloud is referred to as a computer network that exists within or is part of a cloud computing infrastructure.A  cloud is a collection of computer systems.Cloud computing fudementally refers to the storage and accessing of data and programs over the internet instead of through a computer's harddrive.The cloud's benefits stem from the collaborative nature, allowing the alteraction of a document simintanouseasly or in real time.

However a disadvantage of using cloud is that internet access is required, otherwise the information stored is unattainable. Whilst in certain instances storing files on the cloud may require a form of capital, the payment scheme is usually a monthly or yearly plan that opts to establish the pricing based on the amount of storage allocated. In addition failure to supply capital and meet deadlines, generally leads to a foreclosure of the space charted, meaning that the information stored will not be available unless a payment is made.Though the information is inaccessible it should still be stored for a pre-set amount of time until the company hosting the data can confirm that the user may either no longer make payments or that the data stored is no longer credible to the user. 

### Cluster

Cluster differs from Cloud and Grid in that a cluster is a group of computers connected by a local area network (LAN), whereas cloud and grid are more wide scale and can be geographically distributed. The networked computers essentially act as a single, much more powerful machine. A computer cluster provides much faster processing speed, larger storage capacity, better data integrity, superior reliability and wider availability of resources.

However a disadvantage of a cluster network (computer clusters) is that it is not cost efficent, costing more to implement and maintain. This results in much higher running overhead compared to a single computer.

### Centralised

A Centralised network is essentially a type of network where all users connect to a central server, which is the acting agent for all communications. This server would store both the communications and the user account information. The central server, in turn, is responsible for delivering application logic, processing and providing computing resources (both basic and complex) to the attached client machines. The benefits of using a centralised network include; less network interaction to fetch data (fast), ease of management (only a single management node) and could be automatized (though could also be regarded as a disadvantage depending on the situation).

Though the implications of a centeralised network stems from there being only one single point of failure, meaning that if the server is down for various reasons, user's will not be able to access said data until the server is fixed. Whilst as alliterated there is only one central server in a network thus leaving it vulnerable and making it easier for hackers to attain information since it is stored in one place, this is particularly crucial with regards to an organisation setting where valuable user information is being held or required to be stored.

### Virtualised  

Network virtualisation  is the process of combining hardware and software network resources and network functionality into a single, software-based administrative entity, a virtual network. Network virtualisation is designed to allow network optimization of data transfer rates, flexibility, scalability, reliability and security. Network virtualization is especially useful for networks experiencing a rapid, large and unpredictable increase in usage. This is due to the seperation of   available bandwidth into independent channels, which are assigned, or reassigned, in real time to separate servers or network devices.

The intended result of network virtualization is improved network productivity and efficiency, as well as job satisfaction for the network administrator.

## Two Conceptual Models

There are two conceptual models applied, the reason for theses models is to ensure a general consensous as to how something should be done is formed between organisations. The models essentially give a visualisation to the proccess and standards that should be followed thus ensuring communciation and enabling organisations to agree on how to solve problems ensuring that the bigger picture is supported.

![Alt text](https://github.com/matthewsides/Networking/blob/master/TCP_OSI_Models.png?raw=true "Optional Title")


### OSI 

The Open systems interconnection model is an conceptual framework referencing relationships, demostrating how applications communicate over a network. OSI model's main concept is that the process of communication between two endpoints in a network can be divided into seven layers. In this architecture each layer serves the layer above it and, in turn, is served by the layer below it.

|         |                   |                                                  |
|---------|-------------------|--------------------------------------------------|
| Layer 7 | Application Layer | The Applcation Layer is a medium for applications to access a network. The layer specifies and provides communication through the use of protocols, for instance the hyper text transfer protocol (HTTP) a type of hyper text, which is used for all web based languages (HTML, Java,PHP, etc.) transferred across a network. Whilst another example would be the simple mail transfer protocol used (SMPP) a protocol applied to emails. |
| Layer 6 | Presentation Layer| The Presentation Layer essentially interprets the format.This means that the file type (jpeg, html ,etc)  is identified and if required converted, decrypted or compressed during this phase.                                               |
| Layer 5 | Session Layer     | The Session Layer essentially establishes communications or sessions between systems or servers, also terminating when requested or necessary. The Session layers services also include authentication and reconnection after an interruption. |
| Layer 4 | Transport Layer   | The Transport layer manages packetisation (seperation into segments and recapsulation) of data and the delivery of the packets, including checking for errors in the data upon arrival. TCP and PCP are fudemental protocols generally used during this phase, developed in the 1960's by the department of defense ARPanet and made open source. Apple and other companies attempted to create there own protocols however they were not well recieved as people did not want to to become dependant on them, hence the reason TCP and PCP are primarly used. TCP's main funcitons consist of breaking up data or chopping data into segments, this is done to ensure that if somthing goes wrong not all the information is lost, whilst it is also more efficent and quicker. TCP also gives each segment a number or ID for rebuilding the information. In order for the data to be reassembled into information it needs a tag, puts at least 4 pieces of information as a header. Every segment will have a sequence number thats how it puts itself together on the other side. |
| Layer 3 | Network Layer     | The Network layer or IP, which is the network layer for the internet handles addressing and routing the data,  sending it in to the right destination on outgoing transmissions and receiving incoming transmissions at the packet level.      An IP address is 4 bytes generally looking like this: 00000000.00000000.00000000.00000000, each number cannot go over 255 (IP V4). Though four billion is concieved as not  enough anymore  hence  the release of IPV6. |
| Layer 2 | Data Link         | The Data Link Layer sets up links across the physical network, transfering data between adjacent network nodes in a wide area network (WAN) or between nodes on the same local area network (LAN) segment (performs the most reliable node to node delivery of data).Data bits are encoded, decoded and organized in the data link layer.|
| Layer 1 | Physical          | The physical layer is responsible for sending computer bits from one device to another along the network. The layer does not understand the bits, however is tasked with setting up physical connections over a network (node to node) and determining how the bits are represented. |

### TCP

TCP model is a layered protocol similiar to the OSI model, however TCP  excludes 3 of the OSI layers, though the layers are equivalent in operation and function. The network access layer is equivalent to OSI layers 1 and 2. The Internet Protocol layer is comparable to layer 3 in the OSI model. The Transport layer is equivalent to OSI layer 4. These are the TCP and UDP (user datagram protocol) functions. Finally, the application layer is similar to OSI layers 5, 6, and 7 combined. 

The TCP model is not the same as the TCP protocol as the TCP model is a conceptual model showing how applications communicate over a network, whilst the TCP protocol is an offical  procedure concerned with data streaming and deliverly of data.

|            |                   |                                                                                                     |
|------------|-------------------|-----------------------------------------------------------------------------------------------------|
| Layer 4    | Application Layer | The Application Layer is concerned with providing network services to applications. There are many application network processes and protocols that work at this layer, including HyperText Transfer Protocol (HTTP), Simple Mail Transport Protocol (SMTP) and File Transfer Protocol (FTP).|
| Layer 3   | Transport Layer    | The Transport Layer is concerned with the transmission of the data. The two main protocols that operate at this layer are Transmission Control Protocol (TCP) and User Datagram Protocol (UDP). TCP is regarded as being the reliable transmission protocol and it guarantees that the proper data transfer will take place. UDP is not as complex as TCP and as such is not designed to be reliable or guarantee data delivery (UDP does not check to see whether data has arrived). |
| Layer 2  | Internet Layer     | The Internet  layer contains the packet construct that will be transmitted. This takes the form of the Internet Protocol (IP) which describes a packet that contains a source IP Address, destination IP Address and the actual data to be delivered. |
|Layer 1   | Network access Layer| The Network access layer is the lowest level of the TCP/IP protocol stack and functions carried out here include encapsulation of IP packets into frames for transmission, mapping IP addresses to physical hardware addresses (MAC Addresses) and the use of protocols for the physical transmission of data. |


### Model Differences  

|                         |                           |
|-------------------------|---------------------------|
| OSI                     |                       TCP |
| OSI is a generic, protocol independent standard, acting as a communication gateway between the network and end user.| TCP/IP model is based on standard protocols around which the Internet has developed. It is a communication protocol, which allows connection of hosts over a network.|
| The OSI models transport layer guarantees the delivery of packets. | In the TCP/IP model the transport layer does not guarantee the  delivery of packets. However it is generally seen as more reliable.  |
| Follows vertical approach.| Follows horizontal approach.                          |
| OSI model has a separate Presentation layer and Session layer. |TCP/IP does not have a separate Presentation layer or Session layer.|
|Transport Layer is Connection Oriented. | Transport Layer is both Connection Oriented and Connection less.|
| Network Layer is both Connection Oriented and Connection less. | Network Layer is Connection less.       |
| OSI is a reference model around which the networks are built. Generally it is used as a guidance tool.|TCP/IP model is, in a way implementation of the OSI model.|
|Network layer of OSI model provides both connection oriented and connectionless service. | The Network layer in TCP/IP model provides connectionless service.|
| OSI model has a problem of fitting the protocols into the model. | TCP/IP model does not fit any protocol. |     
| OSI model defines services, interfaces and protocols very clearly and makes clear distinction between them. It is protocol independent.                                                             | In TCP/IP, services, interfaces and protocols are not clearly separated. It is also protocol dependent.
| It has 7 layers                          | It has 4 layers                               |


### IEEE (802.3,.7,.8,.11) standards about physical cabling and transmission of data

802.3 is a standard specification for Ethernet, a method of physical communication in a local area network (LAN), which is maintained by the Institute of Electrical and Electronics Engineers (IEEE). The 802.3 standard essentially specifies the physical media (cables) and the working characteristics of Ethernet. 

802.7 is a sub-standard of the IEEE 802 which covers broadband local area networks pratices.it specifies the design, installation, and test parameters for a broadband cable medium.

802.8 was established to assess impact of fiber optics and to recommend standards.

802.11 is a set of media access control (MAC) and physical layer (PHY) specifications for implementing wireless local area network (WLAN) computer communication in different frequency bands.


### Routed Protocols (IPV4,IPV6)

Routed protocols are defined as a protocol in which data can be routed. The most notable protocols consist of IPv4 and IPv6. IPv4 is the fourth version of the Internet Protocol, used for data communication over different kinds of networks. Though IPv4 was recently replaced 
by IPv6, this was due to the limitations regarding IPv4's pool as IPv4 uses 32-bit addresses and is limited to 4,294,967,296 addresses.






address issues of IPv4 & IPv6, Global unicast, Multicast, Link local, Unique local, EUI 64 & Auto configuration

## Impact of Topologies and differences

### Logical Topologys

A logical topology is a concept regarding the arrangement of devices on a computer network and how they communicate with one another (protocols).Through utilising network equipment (routers, switches, etc.) the logical topology of a network can be dynamically maintained and reconfigured. 

 Types of logical Topologies: 

 • Ring: The ring topology is a logical network in which each node connects to two other nodes  forming a single continuous pathway for signals through each node . In the ring topology  only one node is allowed to transfer the data in a network at a given time. This mechanism is achieved by token (the node having token only can transmit the data in a network) and hence the collision can be avoided in a network.

 • Bus: Ethernet uses the logical bus topology to transfer data. Through  a bus topology a node broadcasts the data to the entire network. All other nodes on the network recieve the data and check if the data is intended for them.
 
 
### Physical 

A physical topology refers to the arrangement or layout of computers, cables, and other components on a network (LAN). The use of a physical topology allows for the organisation of a network, through physically laying it out in relation to the enviroment (office,home,etc.) and requires prior planning.

Types of Physical Topologies: 

 • Star:  Network topology is the topological structure of a network and may be depicted physically or logically. A star network consists of one central hub (switch, router, hub,etc.) which acts as a conduit to transmit messages. In the star topology, every host (node) is connected to a central hub.
 
 • Mesh: A mesh network is an cooperative network topology where nodes connect directly , dynamically and non-hierarchically to as many other nodes as possible to efficently route data to and from clients. 
 
 • Ring: The ring topology is a network in which a node connects to two other nodes thus forming a circular and singular continous pathway for signals to pass through each node.  In the ring topology  only one node is allowed to transfer the data in a network at a given time. This mechanism is achieved by token (the node having token only can transmit the data in a network) and hence the collision can be avoided in a network.
 
 • Bus: A bus network is an network arrangement in which each node (workstation or other device) is connected to a main cable or link called the bus, with terminators on each end/side of the bus that absorbs signals ensuring that they do not reflect back down the line. 
 
 • Tree: A tree network, is a hybrid network topology in which star networks are interconnected via bus networks (the star networks are the branches of a bus network).
 
### Physical and Logical Difference

The underlying difference between a logical topology and a physical topology is that a physical topology is how the wires are interconnected, whilst a Logical topology is how the network behaves and inter-operates. Logical typologies tend to focus on traffic flows, routing domains, router peering, control points, IP addressing schemes, network segmentation, administrative domains, etc. Whilst Physical tend to focus on port names, port counts, what cables connect to where, what specific models are used, etc. Essentially the topologys are different ways of illustrating network architecture.

### Communication

Data communications refers to the transmission of data between two or more nodes over a computer network.The physical connection between networked computing devices is established using either cable media or wireless media. The best-known computer network is the Internet. A common proccess regarding data communication and transmissions can be seen through a user requesting information from a server, the router re-directing to the server with the server retrieving the file requested and sending the data back.

In a networking model for instance OSI or TCP/IP the communication of data between nodes occurs through layers. Theses layer each decide most appropriate protocol to use (application layer), quickest pathway (network layer) , format and compression (presentation or transport depending on the model applied), setting up communciation between hosts (session layer). The application of theses layers aid the communication of data through monitoring the data transfer, communicating with the host, ensuring that data is successfully retrieved.

Important considerations in data communication is how fast data is sent and recieved, in bit per second, over a channel. Bandwidth is one of three factors data rate is dependent upon. Though transmission channels usually have limited frequency bandwidth.These limitations arise from the physical properties of the channel or from deliberate limitations on the bandwidth to prevent interference from other sources. Systems typically attempt to maximise the amount of data that can be sent on a channel, primarily for economic reasons.

## Service And Network Applications

### FTP

The File Transfer Protocol (FTP) is a standard network protocol used for the transfer of computer files between a client and server over the internet using a TCP/IP connection (on a computer network). FTP is a client-server protocol that requires  two communications channels between client and server: a command channel for controlling the conversation and a data channel for transmitting file content.

### HTTP

Hypertext Transfer Protocol (HTTP) is an application protocol used by the World wide web as the foundation of data communciation. The foundation of data communication relating to HTTP being the standards or rules set when transferring files on the World Wide Web. Hyper transfer Protocol helps format and connect user's to webpages, running on top of the TCP/IP suite of protocols.

### SMTP

Simple mail trasfer Protocol is a standard protocol for sending emails accross the internet (server to server). Email servers generally apply this protocol sending messages to eachother that can be collected through a client.

### POP3

In computing, the Post Office Protocol (POP) is an application-layer Internet standard protocol used by e-mail clients to store and retrieve e-mail from a server in an Internet Protocol (IP) network. POP3 is a subset of the Post Office Protocol being the third version used for the widespread method of receiving and filtering email.

### SSL

The Secure Sockets Layer is a  security method used for establishing an encrypted link between a web server and a browser. This link ensures that all data passed between the web server and browser remains confidental and integral. This is commonly used for online commerce as payment methods include using cards for online transactions or profile credentials such as a password, as such information being leaked could cause numerous problems (identity theft, stolen property/money, etc.).

## Operating Principles (Glossary)

### Networking devices

#### hubs

A hardware device that contains multiple independent but connected modules of network and internetwork equipment. Hubs can be active (where they repeat signals sent through them) or passive (where they do not repeat but merely split signals sent through them).

#### routers

A device that routes information between interconnected networks. The router determines the best path to route a message,translating information from one network to another. The majority of now contain firewalls. Home routers can contain firewall, router, switching (for cabled connections), and a wireless access point.

#### switches

A switch is an "intelligent" type of hub, in that it sends packets only to the intended ports, rather than all computers on the network. The switch recieves data packets and re-routes them to there intended destination, using only the traffic requested thus eliminating the possibility of collision.

#### multilayer switch

A multilayer switch is a network device with the same capabilties of a switch but with the additional functionality and features of a router. The multilayer switch  can perform at incredibly fast speeds in comparision to a switch.

#### Firewall

A security device which inspects traffic entering and leaving a network, and allows or disallows the traffic, depending on the  rules set regarding the use of the network, by filtering out unwanted packets. The firewall is usually positioned as the gateway device to another network, such as the internet (behind the router).

#### HIDS

A host-based intrusion detection system (HIDS) is an intrusion detection system that is capable of monitoring and analyzing the internals of a computing system as well as network packets to ensure any malicious data is prevented from entering the network via the internet.

#### repeaters

A device used in a network to strengthen a signal as it is passed along the network cable. The use of a repeater can extend a LAN beyond its limits.

#### Bridges

The Bridge is a Device that connects and passess packets between two network segments that use the same communications protocol.

#### Wireless devices

A wireless device is a device that requires no wiring to connect to a network, opting to use signals to connect to the internet. Whilst wireless devices can also relate to the extensions or peripheral hardware in a network used to connect devices to the internet or network like an access point or wireless router.

#### Access point (wireless/wired)

A wireless access point is an extension for the router (can be stand alone or intergrated into the router) usually used to cover dead spots in wifi, areas where the wifi could not reach. An access point essentially acts as a gateway for wireless devices to connect to a network providing connectivity and wifi coverage (extending the range).

#### Content filter

A Content Filter is software that helps decide which content is acceptable for viewing and access through a given system. Filtering any data that is considered spam or harmful, used for security purposes to lower the possibility of malware being contracted from malicious sites.

#### Load balancer

A load balancer essentially imporves the distribution of work loads, efficiently distributing incoming network traffic across a group of backend servers. Load balancing improves; reliability, responsiveness and increases availability of applications.

#### Modem 

The Modem is a Device for transmission that converts digital and analog signals. Modems allow computer data (digital) to be transmitted over voice-grade telephone lines (analog).

#### Packet shaper

The packet shaper is a device that sits in between the internal network and external network. All incoming and outgoing traffic passes through it. Its purpose is to classify the traffic passing through, and prioritize that traffic based on pre-set rules defined.

#### VPN concentrator

A VPN concentrator is a type of networking device that provides secure creation of VPN connections and delivery of messages between VPN nodes. It is a type of router device, built specifically for creating and managing VPN communication infrastructures. 

### Server types

#### Web

A web server distributes content to a user through the internet as it is requisitioned. The content is recieved via the user sending a request to the web server through using HTTP, which then  retrieves the relevant information or HTML page sending it to the web browser or an error message if unable to do so.The web server runs using the HTTP protocol (and seven other protocols) to processes incoming network requests.

#### file

A file server is a computer responsible for the central storage and management of data files so that other computers on the same network can access the files. A file server allows users to share information over a network without having to physically transfer files by  external storage devices.

#### database

A database server is a computer program that provides database services to other computer programs or to computers, allowing the retieval and access of files stored on a database. Access to the server can be done through either front or back end, running through the server or a local node. Once the information is retrieved it is outputted to the user requesting the data.

#### combination 

A combination server is a server that incorporates functions of multiple types of servers (database,web,file,etc) and is capable of achieving what those servers can do, providing all the services but as a singular server. 

#### virtualisation 

Virtualisation involves partitioning a physical server into a number of small, virtual servers (a server that shares hardware and software resources with other operating systems) with the help of virtualization software. In server virtualization, each virtual server runs multiple operating system instances at the same time.


#### terminal services server

A terminal server is a server or network device that enables connections to multiple client systems to connect to a LAN network without using a modem or a network interface, as long as the system has a port. Terminal servers can be used to take control of a remote computer or virtual machine over a network connection.

### Work Station Hardware

#### Interdepence of hardware with relevant networking software

Software essentially controls the hardware.These two components are complementary and cannot act independently of one another. In order for a node/device to effectively manipulate data and produce useful output, its hardware and software must work together. Without software, the hardware would be useless. Conversely, software cannot be used without supporting hardware.For example Server software is a type of software that is designed to be used, operated and managed on a computing server.Server software is integral when interacting with a server’s hardware infrastructure (processor, memory, storage, input/output (I/O), etc.), utilising the server for different functions and services, though primary using inherent computer capacity and resources to complete tasks. Incomparision client software is software that resides in a user's desktop or  device, contrast with server software. The client software is used to provide services or retrieve and utilise services provided by the server, providing an interface for the user to interact with these services. The hardware aspect and interdepence on the networking software relates to retieiving and displaying information/data taken from a server.

A server operating system (OS) is a type of operating system that is designed to be installed and used on a server computer. The server operating system optimises the server computer to run as efficently as possible as multiple user's may access and request something at a given time. It is an advanced version of an operating system having features and capabilities required within a client-server architecture.

The Client Operating System is a system that works within computer systems and various portable devices. This system is different from centralized servers (server operating system) because it only supports a single user and does not require stretching resources to meet multiple requests.

A firewall is a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules. The firewall is typically based on the  host or network. A host based firewall is used to monitor ingoing and outgoing signals. A network-based firewall can be built into the cloud's infrastructure, or can be a virtual firewall service.

Whilst a proxy server is a server that acts as an intermediary (gateway) for requests from clients seeking resources from other servers.  A proxy server may reside on the user's local computer, or at various points between the user's computer and destination servers on the Internet. The proxy server provides increased performance and security.

#### Network comparision

A Network Interface Card , these cards connect directly into the motherboard of a computer, featuring an external network socket. This enables the computer to connect to a network via a network cable. Network cards let a computer exchange data with the network, using suitable protocols to achieve connection (for example CSMA/CD).

Wireless networks are networks that do not rely on cables to connect to a network but rather opts to use radio waves, an implementation that occurs  on the physical level of network structure.

A mobile network is a communication network where the last link is wireless. The network is distributed over land areas called cells, each served by at least one fixed-location transceiver. These base stations provide the cell with the network coverage which can be used for transmission of data. A cell typically uses a different set of frequencies from neighboring cells, to avoid interference.

The underlying differences between a network card, wireless and mobile is essentially the proccess as a networking card, wireless and mobile are all used in the transmission of data, communication and connectivity. The proccess refering to the physical set up and how each one acheives its purpose. For instance a network card is intergrated into a motherboard and then ustilises cabling to connect to a network. In comparision wireless is external and requires no cabling to function also connecting devices to a network, thus achieving the same outcome with different methods or techniques. Whilst with regards to the cellular (mobile) and wireless network, both use a wireless form, though radio waves are used within the wireless network, whilst  cellular requires a dedicated control channel for transmitting digital information. 

#### Cable comparision

Structured cabling refers to the standardised  architecture, components and infrastructure for communications. Structured Cabling is a type of infrastructure that supports the performance of an organisations network. It is used for connecting multiple electronic devices and to better layout the physical hardware (cables) in the applied enviroment. A structured cabling system also provides an environment for data transfers that integrates telecoms networks, local or networked computer systems, video surveillance, and security. 


the different type of cabling (infrastructure, patch, networking, shielded and twisted pair)

#### Permissions


Review the need for permissions (explain the difference between local permissions NTFS and network shared permissions ) 
Local workstation architecture e.g. memory, processor, I/O devices - include a small section on the system bus and how this works (in simple terms CPI->Memory->IO->Data->Control)

#### Local Workstation Architecture







## Network Design

### Introduction

This documentation details the design and implementation of a wide area network through the use of two local area star networks, configured to connect and communicate via routers. Further improvements are also noted for potentional future implementation.

### Scope 

This documentation is intended to be read by the network engineers, whom partook in the development, set up or currently tasked with the maintainence of this network. Other intended readers include share holders in the prospective project.


### Network Specification

Tasked with designing, testing, implementing and maintaining a wireless area network encompassing two local area networks, theses networks must incorparate:

 • A star topology format
 
 • 3 PC's 
 
 • 1 Server
 
 • 1 Printer
 
 • 1 Router
 
 • Wireless access (wireless router/access point choice optional)
 
 • Functional (Capable of pinging same/cross network, etc)
 
 ### User Stories
 
  •  As a user I would like to be able to ping to another computer on the same network (LAN).
  
  •  As a user I would like to be able to ping cross network (LAN1-LAN2).
  
  •  As a user I would like to be able to print.
  
  •  As a user I would like to be able to ping a server (same/cross network).
 
### Network Architecture

The networks layout utilises the star topology, leaving one central hub acting as a conduit to transmit messages.Which in this instance is a switch.  Each of the networks physical hardware is connected using standard copper wiring and both local area networks are capable of cross network communication using a router as a gateway. Moreover each network includes an access point and is (a portal) capable of connecting wireless devices if necessary. Both networks are mirrored including one server and three PC's each, each set to be configured using a DCHP IP address taking from a pool with a pre-set range, exempt the server which will use a static IP.


![Alt text](https://github.com/matthewsides/Networking/blob/master/Network_Diagram.png?raw=true "Optional Title")


### Pre-Set Network Configurations-

LAN-1

PCs IP: • 192.168.1.100 • 192.168.1.101 • 192.168.1.102

Server IP: •192.168.1.10

Router IP: •192.168.1.1

LAN-2

PCs IP: •192.168.10.100 •192.168.10.101 •192.168.10.102

Server IP: •192.168.10.10

Router IP: •192.168.10.1


### Justification Network Design 

The network Architecture and functionality was influenced and had to conform to the set requirements given, however certain aspects were optional, whilst all the design can be justified based on the networks use.

The underlying reason behind using the star topology is due to its commonality in homes and offices. In this instance the network required two local area networks for a home-esc enviroment, connected and capable of transmission between the networks (WAN). A switch was applied rather than a hub due to the functional differences, a switch sends data only to the specified system on a LAN, whilst a hub would transmit copies to all the systems thus making it unsuitable as the systems and network is private.

Copper wiring was used due the wire being cheaper to set up than fibre optic cabling and although copper is known to degenerate over long distances since the network is set up for a home-esc environment the wires are not required to be long. Wireless access was also requirement however it was not specified whether the router was to have wireless intergrated (wireless router) or an extension, hence a wireless access point was acquired and used instead. A Wireless access point was included in the design instead of a router due to the coverage given over a home or office space and ability to cover wifi dead spots in the network. 

A printer was included in the network with the assumption that printing will be a common occurence or required. Whilst the inclusion of a server is to ensure that access is provided to data accumulated from the three connecting PC's and printer. The router, critical to the networks design is for cross network communication providing a gateway.


### User Feedback

Name: Joe

Feedback:

The design is simple, following the star topology format. The Network can send files to other computers fairly fluidly. However the printer does not seem to be configured (IP).


Name: Luke

Feedback:

Both the networks are intuitive using the star topology, whilst a computer can ping other computers. The only downside and possible addition is the exclusion/inclusion of a firewall which adds an extra layer of security.




### Test

The following tests were to ensure that the network functioned in accordance to the specifications and in a logical manner:

[Test Plan](https://github.com/matthewsides/Networking/blob/master/Network_Test.xlsx?raw=true)

![Alt text](https://github.com/matthewsides/Networking/blob/master/Test_Plan_IMG.png?raw=true "Optional Title")


### System Implemented

The below diagram shows the implemetented version of the conceptual design covered above, along with notes pertaining to the configuration of each device.

![Alt text](https://github.com/matthewsides/Networking/blob/master/Network_WAN.png?raw=true "Optional Title")

### Evalutation

The network  factoring in on the feedback and upon review, though meets the requirements could have been improved as the use of the star topology required more cable length than a linear topology. In a small area, in this scenario a home, the wires could prove haphazardous. Whilst if the switch (concentrator/hub) fails, nodes attached are disabled.This means that the hardware is centralised and  depedant on the switch and unaccessable if the switch fails with no failsafe currently in place. In addition with regards to expanding the network the use of copper wire could prove strenuous as copper is known to degenerate over long distances, thus if applied to a larger enviroment the network would either not work or fail to perform. For further improvement the wires could be substituted, while not required the topology could also be changed. In relation to the security of the network the network is currently vulnerable thus would probaly require a firewall to filter and stop foreign data packets from entering the network.


