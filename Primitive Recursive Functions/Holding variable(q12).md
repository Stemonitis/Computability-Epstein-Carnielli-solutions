a. Show that by holding one variable fixed in a primitive recursive function we obtain a primitive recursive function. That is, 
given that <img src="http://latex.codecogs.com/gif.latex?\lambda{n}\lambda\vec{x}f(n,\vec{x})" border="0"/> is primitive
recursive, show that for every n, <img src="http://latex.codecogs.com/gif.latex?\lambda\vec{x}f(n,\vec{x})" border="0"/> is
primitive recursive. (Hint:Use C.1.)

If <img src="http://latex.codecogs.com/gif.latex?\lambda{n}\lambda\vec{x}f(n,\vec{x})" border="0"/>, then for every n it is 
primitive recursive. Than in this case to prove that f(n+1, x) we just look at the n+1 as S(n). Sucessor function is primitive
recursive as is the composition of functions. That means that for every n can be viewed as a function. 


b. Use part (a) and Exercise 1 to show that if f is primitive recursive, so are

<img src="http://latex.codecogs.com/gif.latex?\lambda\vec{x}\sum^{n}_{i=1}f(i,\vec{x})" border="0"/> and 
<img src="http://latex.codecogs.com/gif.latex?\lambda\vec{x}\prod^{n}_{i=1}f(i,\vec{x})" border="0"/>

In this case we apply function f n times, and if all of the functions inside are primitive recursive than the sum and product 
of them should be too. 


