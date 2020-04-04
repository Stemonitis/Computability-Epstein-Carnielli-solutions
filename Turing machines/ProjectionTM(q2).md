a. Define a TM that calculates the projection function on the first coordinate, P(m,n)=m.

q1 1 R q1
q1 0 R q2
q2 1 R q2 
q2 0 L q3
q3 1 0 q2
q3 0 L q4
q4 1 L q4
q4 0 R q5

b. For every k and j such that k>=i>=1 define a TM that calculates the projection on the ith coordinate, <img src="http://latex.codecogs.com/gif.latex?P^{i}_{k}(n_{1}, n_{2},...,n_{k})=n_{i}" border="0"/>

First, we need to write i ones on the left of the string. We assume that i>0, otherwise our turing machine will halt.
q1 1 L q1
q1 0 L q2
q2 0 1 q2
q2 1 L q3
qi 0 1 qi
qi 1 L q(i+1)

q(i+1) 0 R q(i+1)
q(i+1) 1 R q(i+2)

q(i+2) 1 L q(i+3)
q(i+3)


q1 0 L q2
q2 1 L q2
q2 0 L q3
qi 



