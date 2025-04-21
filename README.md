# Networking-journey-in-one-git
<a name="top"></a>

## Introduction

Hi, I'm Mysthological, network engineer embarking on a journey to master network architecture and cybersecurity. I'm excited to contribute to open-source projects, learn from the community, and share my own experiences throughout the years. Let's collaborate and build a stronger, more secure digital world together!. Most importantly, never take anything for granted.

## Additional Resources
### Books
-[Computer Networks - A Tanenbaum - 5th edition](https://csc-knu.github.io/sys-prog/books/Andrew%20S.%20Tanenbaum%20-%20Computer%20Networks.pdf)

-[Network Security Essentials: Applications and Standards](https://www.emgywomenscollege.ac.in/templateEditor/kcfinder/upload/files/Network-security-essentials.pdf)

-[network warrior](https://github.com/InspectorDidi/Hacking-Books/blob/master/Network%20Warrior%2C%202nd%20Edition.pdf)

-[Computer Networking: a Top-Down Approach (8th ed.)](https://gaia.cs.umass.edu/kurose_ross/lectures.php)

-[Computer Networking: A Top-Down Approach 7th Edition ](https://www.ucg.ac.me/skladiste/blog_44233/objava_64433/fajlovi/Computer%20Networking%20_%20A%20Top%20Down%20Approach,%207th,%20converted.pdf)
-[Computer Networks: A Systems Approach](https://book.systemsapproach.org/)

-[CS 168 Textbook](https://textbook.cs168.io/intro/intro.html)

-[networking-practical](https://www.youtube.com/playlist?list=PLowKtXNTBypH19whXTVoG3oKSuOcw_XeW)

-[An Introduction to Computer Networks](https://intronetworks.cs.luc.edu/current/ComputerNetworks.pdf)

### Links
-[cs-168-spring-2025](https://sp25.cs168.io/) \
-[The TCP/IP Guide](http://www.tcpipguide.com/free/t_toc.htm) \
-[Primer](https://hpbn.co/#toc)

## Table of Contents :
 - [Prerequisites](#Prerequisites).
 - [what is Networking](#what-is-Networking).
     -[Protocols](#Protocols).
-[OSI](#OSI-Model)
-[The Internet Design Principles](#The Internet Design Principles)


## Prerequisites
Before knowing what is netwroking we need to ask ourselves why do we need networking? As I told before do not take anything for granted but fortunately we took it for granted. And now here we're curious enough to deep dive into the history of networking. Let me give you a roadmap first to understand the past:

```
    title Evolution of Computer Networking
    
    section Pre-Networking Era
        1950s : Time-Sharing Systems emerge
              : Multiple terminals share computing resources
    section Early Networking
        1969 : ARPANET launched
             : First packet-switched network
        1971 : First email sent over ARPANET
    section Network Expansion
        1973 : Ethernet invented
             : Operated at 2.94 Mbps
        1977 : TCP/IP developed
             : Enables network intercommunication
        1983 : TCP/IP replaces NCP
             : Modern Internet foundation established
    section Commercial Development
        1989 : ARPANET decommissioned
             : NSFNET becomes backbone
        1990 : First commercial ISP launched
             : Internet opens to public
        1991 : World Wide Web released
             : Mass adoption begins
    section Modern Era
        1997 : Wi-Fi introduced
             : Wireless networking emerges
        1999 : Gigabit Ethernet
             : High-speed networking standard
```         
Computer networking has evolved dramatically over the past six decades, transforming from simple time-sharing systems to the complex global infrastructure we know today. Let's explore this journey chronologically.

### Pre-Networking Era (1950s)

The earliest precursor to computer networking emerged in the 1950s with [time-sharing systems](https://cdn.shopify.com/s/files/1/0106/6339/5391/files/1024x576-1_28d3d765-4fdf-4bef-b1e6-3fc59eb18ed9_1024x1024.jpg?v=1675328680). These systems allowed multiple terminals to share computing resources simultaneously, though they couldn't communicate directly with each other. Each terminal consisted of a monitor and keyboard connected to a central computer through controlling routes.

### Early Networking (1960s)

#### The modern era of networking began during the Cold War period, driven by military necessity. Key developments included:

- [Paul Baran](https://en.wikipedia.org/wiki/Paul_Baran) and [Donald Davies](https://en.wikipedia.org/wiki/Donald_Davies) independently proposed [packet-switching technology](https://en.wikipedia.org/wiki/Packet_switching), where data would be broken into packets and transmitted efficiently through networks.
- ARPANET was conceived as the first practical implementation of packet-switching, becoming the foundation of modern Internet infrastructure.
- The Network Control Protocol (NCP) was developed as ARPANET's first transport protocol.
### Network Expansion (1970s)

Several significant advances marked this decade:

- [Robert Metcalfe](https://en.wikipedia.org/wiki/Robert_Metcalfe) invented Ethernet at [Xerox PARC](https://spectrum.ieee.org/xerox-parc) in 1973, initially operating at 2.94 Mbps.
- TCP/IP was developed in 1977, enabling different networks to communicate with each other.
- Satellite links connected international computers to ARPANET, marking its global expansion.

### Commercial Development (1980s-1990s)

This period saw the transition from academic to commercial networks:

- [ARPANET](https://en.wikipedia.org/wiki/ARPANET) was decommissioned in 1989, replaced by [NSFNET](https://icannwiki.org/National_Science_Foundation_Network) as the Internet backbone.
- "The World" became the first commercial ISP founded by Joel Furr in 1989. 
-  The World Wide Web invented by  [Tim Berners-Lee](https://en.wikipedia.org/wiki/Tim_Berners-Lee) while at CERN in 1989, released in 1991 revolutionized public access to Internet resources.

### Modern Era (Late 1990s-Present)

Recent developments have focused on speed and accessibility:

- Wi-Fi emerged in 1997, enabling wireless connectivity.
- Gigabit Ethernet was introduced in 1999, providing high-speed networking capabilities.
- Modern networks support emerging technologies like 5G, Wi-Fi 6, cloud computing, and IoT devices.

## Future

Modern networking continues to evolve rapidly, driven by increasing demands for higher speeds, lower latency, and greater connectivity.

### Core Technologies Driving Future Networks

#### 5G Networks

- Ultra-low latency (as low as 1ms) enabling real-time applications
- Massive machine-type communications supporting billions of IoT devices
- Enhanced mobile broadband for widespread high-speed connectivity
- Network slicing for customized performance and security profiles

#### Wi-Fi Evolution

- Wi-Fi 6 and Wi-Fi 7 bringing unprecedented speeds and capacity
- Improved performance in dense environments
- Enhanced security features and power efficiency
- Better integration with cellular networks

#### Quantum Networking

- Development of quantum-resistant cryptography
- Secure quantum key distribution networks
- New security paradigms for sensitive data transmission
- Early adoption in financial and government sectors

### Emerging Applications

#### Internet of Things (IoT) Integration

- Smart cities infrastructure
- Industrial automation and manufacturing
- Healthcare and medical devices
- Home automation and consumer electronics

#### Cloud Computing Evolution

- Edge computing reducing latency
- Distributed cloud architectures
- Hybrid cloud environments
- Serverless computing models

#### Extended Reality Networks

- AR/VR/MR infrastructure
- Immersive entertainment platforms
- Remote presence applications
- Virtual training environments

### Infrastructure Evolution

#### Software-Defined Networking (SDN)

- Programmable network architecture
- Centralized management and control
- Dynamic traffic routing
- Enhanced security controls

#### Edge Computing

- Reduced latency through local processing
- Improved real-time application performance
- Enhanced privacy and security
- Better support for IoT devices

#### SD-WAN Adoption

- Application-aware routing
- Optimized WAN performance
- Simplified branch networking
- Cost-effective connectivity solutions

### Future Challenges and Opportunities

#### Security Considerations

- Zero-trust architecture adoption
- AI-powered threat detection
- Quantum computing impact on encryption
- IoT device security

#### Environmental Sustainability

- Energy-efficient networking equipment
- Reduced carbon footprint
- Green networking protocols
- Sustainable infrastructure design

#### Social Impact

- Digital divide reduction
- Universal connectivity initiatives
- Remote work infrastructure
- Education and healthcare accessibility

The future of networking represents a complex interplay between technological advancement, societal needs, and environmental responsibility.But personally I think It'll lead us to absolute chaos.

## what is Networking

In simple term, Networking is connecting devices(nodes) together to share resources and exchange information(data/packets).Think of networking like a postal service for digital information - just as letters move between addresses, networks allow data to flow between connected nodes.`But you may ask, how the heck two devices talk to each other? don't they have any common language? BTW! don't forget to ensure privacy? what if someone's been peeking into their conversation?` well, that's why need to have some kind of rules and that's what we call protocols.

#### Protocols
The Internet is all about designing protocols.
`protocol` means set of rules, conventions and guidelines for exchanging data.

Designing a good protocol is harder than it first seems!
    [David D. Clark](https://en.wikipedia.org/wiki/David_D._Clark) was the chief protocol architect for the Internet
    in the 1980s.
```
We reject: kings, presidents, and voting. We believe in: rough consensus and running code.
— David D. Clark (1992)
```
    
- [End-to-End Arguments in System Design (1981)](https://web.mit.edu/saltzer/www/publications/endtoend/endtoend.pdf)

- ["The Design Philosophy of the DARPA Internet Protocols" (1988)](http://ccr.sigcomm.org/archive/1995/jan95/ccr-9501-clark.pdf)


## OSI-Model

The OSI (Open Systems Interconnection) model is a conceptual framework that helps us understand how data travels through a network. The OSI model was developed by the International Organization for Standardization (ISO) in the late 1970s and published in 1984.Think of it as a layered cake where each layer handles a specific task in the communication process.

```        
        Presentation Layer
        • Data Formatting
        • Encryption/decryption
        • Compression/decompressing
        
        Session Layer
        • Connection Control
        • Dialog Management
        
        Transport Layer
        • Error Detection
        • Port Numbers
        • Flow Control
        
        Network Layer
        • Routing
        • Logical Addressing
        • Path Selection
        
        Data Link Layer
        • Frame Creation
        • MAC(Media Access Control Address) Addresses
        • Error Checking
        
        Physical Layer
        • Cable/Wireless
        • Voltage/Signals
        • Network Topology
```
![OSI-MODEL](https://151060567.v2.pressablecdn.com/wp-content/uploads/2024/01/the-7-layers-of-the-OSI-model.png)

#### Why These Models (we'll talk about tpc/ip later) Matter?
By dividing network communication into these layers, the models make it easier to:

- Design and build networks, since each layer handles a specific part of the process.
- Troubleshoot problems, because you can pinpoint which layer is causing an issue.
- Understand how different devices and applications can work together, even if they come from different               manufacturers


We will start undestanding from lower layer first cause it all started form exchanging signals.

1.Physical Layer (Layer 1)- Converts digital data into electrical signals
- Transmits across network cables or wireless medium
- Handles actual transmission medium

2.Data Link Layer (Layer 2)- Creates frames with MAC addresses
- Adds error-checking information
- Manages physical addressing

3.Network Layer (Layer 3)- Adds routing information
- Uses IP addresses to determine the path
- Ensures packets reach the correct destination

4.Transport Layer (Layer 4)- Breaks the email into smaller packets
- Assigns port numbers (like Port 25 for SMTP)
- Ensures reliable delivery

5.Session Layer (Layer 5)- Establishes connection with the mail server
- Manages the dialogue between systems
- Controls how long the session stays open

6.Presentation Layer (Layer 6)- Encrypts sensitive information
- Compresses the email content
- Formats attachments properly

7.Application Layer (Layer 7)- You compose an email in Gmail
- The application layer handles the interface and formatting
- Converts your typed message into digital format

### The Internet Design Principles

Let's explore the Internet Design Principles through clear explanations and visual representations. These principles form the foundation of how the internet works and why it's so successful.

#### Decentralized control
Internet is not governed by a single entity but is a distributed system where each network node operates independently, communicating with its neighbors.

- Each network device (e.g. router) runs on its own. No central mastermind.
- Alternative: SDN (Software-Defined Networking) centralizes control for performance.
- Alternative: DSDN (Distributed SDN) moves back toward decentralization again!

###  Core Principles Overview

The Internet Design Principles can be grouped into two main categories: mandatory principles that must be followed for basic functionality, and recommended principles that enhance robustness and future-proofing.

###  Detailed Breakdown of Mandatory Principles

#### 1.End-to-End Principle (e2ee)
- Definition: Intelligence resides at the endpoints of communication, while the network core handles basic transmission.
- Why It Matters: Prevents network fragility and ensures robustness.
- Example: When you send an email, error checking happens at your device and the recipient's device, not in the middle.

#### 2.Circuit Switching
- Definition: A dedicated path is created through multiple switching routers and connect to end point.

- Why It Matters: Provides consistent bandwidth and minimal latency throughout the connection.  circuit switching remains vital for applications requiring guaranteed bandwidth, low latency, and high  reliability but it's 10x expensive than Packet Switching. 

- Real Example: When you're watching a live sports event online through a dedicated streaming service, circuit switching principles create a temporary dedicated connection between your device and the streaming server, ensuring smooth, uninterrupted video playback without buffering or lag. Also it's mostly used by banks.

#### 3.Packet Switching
- Definition: Breaking data into packets for efficient routing using multiple 
- Why It Matters: Enables scalable network operation and efficient resource usage
- Real Example: When streaming video, your content is broken into small packets that travel independently

#### 4.Connectionless Communication  
- Definition: Each packet finds its own path independently
- Why It Matters: Ensures reliability and fault tolerance
- Example: Even if one packet takes a different route, your message still arrives complete

#### 5.Layered Architecture
- Definition: Separation of concerns across distinct protocol layers (like TCP/IP stack)
- Why It Matters: Enables independent development and updates of different parts
- Example: Your browser can be updated without changing the underlying networking code

#### 6. Best Effort Delivery
  - Definition: Network attempts delivery without guarantees
  - Why It Matters: Balances efficiency with reliability
  - Real Example: Email servers try to deliver mail but won't crash if delivery fails
  - 

### Recommended Principles for Robustness(speed)

1. Open Architecture
- Definition: Designs should allow future modifications
- Benefits: Enables evolution and adaptation
- Example: New protocols can be added without breaking existing ones

2. Robustness Principle
- Definition: Be conservative in sending, liberal in receiving
- Benefits: Ensures interoperability across implementations
- Example: Web browsers accept various formats of HTML even if not perfectly formatted

3. Distribution
- Definition: Resources spread across multiple nodes
- Benefits: Improves efficiency and reliability
- Example: Content delivery networks store copies of content near users

4. Scalability 
- Definition: Systems designed to handle growth
- Benefits: Supports increasing usage and demands
- Example: Cloud services automatically add more resources during high demand

5. Transparency
- Definition: Complexity hidden from users
- Benefits: Improves usability and maintenance
- Example: Users don't need to understand routing protocols to send emails

#### Comparison between Packet Switching and Circuit Switching:

- Helpful for Programmers: Circuit switching<> is favorable due to its guarantee of bandwidth (e.g., 5 Mbps). This predictability assists programmers in ensuring quality for end-users.

- Efficiency: Packet switching is more efficient overall because it minimizes set-up and tear-down time for connections. The need to reserve resources in circuit switching can lead to underutilization.

- Handling Failures: Packet switching deals better with failures, allowing routers to reroute packets seamlessly without requiring end hosts to manage reservations or change paths.

- Implementation Complexity: Packet switching is less complex to implement. Circuit switching necessitates tracking reservations, leading to increased management overhead for routers.

These principles work together to create a robust, scalable, and adaptable global network system. While the mandatory principles ensure basic functionality, the recommended principles help build resilient and future-proof systems. Understanding these principles helps developers design better internet applications and services.

### Bandwidth, Propagation Delay, Ensuring QOS:

Bandwidth and propagation delay are two fundamental concepts in computer networking that together influence the total time it takes for data to travel from sender to receiver.

#### Badwidth
Bandwidth is the maximum rate at which data can be transmitted over a network link, typically measured in bits per second (bps). Whenever we downolad something over the internet for example like downloading games on steam we can see 
it's in bytes not bits. 8 bits = 1byte.

####  transmission delay
The transmission delay (sometimes called bandwidth delay) is the time required to push all the packet’s bits onto the wire. It depends on the packet size and the bandwidth of the link. well, there is a formula to calculate  transmission delay.
```
Transmission delay = Packet size (bits) / Bandwidth (bps)
```
Example: we've a 40Mbps(megabits) connection and we've a file which is 100MB (megaBytes). how much time it will take to transfer the data over the internet?

solution: 
    
    Transmission delay = Packet size (bits) / Bandwidth (bps)
                       = (100 * 8) megabits / 40 Megabits
                       = 800/40
                       = 20 second


#### Propagation Delay
Propagation delay is the time it takes for a signal(elecrical/optical) to travel from the sender to the receiver through the transmission medium (cable, fiber, air, etc.). It depends on the distance between sender and receiver and the propagation speed of the medium (which is typically a fraction of the speed of light). Here's the formula to calculate Propagation delay:
```
 Propagation delay = Distance / Propagation speed
```
Example: 
Suppose you send a signal from Bangladesh to China, a distance of 5,531 km (5,531,000 meters), and the signal travels at the speed of light in air (S=2.998×108S=2.998×108 m/s):
```   
 Propagation delay = 5,531,000 / 2.998*10^8 
                   = 0.01844 second
                   = 18.45 milliseconds 
```


#### Hopping delay
It refers to the delay or latency introduced in a network that employs hopping techniques—where network parameters such as IP addresses, ports, or channels change periodically to enhance security or avoid interference. This delay arises because data packets must be forwarded through multiple intermediate nodes (or hops), and each hop introduces processing, queuing, and transmission delays.

Thus, hopping delay can be understood as the latency component caused by:

- The need to forward packets through multiple hops (routers or nodes), each adding processing and queuing delay.

- The synchronization and switching of network parameters at each hop, which may cause temporary packet loss or
  retransmission delays.

- The overhead of managing time windows to accommodate delayed packets due to network latency.

##### Imp: What is a Queue in Networking:
A queue in networking is a data structure or buffer used to temporarily hold data packets as they wait to be processed, transmitted, or forwarded by a network device such as a router or switch. Queues operate on the First-In, First-Out (FIFO) principle, meaning the first packet to enter the queue is the first to be processed and leave the queue. 

Packet delay = Transmission delay + propagation delay + Queing delay


Static allocation and dynamic allocation in networking most commonly refer to how network resources—especially IP addresses—are assigned to devices.Now we will talk about it both:

#### Static Allocation

- In static allocation, a network administrator manually assigns a fixed IP address or resource to a device.

- The device always uses the same IP address every time it connects to the network.

- This method is ideal for devices that require consistent, uninterrupted access, such as servers, printers, routers, or surveillance cameras.

- Static allocation simplifies network management for critical devices and ensures they are always reachable at the same address, but it can be time-consuming to manage for large numbers of devices and may lead to inefficient use of address space.

#### Dynamic Allocation

- In dynamic allocation, resources (typically IP addresses) are assigned automatically by a server (such as a DHCP server) when a device connects to the network.

- The assigned address can change each time the device reconnects.

- This method is efficient for large or frequently changing networks, such as home networks or offices with many mobile devices.

- Dynamic allocation reduces administrative overhead and optimizes resource usage, but devices may receive different addresses over time, which can complicate access to services that require a fixed address


#### Bursty Traffic
It means it refers to a pattern where data transmission occurs in sudden, unpredictable spikes of high activity, followed by periods of low or minimal activity. Instead of a steady, predictable flow, bursty traffic comes in waves—one moment the network is quiet, and the next, it is flooded with data and it's just atrocious for network admins. Well let me give you some real world scenarios:

- Flash sales or viral social media posts that send thousands of visitors to a website at once: black friday sales...
- Large file transfers, software updates or downloads that hit many users simultaneously: windows update in the back..
- DDoS attacks or automated bots causing traffic surges: hackers trying to overload servers flooding requests...

#### Resource Reservation
Resource reservation in networking is the process of reserving specific network resources—such as bandwidth or buffer space—along the path between a sender and receiver to guarantee a certain level of service quality (QoS) for data flows. This ensures that applications requiring steady performance, like video conferencing, VoIP, or real-time gaming, receive the necessary network resources to function smoothly, even during periods of congestion. Now you may 
ask why and how does it work? Let me explain How Resource Reservation Works:

- The process typically uses a protocol such as RSVP (Resource Reservation Protocol) most of the time.

- The sender initiates communication with a 'Path' message, which travels through the network to the receiver,         mapping out the route as we talked about in the circuit switching.

- The receiver determines the required resources (e.g., bandwidth) and sends a 'Reservation' request back along the   same path.

- Each router along the path checks if it can allocate the requested resources. If so, it reserves them and forwards   the reservation request to the next router.

- once all routers have confirmed the reservation, the receiver is notified, and the application can begin transmitting data with the guaranteed QoS.

- servations are temporary and periodically refreshed, allowing the network to adapt to changing conditions.

now let's talk about some Key Features and Benefits: 

- Quality of Service (QoS): Ensures consistent network performance for critical applications.

- Receiver-Oriented: Protocols like RSVP are typically initiated by the receiver, allowing for flexible and efficient resource management.

- Supports Unicast and Multicast: Resource reservation can be used for both one-to-one and one-to-many communications.

- Temporary and Adaptive: Reservations are not permanent; they are updated or released as application needs change.


#### Network Efficiency
Network efficiency refers to how effectively a network achieves its goals of fast, reliable communication and smooth data transfer with minimal resource waste or downtime. There are 6 common terms we've to ensure to build an efficient networking infustructure:

```
1. Throughput: The actual rate at which data is successfully transferred across the network. High throughput means    the network can move large amounts of data efficiently. Example: A video streaming service like Netflix measures throughput by how many megabits per second (Mbps) of video data are successfully delivered to viewers. If a user can stream a 4K video without buffering, the network is achieving high throughput, efficiently moving large data volumes to the end user.

2. Bandwidth Utilization: Measures how much of the available bandwidth is being used. Efficient networks maximize usage without causing congestion or overloading links. Example: A corporate network has a 1 Gbps internet link. During peak business hours, network monitoring tools show that average usage is around 800 Mbps, meaning 80% of the available bandwidth is being used. This indicates efficient bandwidth utilization, as the link is neither underused nor overloaded, avoiding congestion and maximizing value from the investment.

3. Latency: The time it takes for data to travel from source to destination. Lower latency is a sign of higher efficiency, especially for real-time applications. Example: Online gamers experience latency as "ping." If a game server is located close to the player, the round-trip time for data packets might be just 20 milliseconds (10s for data-out 10s for data-in), resulting in smooth gameplay. Higher latency (e.g., 200 ms) would cause noticeable lag, reducing efficiency for real-time applications like gaming or video calls.

4. Packet Loss and Errors: Efficient networks minimize data loss and transmission errors, ensuring reliable delivery. Example : It can occcur due to hopping multiple nodes or routers causing data loss over the tranmission 
medium.Technologies like forward error correction (FEC) help maintain high throughput and reliability even if some packets are lost.

5. Upime and Reliability: High network efficiency is associated with minimal downtime and consistent availability of network services. Example: As an Isp provier we've to ensure 99.99% guaranteed uptime.This means the network can't be unavailable for less than 5 minutes per year.Well that's a tough job to ensure. High network efficiency is demonstrated by minimal downtime and consistent service availability, which is critical for businesses relying on continuous connectivity.

6. Resource Consumption: Efficient use of CPU, memory, and other network resources to prevent bottlenecks and ensure smooth operation. Example: A data center optimizes its server workload so that CPU and memory usage are balanced across all machines what we call the load balancer. By preventing any single server from becoming a bottleneck, the network can handle more simultaneous connections and data transfers smoothly, improving overall efficiency. So as a 
great engineer we have to design Horizontal and Vertical Scaling to distribute loads evenly.

```
#### Network congestion
Network congestion occurs when the volume of data traffic exceeds the network’s capacity to handle it efficiently. This typically happens when too many data packets are sent through a network node or link at the same time, overwhelming available bandwidth and resources. As a result, the network experiences degraded performance, including increased latency (delays), packet loss, jitter (variability in packet arrival times), and reduced throughput (overall data transfer rate). In one sentence - you don't have enough bandwidth .Let's imagine a scenario and try to understand it in a better way.

Scenario: Imagine a network with 300/400 users.On a regular day, the network operates smoothly, handling emails, web browsing, and occasional video calls.However, let's imagine argentina and brazil is competeing against each other.
What will happen?

- The total data demand far exceeds the available network bandwidth.

- Routers and switches become overwhelmed, causing their buffers to fill up.

- As buffers overflow, packets are dropped, resulting in packet loss.

- Applications (especially real-time ones like video calls) experience jitter and lag.

- users notice significant delays in sending/receiving emails, slow file transfers, and frozen video calls.

- Some connections may time out entirely, forcing users to reconnect.


#### Transient overload

Transient overload in networking refers to a temporary condition where the demand on network resources (such as bandwidth, processing power, or memory) exceeds the available capacity for a short period. Unlike sustained overload, which is continuous or long-lasting, transient overload is brief and often caused by sudden spikes or bursts in network traffic. These overloads typically resolve themselves quickly as the burst subsides or as the system adapt. Example: Imagine a popular e-commerce website like alibaba during a flash sale. For most of the day, the server handles a steady stream of customer requests comfortably. However, when the sale begins at noon, thousands of users attempt to access the site and place orders at the exact same moment. Disaster may happen:

- The number of incoming requests per second suddenly spikes, far exceeding the server’s processing and bandwidth capacity.

- The server’s request queues fill up rapidly, and some requests may be dropped or delayed.

- Users may experience slow page loads, timeouts, or temporary inability to complete transactions.

This overload lasts only a few minutes, until the initial rush subsides and the traffic returns to normal levels.
BTW there are 2 Types of Transient Overload:

- Alternating Overload: The load alternates between high and low, with overload periods equal to low-load periods.
- Intermittent Overload: The load is usually low, but there are occasional, evenly spaced spikes of overload


we've come a long way, yay!!! now we will talk about Routing principles and how packets are being send through.


#### Routing principles
Before explaining routing and routers I'd like to explain how data packets are send over the wires or a medium.

```
Sender(mac Addr1)(packets) ===NAT===>>> router1(ip1) ===NAT===>>> router2(ip2) ===>>> revicer2(mac addr2)(packet recived)

```
simple explanation :

- Sender (mac Addr1): This is the main node, identified by its MAC address (mac Addr1). It sends a data packet toward the destination.

- NAT (at router1 with ip1): The packet first reaches router1, which uses Network Address Translation (NAT). NAT changes the packet's source IP address from the sender's private IP to router1's public IP (ip1). This hides the sender's private IP from the outside network.

- NAT (at router2 with ip2): The packet then reaches router2, which also uses NAT. Router2 changes the source IP address again, this time from router1's public IP (ip1) to router2's public IP (ip2). Now, to the outside world, the packet looks like it came from router2.

- Receiver2 (mac addr2): Finally, the packet arrives at the destination node, identified by its MAC address (mac addr2). When the response is sent back, each NAT router reverses the address translation so the reply can find its way back to the original sender.

In summary:
At each NAT router, the source IP address in the packet is replaced with the router's own public IP. This process hides the internal network structure and allows multiple devices to share a single public IP address. The routers keep track of these translations so return traffic can be routed correctly back to the original sender.But the question is 
do we really get the idea what router did? It just routed our package to the sender to make a transaction.Let me elaborate a detailed Routing Process Example:

- Initiation: A source node wants to send data to a destination node.
- Packet Creation: The data is divided into packets, each labeled with the destination IP address.
- Routing Table Lookup: The router checks its routing table to find the best next hop for the packet based on the shortest or least-cost path.
- Packet Forwarding: The packet is forwarded from router to router (hops) until it reaches the destination.
- Reassembly: At the destination, packets are reassembled into the original data

#### Routing principles
Routing in networking is the process of selecting paths in a network along which data packets travel from a source to a destination. The core principles of routing involve determining the optimal path, forwarding packets, and maintaining routing information dynamically or statically to ensure efficient data delivery. Well, there are 6 
mandatory routing principles:

1. Path Determination:
Routing algorithms calculate the best possible path for data packets to travel across the network. This involves evaluating multiple possible routes and selecting the optimal one based on specific metrics such as hop count, bandwidth, delay, or cost.

2. Routing Tables:
Routers maintain routing tables, which are data structures containing information about network destinations and the next hop to reach them. These tables are updated either manually (static routing) or automatically (dynamic routing) to reflect the current network topology and conditions.

3. Routing Metrics:
Routing decisions rely on metrics to assess the desirability of a route. Common metrics include:
- Hop count (number of intermediate routers).
- Bandwidth (capacity of the link).
- Delay (time taken for data to traverse the path).
- Cost (an abstract value representing route preference).

4. Types of Routing:
Static Routing: Routes are manually configured by network administrators. It offers fine control but lacks scalability and adaptability to network changes.

Dynamic Routing: Routers automatically discover and maintain routes using routing protocols that adapt to network topology changes and traffic conditions. This improves flexibility and fault tolerance.

5. Routing Protocols:
Routing protocols define rules for routers to communicate routing information and update routing tables. They can be categorized as:
Interior Gateway Protocols (IGPs): Operate within a single autonomous system (AS), e.g., RIP, OSPF, EIGRP.

Exterior Gateway Protocols (EGPs): Manage routing between different autonomous systems, e.g., BGP.

6. Packet Forwarding and Hopping:
When a data packet is sent, routers forward it hop-by-hop through intermediate nodes until it reaches the destination. The packet header contains the destination address, and each router uses its routing table to determine the next hop

continue....

[Back to top](#top) [:arrow_up:](#top)
