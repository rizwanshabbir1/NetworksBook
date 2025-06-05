SEC. 1.2 NETWORK HARDWARE 17
1.2 NETWORK HARDWARE
It is now time to turn our attention from the applications and social aspects of
networking (the dessert) to the technical issues involved in network design (thespinach). There is no generally accepted taxonomy into which all computer net-
works fit, but two dimensions stand out as important: transmission technology and
scale. We will now examine each of these in turn.
Broadly speaking, there are two types of transmission technology that are in
widespread use: broadcast links and point-to-point links.
Point-to-point links connect individual pairs of machines. To go from the
source to the destination on a network made up of point-to-point links, short mes-sages, called packets in certain contexts, may have to first visit one or more inter-
mediate machines. Often multiple routes, of different lengths, are possible, so
finding good ones is important in point-to-point networks. Point-to-pointtransmission with exactly one sender and exactly one receiver is sometimes called
unicasting .
In contrast, on a broadcast network, the communication channel is shared by
all the machines on the network; packets sent by any machine are received by all
the others. An address field within each packet specifies the intended recipient.
Upon receiving a packet, a machine checks the address field. If the packet is in-
tended for the receiving machine, that machine processes the packet; if the packet
is intended for some other machine, it is just ignored.
A wireless network is a common example of a broadcast link, with communi-
cation shared over a coverage region that depends on the wireless channel and thetransmitting machine. As an analogy, consider someone standing in a meeting
room and shouting ‘‘Watson, come here. I want you.’’ Although the packet mayactually be received (heard) by many people, only Watson will respond; the others
just ignore it.
Broadcast systems usually also allow the possibility of addressing a packet to
alldestinations by using a special code in the address field. When a packet with
this code is transmitted, it is received and processed by every machine on the net-
work. This mode of operation is called broadcasting . Some broadcast systems
also support transmission to a subset of the machines, which known as multicast-
ing.
An alternative criterion for classifying networks is by scale. Distance is im-
portant as a classification metric because different technologies are used at dif-
ferent scales.
In Fig. 1-6 we classify multiple processor systems by their rough physical
size. At the top are the personal area networks, networks that are meant for oneperson. Beyond these come longer-range networks. These can be divided into
local, metropolitan, and wide area networks, each with increasing scale. Finally,
the connection of two or more networks is called an internetwork. The worldwide
Internet is certainly the best-known (but not the only) example of an internetwork.