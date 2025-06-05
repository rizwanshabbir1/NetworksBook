SEC. 1.2 NETWORK HARDWARE 21
engineering and finance departments of a company might have computers on the
same physical LAN because they are in the same wing of the building but it might
be easier to manage the system if engineering and finance logically each had its
own network Virtual LAN orVLAN . In this design each port is tagged with a
‘‘color,’’ say green for engineering and red for finance. The switch then forwardspackets so that computers attached to the green ports are separated from the com-puters attached to the red ports. Broadcast packets sent on a red port, for example,will not be received on a green port, just as though there were two different
LANs. We will cover VLANs at the end of Chap. 4.
There are other wired LAN topologies too. In fact, switched Ethernet is a
modern version of the original Ethernet design that broadcast all the packets overa single linear cable. At most one machine could successfully transmit at a time,
and a distributed arbitration mechanism was used to resolve conflicts. It used asimple algorithm: computers could transmit whenever the cable was idle. If twoor more packets collided, each computer just waited a random time and tried later.
We will call that version classic Ethernet for clarity, and as you suspected, you
will learn about it in Chap. 4.
Both wireless and wired broadcast networks can be divided into static and
dynamic designs, depending on how the channel is allocated. A typical static al-
location would be to divide time into discrete intervals and use a round-robin al-gorithm, allowing each machine to broadcast only when its time slot comes up.
Static allocation wastes channel capacity when a machine has nothing to say dur-ing its allocated slot, so most systems attempt to allocate the channel dynamically
(i.e., on demand).
Dynamic allocation methods for a common channel are either centralized or
decentralized. In the centralized channel allocation method, there is a single enti-
ty, for example, the base station in cellular networks, which determines who goesnext. It might do this by accepting multiple packets and prioritizing them accord-
ing to some internal algorithm. In the decentralized channel allocation method,
there is no central entity; each machine must decide for itself whether to transmit.
You might think that this approach would lead to chaos, but it does not. Later wewill study many algorithms designed to bring order out of the potential chaos.
It is worth spending a l ittle more time discussing LANs in the home. In the
future, it is likely that every appliance in the home will be capable of communi-cating with every other appliance, and all of them will be accessible over the In-
ternet. This development is likely to be one of those visionary concepts thatnobody asked for (like TV remote controls or mobile phones), but once theyarrived nobody can imagine how they lived without them.
Many devices are already capable of being networked. These include com-
puters, entertainment devices such as TVs and DVDs, phones and other consumerelectronics such as cameras, appliances like clock radios, and infrastructure likeutility meters and thermostats. This trend will only continue. For instance, theaverage home probably has a dozen clocks (e.g., in appliances), all of which could