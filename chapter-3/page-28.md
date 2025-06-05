4 INTRODUCTION CHAP. 1
database in Singapore. Networks called VPNs (Virtual Private Networks ) may
be used to join the individual networks at different sites into one extended net-work. In other words, the mere fact that a user happens to be 15,000 km awayfrom his data should not prevent him from using the data as though they werelocal. This goal may be summarized by saying that it is an attempt to end the‘‘tyranny of geography.’’
In the simplest of terms, one can imagine a company’s information system as
consisting of one or more databases with company information and some numberof employees who need to access them remotely. In this model, the data are stor-
ed on powerful computers called servers . Often these are centrally housed and
maintained by a system administrator. In contrast, the employees have simplermachines, called clients , on their desks, with which they access remote data, for
example, to include in spreadsheets they are constructing. (Sometimes we willrefer to the human user of the client machine as the ‘‘client,’’ but it should beclear from the context whether we mean the computer or its user.) The client andserver machines are connected by a network, as illustrated in Fig. 1-1. Note that
we have shown the network as a simple oval, without any detail. We will use thisform when we mean a network in the most abstract sense. When more detail isrequired, it will be provided.
Client
Server
Network
Figure 1-1. A network with two clients and one server.
This whole arrangement is called the client-server model . It is widely used
and forms the basis of much network usage. The most popular realization is thatof a Web application , in which the server generates Web pages based on its data-
base in response to client requests that may update the database. The client-server
model is applicable when the client and server are both in the same building (andbelong to the same company), but also when they are far apart. For example,when a person at home accesses a p age on the World Wide Web, the same model
is employed, with the remote Web server being the server and the user’s personal