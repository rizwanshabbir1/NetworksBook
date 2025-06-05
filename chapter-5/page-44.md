20 INTRODUCTION CHAP. 1
Ethernet
switch Ports To rest of
networkTo wired network Access
point
Figure 1-8. Wireless and wired LANs. (a) 802.11. (b) Switched Ethernet.
to hundreds of Mbps. (In this book we will adhere to tradition and measure line
speeds in megabits/sec, where 1 Mbps is 1,000,000 bits/sec, and gigabits/sec,where 1 Gbps is 1,000,000,000 bits/sec.) We will discuss 802.11 in Chap. 4.
Wired LANs use a range of different transmission technologies. Most of
them use copper wires, but some use optical fiber. LANs are restricted in size,
which means that the worst-case transmission time is bounded and known in ad-vance. Knowing these bounds helps with the task of designing network protocols.Typically, wired LANs run at speeds of 100 Mbps to 1 Gbps, have low delay(microseconds or nanoseconds), and make very few errors. Newer LANs can op-
erate at up to 10 Gbps. Compared to wireless networks, wired LANs exceed them
in all dimensions of performance. It is just easier to send signals over a wire orthrough a fiber than through the air.
The topology of many wired LANs is built from point-to-point links. IEEE
802.3, popularly called Ethernet , is, by far, the most common type of wired
LAN. Fig. 1-8(b) shows a sample topology of switched Ethernet . Each com-
puter speaks the Ethernet protocol and connects to a box called a switch with a
point-to-point link. Hence the name. A switch has multiple ports , each of which
can connect to one computer. The job of the switch is to relay packets between
computers that are attached to it, using the address in each packet to determine
which computer to send it to.
To build larger LANs, switches can be plugged into each other using their
ports. What happens if you plug them together in a loop? Will the network stillwork? Luckily, the designers thought of this case. It is the job of the protocol tosort out what paths packets should travel to safely reach the intended computer.
We will see how this works in Chap. 4.
It is also possible to divide one large physical LAN into two smaller logical
LANs. You might wonder why this would be useful. Sometimes, the layout of thenetwork equipment does not match the organization’s structure. For example, the