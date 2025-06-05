2 INTRODUCTION CHAP. 1
one or two computers, while very large institutions had at most a few dozen. The
idea that within forty years vastly more powerful computers smaller than postagestamps would be mass produced by the billions was pure science fiction.
The merging of computers and communications has had a profound influence
on the way computer systems are organized. The once-dominant concept of the‘‘computer center’’ as a room with a large computer to which users bring theirwork for processing is now totally obsolete (although data centers holding thou-sands of Internet servers are becoming common). The old model of a single com-puter serving all of the organization’s computational needs has been replaced by
one in which a large number of separate but interconnected computers do the job.
These systems are called computer networks . The design and organization of
these networks are the subjects of this book.
Throughout the book we will use the term ‘‘computer network’’ to mean a col-
lection of autonomous computers interconnected by a single technology. Two
computers are said to be interconnected if they are able to exchange information.
The connection need not be via a copper wire; fiber optics, microwaves, infrared,
and communication satellites can also be used. Networks come in many sizes,
shapes and forms, as we will see later. They are usually connected together to
make larger networks, with the Internet being the most well-known example of a
network of networks.
There is considerable confusion in the literature between a computer network
and a distributed system . The key distinction is that in a distributed system, a
collection of independent computers appears to its users as a single coherent sys-tem. Usually, it has a single model or paradigm that it presents to the users. Of-ten a layer of software on top of the operating system, called middleware ,i s
responsible for implementing this model. A well-known example of a distributed
system is the World Wide Web . It runs on top of the Internet and presents a
model in which everything looks like a document (Web page).
In a computer network, this coherence, model, and software are absent. Users
are exposed to the actual machines, without any attempt by the system to makethe machines look and act in a coherent way. If the machines have different hard-ware and different operating systems, that is fully visible to the users. If a userwants to run a program on a remote machine, he
†has to log onto that machine and
run it there.
In effect, a distributed system is a software system built on top of a network.
The software gives it a high degree of cohesiveness and transparency. Thus, thedistinction between a network and a distributed system lies with the software (es-pecially the operating system), rather than with the hardware.
Nevertheless, there is considerable overlap between the two subjects. For ex-
ample, both distributed systems and computer networks need to move filesaround. The difference lies in who invokes the movement, the system or the user.
† ‘‘He’’ should be read as ‘‘he or she’’ throughout this book.