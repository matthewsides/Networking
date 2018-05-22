
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

## Service And Network Applications

### FTP

The File Transfer Protocol (FTP) is a standard network protocol used for the transfer of computer files between a client and server over the internet using a TCP/IP connection on a computer network.  

### HTTP

### SMTP

### POP3

### SSL





https://searchnetworking.techtarget.com/definition/8023
benefits and constraints

talk about osi and tcp and the point of the conceptual models (gives us visualisation, can agree it and share the same information having a common understanding / a way of companys and manufacturers agreeing how it should be done creating standards ensuring they can communicate ways to agree how to solve problems ensuring things support the big picture)

2 conceptual models osi and tcp  (tcp model is a less layered version osi)

tcp protocol is not the same as the model

comparision between two 

tcp sits in the osi model 


conceptual models, osi models, tct model (using a table)

osi application layer talking about system /  networking applications (transferring information etc.)

IEEE (802.3, etc.) standards about physical cabling and transmission of data

mesh topology 

protocols ipv4 (ipv6) ipv4 run out of ip addressess have tech to minimize the number of addressess used /  classic internet protocol
your address on the internet (private addressess not viable in the internet / public avaliable on the internet)


dns (domain name system) -  converts domain names to ip addressess and vice versa (ip addressess to domain names) ask parent dns if dont know (6-7 route dns systems in the world) information constantly updated


To communicate, the computers must have a common language, and they must follow rules so that both the client and the server know what to expect. The language and rules of communication are defined in a communications protocol. All client-server protocols operate in the application layer. The application layer protocol defines the basic patterns of the dialogue. To formalize the data exchange even further, the server may implement an application programming interface (API).[3] The API is an abstraction layer for accessing a service. By restricting communication to a specific content format, it facilitates parsing. By abstracting access, it facilitates cross-platform data exchange.

## Operating Principles (Glossary)

###

•	Networking devices: hubs, routers; switches; multilayer switch, firewall, HIDS, repeaters; bridges; wireless devices; access point (wireless/wired), content filter, Load balancer, Modem, Packet shaper, VPN concentrator.
•	Server types: Web, file, database, combination (e.g MS Small Business Servers), virtualisation and terminal services server


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


