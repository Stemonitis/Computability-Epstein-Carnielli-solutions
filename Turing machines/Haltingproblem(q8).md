The halting problem of Turing machines.
From Exercise 7 we can list all Turing machines M0, M1,...,Mn,...(let the nth one be the machine which has the nth largest 
number assigned to it). Each calculates a function of one variable (although that may be undefined for every input). Show that 
the function 

<img src="http://latex.codecogs.com/gif.latex?h(m,n)=\left\{\begin{matrix} 0&if&M_{m}&halts&on&input&n\\1&if&otherwise\end{matrix}\right." border="0"/>

known as the halting problem for Turing machines, is not Turing machine computable. 
(Hint: if there were a machine H that computed h, we could define another Turing machine, that, 
given input n,
a. writes 1^(n+1)01^(n+1))
b. implements H on that input, and then
   if the result is blank tape, it writes a 1 and halts,
   if the result is a single 1 on the tape, it goes into the loop and never halts.
What would the number of that new machine be?).

https://www.tutorialspoint.com/automata_theory/turing_machine_halting_problem.htm
