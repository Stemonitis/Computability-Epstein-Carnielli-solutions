Show that the equality function 

<img src="http://latex.codecogs.com/gif.latex?E(m,n)=\left\{\begin{matrix}1&if&m=n&\\0&if&m=n\end{matrix}\right." border="0"/>

is TM computable.

Let1s write a code for this Turing Machine.

First, let`s got to the end of the first input.
q1 1 R q1
q1 0 R q2

at this point our algorithm divides into two branches. First one in case there is second input, and the second, there is not.
In case there is second input, we go to the end of it and delete the last 1.

q2 1 R q3
q3 1 R q3
q3 0 L q4 
q4 1 0 q4
q4 0 L q5

Now we have deleted the last 1 and we are now at the end of the last number. Let`s move to the beginning of the last number 
and delete the first 1 in the beginning of it.

q5 1 L q5
q5 0 L q6
q6 1 L q6
q6 0 R q7
q7 1 0 q7
q7 0 R q1

Now this process is repeated until one of the rows of one is empty. This will result state q2 being equal to zero. 

q2 0 R q8

We have three possibilities here. First is that the second number is bigger. We can test it by moving one step to the right 
and checking if there is a 1 there.

q2 0 R q8

If our hypothesis is true we would have to delete all the 1`s in the row, but one and halt on it.

q8 1 0 q9
q9 0 R q10
q10 0 1 q11 ... halt
q10 1 0 q9

Second and third possibility is that number 1 is bigger or the two numbers are equal. In this case state q8 will be equal to 
zero. 
To discern these two possibilities we will have to move two steps left and check whethere there is 1 there.

q8 0 L q12
q12 0 L q13

Now if q13=0, then the two numbers are equal and we can halt. If q13=1, then we have to delete all 1`s but one and halt on the
remaining 1.

q13 1 0 q14
q14 0 L q15
q15 0 1 q11 ... halt
q15 1 0 q14







