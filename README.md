sicp_exercises
==============

My sicp exercise solutions are in chapter files.  eg ch1.txt

Here are my notes on reading book.

Chapter 1 section 1.

substitution model for procedure application.  You replace formal params - and then work through 
 - eg evaluating parts in brackets or apply functions.


fully expand and then reduce model - called normal order evaluation.

evaluate args then apply  - applicative order - which interpreter actually uses

what applicative order means is that if you call (square (+ 1 2)) then it will be evaluated in these steps:

1. (+ 1 2) is evaluated to return 3

2. Then the square function is called like this: (square 3)

Other languages like C also use applicative order.
