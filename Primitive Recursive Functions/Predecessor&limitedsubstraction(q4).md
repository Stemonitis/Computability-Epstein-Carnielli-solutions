Show that the predecessor and limited substraction are primitive recusrsive.

Predecessor:

<img src="http://latex.codecogs.com/gif.latex?P(0)=0"/>

<img src="http://latex.codecogs.com/gif.latex?P(n+1)=n"/>

formal

<img src="http://latex.codecogs.com/gif.latex?P(0)=Z(0)"/>

<img src="http://latex.codecogs.com/gif.latex?P(n+1)=P_{2}^{2}(P(n),n)"/>


Limited substraction:

<img src="http://latex.codecogs.com/gif.latex?x\dot-n=\left\{\begin{matrix}x-n&if&n\leqslant{x}& \\ 0&if&n>x \end{matrix}\right."/>

formal 

<img src="http://latex.codecogs.com/gif.latex?\dot-(0,x_{1})=Z(0)"/>

<img src="http://latex.codecogs.com/gif.latex?\dot-(n+1,x_{1})=P(P^{1}_{3}(\dot-(n,x_{1}), n, x_{1}))"/>
(in this case we ignore the condition, because P(0)=0 anyway)
