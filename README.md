Logical-Proof-Checker
=====================

### High-Level Description ###
``` 
Proof Checker for Propositional Logic Statements.
User types in Proof, parser verifies or invalidates statements line-by-line.
```  
### UI Design ###
##### Each input line will consist either of the word "print" appearing alone on the line (except for white space), or of a reason, followed by blank space, followed by an expression. A reason is one of the following: #####
```
    * show
    * assume
    * one of the words mp, mt, or co followed by blank space, followed by a line number and blank space and another line number
    * one of the words ic or repeat followed by blank space and a line number
    * the name of a theorem (see below)
    * The words ** "mp" **, ** "mt" ** , "co", and "ic", abbreviate the terms "modus ponens", "modus tollens", "contradiction", and "implication construction".
```



#### Background on Propositional Logic ####
[Propsitional Logic](http://inst.eecs.berkeley.edu/~cs61bl/su13/projects/proj2/prop.logic.html)

