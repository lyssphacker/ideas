### Real object-oriented programming

What are differences between "real OOP" (as Alan Kay calls it) and conventional OOP?

#### General

1. [Seminar on Object Oriented Programming](https://www.youtube.com/watch?v=QjJaFG63Hlo)
2. [Design Principles Behind Smalltalk](https://www.cs.virginia.edu/~evans/cs655/readings/smalltalk.html)
3. [What is Alan Kay's definition of Object Oriented?](https://www.quora.com/What-is-Alan-Kays-definition-of-Object-Oriented)
4. [From Squeak mailing list](http://lists.squeakfoundation.org/pipermail/squeak-dev/1998-October/017019.html)
5. Definition from Alan Kay: "OOP to me means only messaging, local retention and protection and hiding of state-process, and extreme late-binding of all things. It can be done in Smalltalk and in LISP. There are possibly other systems in which this is possible, but I'm not aware of them."
6. [Is a microservices architecture with RESTful APIs an implementation of Alan Kay's concept of object-oriented programming?](https://www.quora.com/Is-a-microservices-architecture-with-RESTful-APIs-an-implementation-of-Alan-Kays-concept-of-object-oriented-programming)
7. [Do you consider the micro services movement as a realization of the real object oriented language as envisioned by Alan Kay, where the services would be the objects and the API calls would be the messages?](https://www.quora.com/Do-you-consider-the-micro-services-movement-as-a-realization-of-the-real-object-oriented-language-as-envisioned-by-Alan-Kay-where-the-services-would-be-the-objects-and-the-API-calls-would-be-the-messages)
8. [What did Alan Kay mean by, "I made up the term object-oriented, and I can tell you I did not have C++ in mind."?](https://www.quora.com/What-did-Alan-Kay-mean-by-I-made-up-the-term-object-oriented-and-I-can-tell-you-I-did-not-have-C++-in-mind)
9. [Alan Kay at OOPSLA 1997 - The computer revolution hasnt happened yet](https://www.youtube.com/watch?v=oKg1hTOQXoY)
10. [Object-Oriented Programming, lecture by Daniel Ingalls](https://www.youtube.com/watch?v=Ao9W93OxQ7U): "Complex systems are hard to build with conventional programming languages. Object-oriented programming is an approach in which software organization corresponds closely to the system being simulated. When one supplants conventional procedure calls with the more general mechanism of sending messages, it greatly enhances the flexibility and reusability of software components."
11. [Daniel G Bobrow: Common LISP Object Standard 1987](https://www.youtube.com/watch?v=1zS46_HWRMo)
12. [Smalltalk-80: The Language and its Implementation](http://stephane.ducasse.free.fr/FreeBooks/BlueBook/Bluebook.pdf)
13. [Alan Kay](https://www.quora.com/What-are-the-main-successes-of-the-AI-group-at-Xerox-PARC-during-the-70s-and-first-half-of-the-80s-How-much-influence-did-it-have-on-other-groups-like-Smalltalk-group-and-vice-versa/answer/Alan-Kay-11): "This was my initial plan for Smalltalk. Fate intervened with something else. But these ideas reflected back to Carl Hewitt in his later “Actor” ideas, which are more like the early Smalltalk ideas, and which went beyond in a number of ways."
14. From SICP: "The point of exhibiting the procedural representation of pairs is not that our language works this way (Scheme, and Lisp systems in general, implement pairs directly, for efficiency reasons) but that it could work this way. The procedural representation, although obscure, is a perfectly adequate way to represent pairs, since it fulfills the only conditions that pairs need to fulfill. This example also demonstrates that the ability to manipulate procedures as objects automatically provides the ability to represent compound data. This may seem a curiosity now, but procedural representations of data will play a central role in our programming repertoire. This style of programming is often called **message passing** ..."  
15. [Object-Oriented Style - Daniel P. Friedman](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.69.7199&rep=rep1&type=pdf)
16. [If one starts with a state of the art object-oriented programming from the late 80s and early 90s (Smalltalk, Self, CLOS), what could have been the next breakthrough in that style of programming, but never happened?](https://www.quora.com/If-one-starts-with-a-state-of-the-art-object-oriented-programming-from-the-late-80s-and-early-90s-Smalltalk-Self-CLOS-what-could-have-been-the-next-breakthrough-in-that-style-of-programming-but-never-happened)


#### Internet of objects  

1. [The LOCUS Distributed System Architecture](https://www.amazon.com/Distributed-System-Architecture-Computer-Systems/dp/0262161028/ref=sr_1_4?ie=UTF8&qid=1514807872&sr=8-4&keywords=locus+system)  
2. [NAMING AND SYNCHRONIZATION IN A DECENTRALIZED COMPUTER SYSTEM](http://publications.csail.mit.edu/lcs/specpub.php?id=773)  
3. Alan Kay: "Part of the idea behind “real objects” was to act as “virtual machines” connected by “neutral messages” in the very same way as we were starting to design the Internet — and that the “virtual internet of objects” would map into the subsequent hardware network."  
4. [The Early History of Smalltalk](http://worrydream.com/EarlyHistoryOfSmalltalk/): "In computer terms, Smalltalk is a recursion on the notion of computer itself. Instead of dividing "computer stuff" into things each less strong than the whole—like data structures, procedures, and functions which are the usual paraphernalia of programming languages—each Smalltalk object is a recursion on the entire possibilities of the computer. Thus its semantics are a bit like having thousands and thousands of computers all hooked together by a very fast network."  


#### Protocol-oriented programming

1. [Object-Oriented Programming in COMMON LISP: A Programmer's Guide to CLOS](https://www.amazon.com/Object-Oriented-Programming-COMMON-LISP-Programmers/dp/0201175894)  
2. [Scott McKay at Dynamic Languages Wizards Panel (runtime topic)](https://www.youtube.com/watch?v=SjbtEnfm7_Q)  
3. [The Art of the Metaobject Protocol](https://www.amazon.com/Art-Metaobject-Protocol-Gregor-Kiczales/dp/0262610744/ref=sr_1_1?s=books&ie=UTF8&qid=1511408030&sr=1-1&keywords=metaobject+protocol)
4. [Seminar on Object Oriented Programming](https://www.youtube.com/watch?v=QjJaFG63Hlo)
5. [Design Principles Behind Smalltalk](https://www.cs.virginia.edu/~evans/cs655/readings/smalltalk.html)
6. Protocols (interfaces) are collections of functions.  
CLOS: protocol, generic function, method  
Smalltalk: protocol, "message handler", method  
7. [Clojure Protocols](https://clojure.org/reference/protocols)

#### Actors
[Akka Actors](https://doc.akka.io/docs/akka/current/actors.html)

#### Questions
1. Does message-oriented middleware have anything to do with real object-oriented programming?
2. Are Java interfaces equivalent to protocols in Smalltalk? (some [hints](https://en.wikipedia.org/wiki/Protocol_(object-oriented_programming)))  
3. Is OOP presented in [SICP](https://mitpress.mit.edu/sicp/full-text/book/book-Z-H-19.html#%_chap_3) real OOP?  
4. Does Java EE and other kinds of frameworks make Java into a real OOP language? Are they created to fix Java?
5. What is the importance of blocks in Smalltalk? Are blocks making a difference between real and normal OOP?   
6. Is middleware "stuff between objects", that is more important than objects themselves?
