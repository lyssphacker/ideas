### Internet of objects

---
#### [Send objects not data](send-objects-not-data/send-objects-not-data.md)

---

#### Alan Kay about Internet of Objects
[How to Invent the Future](http://www.youtube.com/watch?v=1e8VZlPBx_0&t=23m55s)  
[Everything is kind of like the Internet](http://www.youtube.com/watch?v=tp9VbtLn2Jw&t=27m20s)  
[Meaning dominates connections](https://www.youtube.com/watch?v=tp9VbtLn2Jw&t=46m21s)  

---

#### CORBA vs RMI vs Microservices
[Reinventing the Wheel? CORBA vs. Web Services](http://wwwconference.org/proceedings/www2002/alternate/395/index.html)  
[Web Services/SOAP and CORBA](http://www.omg.org/news/whitepapers/CORBA_vs_SOAP1.pdf)  
[Comparison of Web Services, Java-RMI, and CORBA service implementations ](http://www.metz.supelec.fr/metz/personnel/galtier/PagesPerso/Enseignement/3A/SOA/Articles/compare_WS_RMI_CORBA.pdf)  
[The Rise and Fall of CORBA](https://news.ycombinator.com/item?id=10144734)

---

#### CORBA vs SOA
[What object oriented distributed programming does not have to be, and what it may be](https://infoscience.epfl.ch/record/83554/files/neg--933288481Inf-Rachid.pdf)

---

#### Distributed object-oriented programming
[What object oriented distributed programming does not have to be, and what it may be](https://infoscience.epfl.ch/record/83554/files/neg--933288481Inf-Rachid.pdf)  
[Distributed object](https://en.wikipedia.org/wiki/Distributed_object)  
[A Comparison of Distributed Object Technologies](https://pdfs.semanticscholar.org/a0b5/dc49fbc3f46a45d58ef4c348482452dd1ee2.pdf)  
[Distributed Object Systems: An Evolutionary Perspective](http://www.diss.fu-berlin.de/diss/servlets/MCRFileNodeServlet/FUDISS_derivate_000000000988/2_chapter2.pdf?hosts=)

---

#### Is RPC bad?
Is it worth revisiting CORBA?  
http://archive.oreilly.com/cs/user/view/cs_msg/15469  

Was CORBA done with message passing or messaging in mind?  

[rpc is bad?](http://erlang.org/pipermail/erlang-questions/2008-May/035209.html)

---

#### Peer-to-peer vs client-server
Is SOA peer-to-peer architecture?

---

#### SOA vs microservices
What is SOA all about?
How is microservices architecture related to SOA?

---

#### From ARPA/PARC community
1. [The LOCUS Distributed System Architecture](https://www.amazon.com/Distributed-System-Architecture-Computer-Systems/dp/0262161028/ref=sr_1_4?ie=UTF8&qid=1514807872&sr=8-4&keywords=locus+system)  
2. [NAMING AND SYNCHRONIZATION IN A DECENTRALIZED COMPUTER SYSTEM](http://publications.csail.mit.edu/lcs/specpub.php?id=773)  
3. Alan Kay: "Part of the idea behind “real objects” was to act as “virtual machines” connected by “neutral messages” in the very same way as we were starting to design the Internet — and that the “virtual internet of objects” would map into the subsequent hardware network."  
4. [The Early History of Smalltalk](http://worrydream.com/EarlyHistoryOfSmalltalk/): "In computer terms, Smalltalk is a recursion on the notion of computer itself. Instead of dividing "computer stuff" into things each less strong than the whole—like data structures, procedures, and functions which are the usual paraphernalia of programming languages—each Smalltalk object is a recursion on the entire possibilities of the computer. Thus its semantics are a bit like having thousands and thousands of computers all hooked together by a very fast network."  
5. [Croquet – A Collaboration System Architecture](http://worrydream.com/refs/Smith%20-%20Croquet%20-%20A%20Collaboration%20System%20Architecture.pdf)  

---

#### Why microservices?
What is the major motivation for microservices?  
How are microservices related to earlier technologies, starting with CORBA, JavaBeans, etc.?  
[have we come full circle with microservices, back to very old school approaches?](https://softwareengineering.stackexchange.com/questions/275927/have-we-come-full-circle-with-microservices-back-to-very-old-school-approaches)  
[Microservices? Please, Don't](https://news.ycombinator.com/item?id=13167188)  

---

#### Actors
[Akka Actors](https://doc.akka.io/docs/akka/current/actors.html)  
[What is the difference between Alan Kay's definition of OOP and Carl Hewitt's Actor Model?](https://www.quora.com/What-is-the-difference-between-Alan-Kays-definition-of-OOP-and-Carl-Hewitts-Actor-Model)  
[Alan Kay](https://www.quora.com/What-are-the-main-successes-of-the-AI-group-at-Xerox-PARC-during-the-70s-and-first-half-of-the-80s-How-much-influence-did-it-have-on-other-groups-like-Smalltalk-group-and-vice-versa/answer/Alan-Kay-11): "This was my initial plan for Smalltalk. Fate intervened with something else. But these ideas reflected back to Carl Hewitt in his later “Actor” ideas, which are more like the early Smalltalk ideas, and which went beyond in a number of ways."  
[Alan Kay](https://computinged.wordpress.com/2010/09/11/moti-asks-objects-never-well-hardly-ever/):  
We didn’t even do all of the idea at PARC. Many of Carl Hewitt’s Actors ideas which got sparked by the original Smalltalk were more in the spirit of OOP than the subsequent Smalltalks. Significant parts of Erlang are more like a real OOP language the the current Smalltalk, and certainly the C based languages that have been painted with “OOP paint”.

---

#### Internet of Things
Is internet of objects related to internet of things?

---

#### Quora questions
[Did distributed object-oriented technologies like CORBA, DCOM and RMI deservedly fail? Did better alternatives exist but were not popular enough to survive?](https://www.quora.com/Did-distributed-object-oriented-technologies-like-CORBA-DCOM-and-RMI-deservedly-fail-Did-better-alternatives-exist-but-were-not-popular-enough-to-survive)  
[Should one understand CORBA, RPC, web services, SOA and other predecessors of microservices architecture, in order to understand microservices architecture itself?](https://www.quora.com/Should-one-understand-CORBA-RPC-web-services-SOA-and-other-predecessors-of-microservices-architecture-in-order-to-understand-microservices-architecture-itself)  
[Are there any systems which were built using SOA or microservices architectural principles whose source is available so that one can learn from it?](https://www.quora.com/Are-there-any-systems-which-were-built-using-SOA-or-microservices-architectural-principles-whose-source-is-available-so-that-one-can-learn-from-it)
[Since message passing is crucial in OOP and distributed systems architectures like SOA and REST have lot do with services talking to each other sending messages, could all of them be called distributed object-oriented programming?](https://www.quora.com/Since-message-passing-is-crucial-in-OOP-and-distributed-systems-architectures-like-SOA-and-REST-have-lot-do-with-services-talking-to-each-other-sending-messages-could-all-of-them-be-called-distributed-object)  
[For somebody experienced in SOA, is there anything interesting or new in microservices architecture? Is hype surrounding microservices legitimate?](https://www.quora.com/unanswered/For-somebody-experienced-in-SOA-is-there-anything-interesting-or-new-in-microservices-architecture-Is-hype-surrounding-microservices-legitimate)  
[Should one understand CORBA, RPC, web services, SOA and other predecessors of microservices architecture, in order to understand microservices architecture itself?](https://www.quora.com/Should-one-understand-CORBA-RPC-web-services-SOA-and-other-predecessors-of-microservices-architecture-in-order-to-understand-microservices-architecture-itself)  
[Have integration technologies and architectures regressed over the years, going from CORBA, RPC, SOAP/WSDL and finishing with REST?](https://www.quora.com/unanswered/Have-integration-technologies-and-architectures-regressed-over-the-years-going-from-CORBA-RPC-SOAP-WSDL-and-finishing-with-REST)
[Can metaobject protocols help in making systems written in different object systems interoperate better on the Internet?](https://www.quora.com/unanswered/Can-metaobject-protocols-help-in-making-systems-written-in-different-object-systems-interoperate-better-on-the-Internet)

---

#### [Real object-oriented programming](https://github.com/lyssphacker/ideas/blob/master/internet-of-objects/real-oop.md)

---

#### Propagator model
[Revised Report on the Propagator Model](https://groups.csail.mit.edu/mac/users/gjs/propagators/)  
[Propagators in Clojure](https://www.youtube.com/watch?v=JXOOO9MLvhs)

##### Talks
[Constraints and Hallucinations: Filling in the Details](https://github.com/lyssphacker/talks/blob/master/constraints-and-halucinations-filling-in-the-details/constraints-and-halucinations-filling-in-the-details.md)  
[Flexible Systems: The Power of Generic Operations](https://github.com/lyssphacker/talks/blob/master/flexible-systems-power-of-generic-operations/flexible-systems-power-of-generic-operations.md#flexible-systems-the-power-of-generic-operations)  
[We Really Don't Know How to Compute!](https://github.com/lyssphacker/talks/blob/master/we-really-do-not-know-how-to-compute/we-really-do-not-know-how-to-compute.md)

---
#### Design patterns
[SOA Patterns](https://www.manning.com/books/soa-patterns)  
Service Design Patterns  
Enterprise Integration Patterns  
Pattern-Oriented Software Architecture, Patterns for Concurrent and Networked Objects, Volume 2  
Design Patterns: Elements of Reusable Object-Oriented Software  
Pattern-Oriented Software Architecture Volume 4: A Pattern Language for Distributed Computing  

---
#### Metaobject protocols
[Why Black Boxes are so Hard to Reuse: A New Approach to Abstraction for the Engineering of Software](https://github.com/lyssphacker/talks/blob/master/why-black-boxes-are-so-hard-to-reuse/why-black-boxes-are-so-hard-to-reuse.md)  
The Art of Metaobject Protocol  
[Alan Kay at OOPSLA](https://www.youtube.com/watch?v=oKg1hTOQXoY&amp;t=53m10s)  

---
#### Functional programming and distributed systems
[Are functional programming techniques influencing or have they been influencing techniques used to build distributed systems?](https://www.quora.com/Are-functional-programming-techniques-influencing-or-have-they-been-influencing-techniques-used-to-build-distributed-systems)  
[Is Erlang really a functional language?](https://stackoverflow.com/questions/2271417/is-erlang-really-a-functional-language)  
[Can one build distributed system using only functional programming techniques? If not, does this makes functional programming much less useful then object-oriented programming whose idea of message passing scales better?](https://www.quora.com/Can-one-build-distributed-system-using-only-functional-programming-techniques-If-not-does-this-makes-functional-programming-much-less-useful-then-object-oriented-programming-whose-idea-of-message-passing-scales?__filter__&__nsrc__=2&__snid3__=2106094277)

---
#### Erlang

---
#### Cloud computing
[Cloud Computing and the Internet](https://research.googleblog.com/2009/04/cloud-computing-and-internet.html)

---
#### Reactive Systems
[From Microliths To Microsystems](https://www.youtube.com/watch?v=xMWg5KNACsA)  
[Reactive Microsystems - The Evolution of Microservices at Scale](https://www.youtube.com/watch?v=3hMtjPcU248)
