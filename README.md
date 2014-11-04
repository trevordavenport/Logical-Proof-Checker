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
    * The words "mp", "mt", "co", and "ic", abbreviate the terms "modus ponens", "modus tollens", "contradiction", and "implication construction".
```
### Format of Expressions ###
```
   * a variable (a lower-case letter) is an expression;
   * if E is an expression, then ~E is an expression;
   * if E1 and E2 are expressions, then (E1&E2) and (E1|E2) are expressions;
   * if E1 and E2 are expressions, then (E1=>E2) is an expression.
```
###### Application of a Theorem: ######
>   and1 (((a|b)&~c)=>(a|b))



#### Background on Propositional Logic ####
[Propsitional Logic](http://inst.eecs.berkeley.edu/~cs61bl/su13/projects/proj2/prop.logic.html)

