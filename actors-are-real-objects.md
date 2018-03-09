### Are actors real objects?



[Objects as Actors ?](http://debasishg.blogspot.hr/2009/04/objects-as-actors.html)  
coming full circle: actually, the circle is even "fuller" than you realize. It dates back even further than Actors, since Carl Hewitt's paper was actually heavily inspired by Smalltalk-71. Originally, Actors and Objects were one and the same, so much so, that there weren't even two different words to describe them – they were just called objects.

This isn't really too surprising, considering that object-oriented programming was invented by two real-world simulation guys (Ole-Johan Dahl and Kristen Nygaard) and a microbiologist (Alan Kay). Both real world objects and biological cells are actors, so it seemed completely natural to these guys to model programming with a network of independent, concurrent entities that communicate with each other via message passing.

This was so obvious to them that they didn't even realize that they had invented a new concurrency paradigm, until Alan Kay gave Carl Hewitt a demonstration of Smalltalk-71, and Hewitt realized that the message-directed execution model of Smalltalk-71 (inspired by PLANNER's pattern-directed execution) could be extracted into it's own paradigm.

Unfortunately, then, Alan Kay made what he would later call one of the biggest mistakes in his lifetime: some of his compiler-savvy colleagues convinced him that he would never be able to implement this efficiently, and in what is probably one of the most tragic instances of premature optimization gone horribly wrong, Kay made two design changes to Smalltalk: he replaced the message-passing execution model with conventional subroutine calls and he introduced the idea of classes.

From then on, Actors and Objects went their separate ways … 


