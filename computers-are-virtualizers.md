[Alan Kay](http://www.youtube.com/watch?v=tp9VbtLn2Jw&t=32m40s): "You can almost always make something that scales very very well by completely virtualizing the computer you have into some new kind of computer that's kind of."  

If one can take LOC measure as a kind of metric for scalability, then it is useful to take a look at an example of Genera, the programming environment on Lisp Machines, which was implemented with roughly 1 million LOC, but provides comparable experience as any modern operating system (Windows, GNU/Linux, Mac) whose LOC go over several hunders LOC.  

What enabled the concise implementation of Genera?  

Were Genera designers able to virtualize the underlying machine into something very different? it is clear that Genera conceptually looks quite a bit different than a Unix machines back then (what about now?).  

![](http://lispm.de/images/figure4.gif)  
*Lisp Machine*

![](http://lispm.de/images/figure3.gif)  
*Unix Machine*

Howard Shrobe and Robert Laddaga wrote a [paper](https://dspace.mit.edu/handle/1721.1/30447) trying to explain what made Genera different - small (in terms of LOC) but powerful.  

They wrote: 

*Traditionally, we've focussed on the question of how to make a system easy to code the first time, or perhaps on how to ease the system's continued evolution. But if we look at life cycle costs, then we must conclude that the important question is how to make a system easy to operate. To do this we need to make it easy for the operators to see what's going on and to then manipulate the system so that it does what it is supposed to. This is a radically different criterion for success.What makes a computer system visible and controllable? This is a difficult question, but it's clear that today's modern operating systems with nearly 50 million source lines of code are neither. Strikingly, the MIT Lisp Machine and its commercial successors provided almost the same functionality as today's mainstream sytsems, but with only 1 Million lines of code. This paper is a retrospective examination of the features of the Lisp Machine hardware and software system. Our key claim is that by building the Object Abstraction into the lowest tiers of the system, great synergy and clarity were obtained.It is our hope that this is a lesson that can impact tomorrow's designs. We also speculate on how the spirit of the Lisp Machine could be extended to include a comprehensive access control model and how new layers of abstraction could further enrich this model.*

Key points they make:
