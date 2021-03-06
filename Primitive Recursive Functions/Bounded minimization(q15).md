a. Show that if h and g are primitive recursive, then so is f, where <img src="http://latex.codecogs.com/gif.latex?f(\vec{x}) =min \thinspace{} y_{y\leq{g(\vec{x})}} [h(\vec{x},y)=0]"/>.

We proved that min is primitive recursive and all of the other functions included in this composition of functions are primitive recursive as well. Also because y is bounded beyond certain limit we can be sure that the number of steps we need to obtain the result are predefined. 
<img src="http://latex.codecogs.com/gif.latex?f(x,y,n)=\neg(min(\leq(y,n))\vee{}\overline{sg}(h(\vec{x},y)))\wedge{n}" />.

b. Show that if a function g and predicate Q are primitive recursive, then so is f , where <img src="http://latex.codecogs.com/gif.latex?f(\vec{x}) =min \thinspace{} y_{y\leq{g(\vec{x})}} [Q(\vec{x},y)]"/>

All primitive recursive predicates can be easily defined as a primitive recursive function. 

c. Show that if the predicate P and function g are primitive recursive, then so are the predicates <img src="http://latex.codecogs.com/gif.latex?\exists{y}\leq{g(\vec{x})}[P(\vec{x},y)]"/> and <img src="http://latex.codecogs.com/gif.latex?\forall{y}\leq{g(\vec{x})}[P(\vec{x},y)]"/>.

These predicates can be obtained from bounded minimization. Also, every y is bounded, so we can define the number of steps before the definition. 

d. Repeat parts (a)-(c) with "<=" replaced by "<".

In all the definitions all the less or equal functions have to be replaced by less.

