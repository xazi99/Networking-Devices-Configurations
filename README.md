# Networking-Devices-Configurations
Fault Tolerance
A fault tolerant network is one that limits the number of affected devices during a failure. It is built to allow quick recovery when such a failure occurs. These networks depend on multiple paths between the source and destination of a message. If one path fails, the messages are instantly sent over a different link.
Redundacy is having multiple parts to reach the destination.

#Scalability
A scalable network expands quickly to support new users and applications. It does this without degrading the performance of services that are being accessed by existing users.

# Quality of Service
Quality of Service (QoS) is an increasing requirement of networks today.Congestion occurs when the demand for bandwidth exceeds the amount available.
 Network bandwidth is measured in the number of bits that can be transmitted in a single second, or bits per second (bps).

# Network Security
Securing the network infrastructure includes physically securing devices that provide network connectivity and preventing unauthorized access to the management software that resides on them.
Confidentiality - Data confidentiality means that only the intended and authorized recipients can access and read data.
Integrity - Data integrity assures users that the information has not been altered in transmission, from origin to destination.
Availability - Data availability assures users of timely and reliable access to data services for authorized users.

#Hierarchical Network Design
  #Physical and Logical Addresses
A person's name usually does not change. A person's address on the other hand, relates to where the person lives and can change. On a host, the MAC address does not change; it is physically assigned to the host NIC and is known as the physical address. The physical address remains the same regardless of where the host is placed on the network.
IP addresses contain two parts. One part identifies the network portion.The network portion of the IP address will be the same for all hosts connected to the same local network. The second part of the IP address identifies the individual host on that network. 

#Hierarchical Analogy
On an Ethernet network, the host MAC address is similar to a person's name. A MAC address indicates the individual identity of a specific host, but it does not indicate where on the network the host is located.Ethernet technology generates a large amount of broadcast traffic in order for hosts to communicate.

#Benefits of a Hierarchical Network Design
#Acess Layer
The access layer provides a connection point for end user devices to the network and allows multiple hosts to connect to other hosts through a network device, usually a switch, such as the Cisco 2960-XR or a wireless access point. All devices within a single access layer will have the same network portion of the IP address.
#Distribution Layer
The distribution layer provides a connection point for separate networks and controls the flow of information between the networks.
Distribution layer devices control the type and amount of traffic that flows from the access layer to the core layer.Contains more powerful switches, such as the Cisco C9300 series as well as routers for routing between the networks.
#Core Layer
The core layer is a high-speed backbone layer with redundant (backup) connections.It is responsible for transporting large amounts of data between multiple end networks.
Core layer devices typically include very powerful, high-speed switches and routers, such as the Cisco Catalyst 9600. The main goal of the core layer is to transport data quickly.

#Cloud and Virtualization
 #Cloud and Cloud Services
  #Types of Cloud
Public clouds - Cloud-based applications and services offered in a public cloud are made available to the general population.Services may be free or are offered on a pay-per-use model, such as paying for online storage. The public cloud uses the internet to provide services.

Private clouds - Cloud-based applications and services offered in a private cloud are intended for a specific organization or entity, such as the government. A private cloud can be set up using the private network of an organization, though this can be expensive to build and maintain. A private cloud can also be managed by an outside organization with strict access security.

Hybrid clouds - A hybrid cloud is made up of two or more clouds (example: part private, part public), where each part remains a separate object, but both are connected using a single architecture. Individuals on a hybrid cloud would be able to have degrees of access to various services based on user access rights.

Community clouds - A community cloud is created for exclusive use by a specific community. The differences between public clouds and community clouds are the functional needs that have been customized for the community. For example, healthcare organizations must remain compliant with policies and laws (e.g., HIPAA) that require special authentication and confidentiality.

#Virtualization
#Advantages of Virtualization
One major advantage of virtualization is overall reduced cost:
Less equipment is required - Virtualization enables server consolidation, which requires fewer physical devices and lowers maintenance costs.
Less energy is consumed - Consolidating servers lowers the monthly power and cooling costs.
Less space is required - Server consolidation reduces the amount of required floor space.

#Benefits of Virtualizatuion
Easier prototyping - Self-contained labs, operating on isolated networks, can be rapidly created for testing and prototyping network deployments.
Faster server provisioning - Creating a virtual server is far faster than provisioning a physical server.
Increased server uptime - Most server virtualization platforms now offer advanced redundant fault tolerance features.
Improved disaster recovery - Most enterprise server virtualization platforms have software that can help test and automate failover before a disaster happens.
Legacy support - Virtualization can extend the life of OSs and applications providing more time for organizations to migrate to newer solutions.

#Hypervisors
The hypervisor is a program, firmware, or hardware that adds an abstraction layer on top of the physical hardware. The abstraction layer is used to create virtual machines which have access to all the hardware of the physical machine such as CPUs, memory, disk controllers, and NICs.

Type 1 Hypervisor - “Bare Metal” Approach
Type 1 hypervisors are also called the “bare metal” approach because the hypervisor is installed directly on the hardware. Type 1 hypervisors are usually used on enterprise servers and data center networking devices.
Type 2 Hypervisor - “Hosted” Approach
A Type 2 hypervisor is software that creates and runs VM instances. The computer, on which a hypervisor is supporting one or more VMs, is a host machine. Type 2 hypervisors are also called hosted hypervisors. This is because the hypervisor is installed on top of the existing OS, such as macOS, Windows, or Linux. Then, one or more additional OS instances are installed on top of the hypervisor.

#BINARY NUMBER SYSTEM
# Binary and IPv4 Addresses
