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


q1 1 0 q2
q2 0 R q1
q1 0 R q2

q2 1 0 q3
q3 0 R q2
q2 0 R q3

q(i-1) 1 0 qi
qi 0 R q(i-1)
q(i-1) 0 R qi 
....
We arrived at the number in the sequence that we want to keep. If it i=1 we will, obviously, start from this point. 

qi 1 L qi
qi 0 L q(i+1)

After leaving the projection we want to erase all the numbers till k. We repeat the same procedure.

q(i+1) 1 0 q(i+2)
q(i+2) 0 R q(i+1)
q(i+1) 0 R q(i+2)...

qk 1 0 q(k+1)
q(k+1) 0 R qk
qk 0 R q(k+1)...

And now we have to go back to the beginning.

q(k+1) 0 L q(k+1)
q(k+1) 1 L q(k+2)
q(k+2) 1 L q(k+2)
