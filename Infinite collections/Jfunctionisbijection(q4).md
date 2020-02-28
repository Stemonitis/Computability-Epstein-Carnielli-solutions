Prove that J is 1-1 and onto by showing that:

<img src="http://latex.codecogs.com/gif.latex?J(m,n)=\begin{cases}& \text{ the number of pairs (x,y ) such that  } \\ & \text{ x+y is less than m+n or (x+y=m+n) and x is less than m} \end{cases}" border="0"/>


To prove that J(m,n) is 1-1 and onto we first need to prove that every preceding pair of numbers, as x+y<m+n is assigned 
a number that is less, than the current one. In other words, we need to prove that for every x+y<m+n => J(x,y)<J(m,n).

So lets look at the base case:
J(0,0)>J(0,1), 0+0<0+1

<img src="http://latex.codecogs.com/gif.latex?\frac{1}{2}((0+0)(0+0+0))+0<\frac{1}{2}((0+1)(0+1+1))+0" border="0"/>
<img src="http://latex.codecogs.com/gif.latex?\0<1" border="0"/>

Then let`s prove that J(m,n)<J(m+1,n) and J(m,n)<J(m,n+1).

<img src="http://latex.codecogs.com/gif.latex?\frac{1}{2}((m+n)(m+n+1))+m<\frac{1}{2}((m+n+1)(m+n+2))+m+1" border="0"/>
obviously, true

and

<img src="http://latex.codecogs.com/gif.latex?\frac{1}{2}((m+n)(m+n+1))+m<\frac{1}{2}((m+n+1)(m+n+2))+m" border="0"/>
obviously, true

Secondly, we need to prove that J(x,y)<J(m,n), if x+y=m+n and x<m.
In another words we need to show that in case we have the same pair of numbers, but in different order, the J function will 
enumerate them separately, and will enumerate the pair with the bigger second number (n) first. So basicly we need to prove 
that in case m>n, => J(m,n)>J(n,m).

<img src="http://latex.codecogs.com/gif.latex?\frac{1}{2}((m+n)(m+n+1))+m>\frac{1}{2}((m+n)(m+n+1))+n" border="0"/>
<img src="http://latex.codecogs.com/gif.latex?m>n" border="0"/>



