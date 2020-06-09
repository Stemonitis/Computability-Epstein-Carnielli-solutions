Demonstrate that following functions are primitive recursive:

1)
<img src="http://latex.codecogs.com/gif.latex?<(x,y)=\left\{\begin{matrix}1&if&x&<&y& \\ 0&if&x&\geq&y \end{matrix}\right." border="0"/>

<img src="http://latex.codecogs.com/gif.latex?<(0,y)=S(Z(0))" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?<(x+1,y)=\dot{-}(S(P^{2}_{3}(<(x,y),x,y)),P^{3}_{3}(<(x,y),x,y))" border="0"/>

2)
<img src="http://latex.codecogs.com/gif.latex?E(x,y)=\left\{\begin{matrix}1&if&x&=&y& \\ 0&if&x&\neq&y \end{matrix}\right." border="0"/>

<img src="http://latex.codecogs.com/gif.latex?E(0,y)=0,\> where \> y\neq{}0 \; or" border="0"/>
<img src="http://latex.codecogs.com/gif.latex?E(0,y)=sg(y)" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?E(n+1,y)=\dot{-}(S(P^{2}_{3}(E(n,y),n,y)),P^{3}_{3}(E(n,y),n,y))" border="0"/>


