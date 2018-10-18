#### Metalinguistic abstraction is the key for building robust systems ####

Gerry Sussman, [Lecture 3B](https://www.youtube.com/watch?v=X21cKVtGvYk): In order to make a system that is robust, it has to be insensitive to small changes, i.e. small change in the problem should lead only to the small change in the solution. There ought to be a continuity - the space of solutions out to be continous in the space of problems. The way to do that was instead of solving a particular problem at every level of decomposition of the problem into subproblems, what you solve is a class of problems which are in the neighbourhood of the particular problem you are trying to solve. The you do that is by producing a language at level of detail, in which the solutions to that class of problems is representable in that language. Therefore, when you make small changes to the problem you are trying to solve, you generally have to make only small changes to the solution you constructed because at the level of detail you are working there is a language where you can express various solutions to alternate problems of the same type.

---

#### Tower of languages ####

Creating a little language to solve a specific problem is the most effective 
technique yet devised for reducing complexity in software. ... For this reason, 
little languages work best in concert. The ideal technique for writing a 
complex program is to slice it into multiple problem-specific pieces and then
define a language for each problem slice. If we slice the program vertically, 
the result is a “tower” of languages, layered atop one another. Regardless 
of how we slice the overall problem, we can use the right language, and 
the right paradigm, for each subproblem.

 WILLIAM E. BYRD AND DANIEL P. FRIEDMAN (Authors of The Reasoned Schemer) in foreword to the book "The Joy of Clojure"
 
 ---

#### The power of Lisp ####

There is more general point about the structure of this system, the structure of the system as creating a language, viewing the engineering design process as one of creating a language or rather one of creating sequence of layers of language. There is this methodology or maybe I should say mythology, that is charitably called software engineering. It says: you go and figure out your task, and you figure out exactly what you want to do, and once you do that, you find out that it breaks out into 3 subtasks, and you work on this subtask and you figure out exactly what that is, and that breaks down into 3 subtasks and you specify them completely, and you work on this sub-one, etc. At the end you end up with this beautiful edifice, a marvelous tree. Each of the nodes in the tree is exactly and precisely defined to do the wonderful, beautiful task to make it fit into the whole edifice. That's this mythology. Only computer scientists could possibly believe that you can build complex system like that. Contrast that with this Henderson example - it did not work like that. What happened is that there was a sequence of layers of language. ... Things at each layer happend with the reference to things from the layer bellow. At each level, objects that are being talked about are the things that are being errected at the previous level. What is the difference between this thing and the tree? In the tree, each node, each decomposition, is being designed to do a specific task. In the other scheme what you have is full range of linguistic power at each level. What is happening there at any level, it is not set up to do a particular task, but to be talk about the whole range of things. The consequence of that for design is that something that's designed with that method is likely to be more robust. By robust I mean that if you go a make a change in your description, it is more likely going to be captured by a corresponding change in the way that the language is implemented at the next level up. You are not talking about particular thing called "beside", but you have given yourself whole vocabulary to express things of that sort, so that if you change your specification a little bit it is more likely that your methodology is going to be able to adapt to capture that change, whereas the desing like in the tree is not going to be robust because if I change something here, that might affect the entire way I decomposed everything further down the tree. That is very big difference in outlook in decomposition - levels of language rather then strict hierarchy. Not only that, but when you have levels of language you've given yourself different vocabularies for talking about design at different levels. That is a big point about the difference in software methodology that comes out from Lisp, and it all comes from the notion that really the design process is not so much implementing programs as implementing languages. That is really the power of Lisp.  

Hal Abelson in [SICP lecture, 1986](https://www.youtube.com/watch?v=2QgZVYI3tDs&index=5&list=PL8FE88AA54363BC46); starts at 1:08:15  

