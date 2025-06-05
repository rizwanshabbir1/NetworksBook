24 INTRODUCTION CHAP. 1
InternetAntennaJunction
box
Head end
Figure 1-9. A metropolitan area network based on cable TV.
communication subnet , or just subnet for short. The job of the subnet is to carry
messages from host to host, just as the telephone system carries words (really just
sounds) from speaker to listener.
In most WANs, the subnet consists of two distinct components: transmission
lines and switching elements. Transmission lines move bits between machines.
They can be made of copper wire, optical fiber, or even radio links. Most com-
panies do not have transmission lines lying about, so instead they lease the linesfrom a telecommunications company. Switching elements , or just switches , are
specialized computers that connect two or more transmission lines. When data
arrive on an incoming line, the switching element must choose an outgoing line on
which to forward them. These switching computers have been called by variousnames in the past; the name router is now most commonly used. Unfortunately,
some people pronounce it ‘‘rooter’’ while others have it rhyme with ‘‘doubter.’’Determining the correct pronunciation will be left as an exercise for the reader.
(Note: the perceived correct answer may depend on where you live.)
A short comment about the term ‘‘subnet’’ is in order here. Originally, its
only meaning was the collection of routers and communication lines that moved
packets from the source host to the destination host. Readers should be aware thatit has acquired a second, more recent meaning in conjunction with network ad-
dressing. We will discuss that meaning in Chap. 5 and stick with the originalmeaning (a collection of lines and routers) until then.
The WAN as we have described it looks similar to a large wired LAN, but
there are some important differences that go beyond long wires. Usually in aWAN, the hosts and subnet are owned and operated by different people. In our