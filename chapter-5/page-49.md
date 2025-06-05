SEC. 1.2 NETWORK HARDWARE 25
Subnet
Router
PerthBrisbane
MelbourneTransmission
line
Figure 1-10. WAN that connects three branch offices in Australia.
example, the employees might be responsible for their own computers, while the
company’s IT department is in charge of the rest of the network. We will seeclearer boundaries in the coming examples, in which the network provider or tele-
phone company operates the subnet. Separation of the pure communicationaspects of the network (the subnet) from the application aspects (the hosts) greatlysimplifies the overall network design.
A second difference is that the routers will usually connect different kinds of
networking technology. The networks inside the offices may be switched Ether-
net, for example, while the long-distance transmission lines may be SONET links
(which we will cover in Chap. 2). Some device needs to join them. The astutereader will notice that this goes beyond our definition of a network. This meansthat many WANs will in fact be internetworks , or composite networks that are
made up of more than one network. We will have more to say about internet-works in the next section.
A final difference is in what is connected to the subnet. This could be indivi-
dual computers, as was the case for connecting to LANs, or it could be entire
LANs. This is how larger networks are built from smaller ones. As far as the sub-net is concerned, it does the same job.
We are now in a position to look at two other varieties of WANs. First, rather
than lease dedicated transmission lines, a company might connect its offices to the
Internet This allows connections to be made between the offices as virtual links