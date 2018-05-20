
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


### Two Conceptual Models

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

TCP model is a conceptual model referencing the relationship of applications over a network. TCP applies a similiar framework or structure to the OSI model however the TCP version excludes 3 layers opting only to use 4 of the layers. The TCP model is not the same as the TCP protocol as the TCP model is a conceptual model showing how applications communicate over a network, whilst the TCP protocol is a offical  procedure concerned with data streaming and deliverly of data.





|                         |                           |
|-------------------------|---------------------------|
| OSI                     |                       TCP |
|                         |                           |


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
