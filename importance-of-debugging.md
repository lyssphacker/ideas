#### Questions
1. Is there an art of debugging?  
2. For most workaday programmers, and even for desingers, a lot time is spent debugging an existing system. What can be done to make that simpler?  
3. Should systems be deliberately expressed in lower level languages to make debugging easier? It is very hard to debug system written in higher level language, especially if it is dynamically typed.  

#### Resources
[Debugging with the Scientific Method - Stuart Halloway](https://www.youtube.com/watch?v=FihU5JxmnBg)  

[Revised Report on the Propagator Model](https://groups.csail.mit.edu/mac/users/gjs/propagators/):  
"The most important problem facing a programmer is the revision of an existing program to extend it for some new situation. Unfortunately, the traditional models of programming provide little support for this activity. The programmer often finds that commitments made in the existing code impede the extension, but the costs of reversing those commitments are excessive.
Such commitments tend to take the form of choices of strategy. In the design of any significant system there are many implementation plans proposed for every component at every level of detail. However, in the system that is finally delivered this diversity of plans is lost and usually only one unified plan is adopted and implemented. As in an ecological system, the loss of diversity in the traditional engineering process has serious consequences.
The Propagator Programming Model is an attempt to mitigate this problem. It is a model that supports the expression and integration of multiple viewpoints on a design. It incorporates explicit structure to support the integration of redundant pieces and subsystems that solve problems in several different ways. It will help us integrate the diversity that was inherent in the design process into the delivered operational product."  
Is this related to debugging as well?

[New Architectural Models for Visibly Controllable Computing: The Relevance of Dynamic Object Oriented Architecturesand Plan Based Computing Models](https://dspace.mit.edu/handle/1721.1/30447?show=full)  

[Steps toward better debugging tools for LISP](https://dl.acm.org/citation.cfm?doid=800055.802041)  

[Dynamic Language Wizards - runtime](http://www.youtube.com/watch?v=SjbtEnfm7_Q&t=1h26m51s)  
Audience: Source-level debugging is important in designing a language. How do you resolve the tension between that feature and having code generators, like hygenic macros or source generation facilities?  
Dave Moon: I got to be smart in your source-level debugger. It has to be able to backtrack all the way from the machine-code bits to the original source code and everything in between. That is not always easy. We never solved that on the Lisp Machine.  
Scott McKay: We came close in Harlequin Dylan, but rule-based macros stuff makes it easier than Lisp-style macros. Good research project. 

[If Tony Hoare said that “debugging is harder than programming and you shouldn’t use all of your cleverness to write the program” — or make anything — then what role does planning have in engineering and software design?](https://www.quora.com/If-Tony-Hoare-said-that-%E2%80%9Cdebugging-is-harder-than-programming-and-you-shouldn%E2%80%99t-use-all-of-your-cleverness-to-write-the-program%E2%80%9D-%E2%80%94-or-make-anything-%E2%80%94-then-what-role-does-planning-have-in-engineering-and-software-design)
