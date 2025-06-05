26 INTRODUCTION CHAP. 1
that use the underlying capacity of the Internet. This arrangement, shown in
Fig. 1-11, is called a VPN (Virtual Private Network ). Compared to the dedi-
cated arrangement, a VPN has the usual advantage of virtualization, which is thatit provides flexible reuse of a resource (Internet connectivity). Consider how easy
it is to add a fourth office to see this. A VPN also has the usual disadvantage ofvirtualization, which is a lack of control over the underlying resources. With adedicated line, the capacity is clear. With a VPN your mileage may vary withyour Internet service.
Internet
PerthBrisbane
MelbourneLink via the
internet
Figure 1-11. WAN using a virtual private network.
The second variation is that the subnet may be run by a different company.
The subnet operator is known as a network service provider and the offices are
its customers. This structure is shown in Fig. 1-12. The subnet operator will con-nect to other customers too, as long as they can pay and it can provide service.Since it would be a disappointing network service if the customers could only
send packets to each other, the subnet operator will also connect to other networks
that are part of the Internet. Such a subnet operator is called an ISP (Internet
Service Provider ) and the subnet is an ISP network . Its customers who connect
to the ISP r eceive Internet service.
We can use the ISP network to preview some key issues that we will study in
later chapters. In most WANs, the network contains many transmission lines,each connecting a pair of routers. If two routers that do not share a transmission
line wish to communicate, they must do this indirectly, via other routers. There