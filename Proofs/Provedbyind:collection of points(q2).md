Prove by induction: Given any collection of n points in the plane no three of which lie on the line, there are exactly 
1/6n(n-1)(n-2) triangles that can be formed by the line segments joining the points.

Lets look at the base case, 3 points.

<img src="http://latex.codecogs.com/gif.latex?\frac{1}{6}\cdot{3}\cdot{(3-1)}(3-2)=\frac{1}{2}\cdot{2}\cdot{1}=1" border="0"/>

Then for every new point the number of triangles is equal to the combination of points in groups of 2.

<img src="http://latex.codecogs.com/gif.latex?C\binom{n}{2}=\frac{n!}{2!(n-2)!}" border="0"/>

So,

<img src="http://latex.codecogs.com/gif.latex?\frac{1}{6}\cdot{n}\cdot{(n-1)}(n-2)+\frac{n!}{2!(n-2)!}=\frac{1}{6}\cdot{n}(n-1)(n-2)+\frac{n(n-1)}{2}^{(\cdot{3}}=" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?\frac{n(n-1)(n-2)}{6}+\frac{3n(n-1)}{6}=\frac{n(n-1)(n-2)+3n(n-1)}{6}=\frac{(n-1)(n^{2}-2n+3n)}{6}=" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?\frac{(n-1)(n^{2}+n)}{6}=\frac{1}{6}\cdot{(n-1)(n+1)n}=\frac{1}{6}\cdot{n}(n^{2}-1)" border="0"/>


