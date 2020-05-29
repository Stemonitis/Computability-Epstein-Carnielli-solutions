Give a definition of multiplication as a primitive recursive function that precisely fits the specifications of B. Compare 
that definition to the Turing machine definition in Chapter 9 C.

<img src="http://latex.codecogs.com/gif.latex?\cdot(0,x_{1})=P^{1}_{1}(x_{1})" border="0"/>
<img src="http://latex.codecogs.com/gif.latex?\cdot(n+1,x_{1})=+(P^{1}_{3}(\cdot(n,x_{1}),n,x_{1}),P^{3}_{3}(\cdot(n,x_{1}),n,x_{1}))" border="0"/>

The defintion is suprisingly similar.
