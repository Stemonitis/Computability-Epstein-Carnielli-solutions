A famous function defined by induction is the Fibonacci series:

<img src="http://latex.codecogs.com/gif.latex?1,1,2,3,5,8,13,..., u_{n+2}=u_{n+1}+u_{n}" border="0"/>

To calculate <img src="http://latex.codecogs.com/gif.latex?u_{n}" border="0"/> we need to know what`s been calculated in the 
previous two steps, which, backtracking, we can do once we get to the first two terms. See if you can devise a definition of 
<img src="http://latex.codecogs.com/gif.latex?f(n)=u_{n}" border="0"/> as a primitive recursive function. 

<img src="http://latex.codecogs.com/gif.latex?f(1)=1" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?f(2)=1" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?f(n+1)=+(P^{1}_{2}(f(n-1),n-1), P^{1}_{2}(f(n),n))" border="0"/>
