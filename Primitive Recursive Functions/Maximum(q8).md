Denote the maximum of <img src="http://latex.codecogs.com/gif.latex?x_{1},...,x_{n}" border="0"/> by <img src="http://latex.codecogs.com/gif.latex?max(x_{1},...x_{n})" border="0"/>.
Show that this is primitive recursive. (Hint: cf C.1; there is one function for each n.)

for n=2

<img src="http://latex.codecogs.com/gif.latex?max(x,y)=x+(y\dot{-}x)" border="0"/>
<img src="http://latex.codecogs.com/gif.latex?max(x_{1},x_{2},n)=x+(x_{2}\dot{-}x_{1})" border="0"/>
<img src="http://latex.codecogs.com/gif.latex?max(x_{1},x_{2},...,x_{n+1},n+1)=+(\cdot(x_{n+1},<(max(\vec{x_{n}},n),x_{n+1})),\cdot{}(sg(<(max(x_{n},n),x_{n+1})))))" border="0"/>


