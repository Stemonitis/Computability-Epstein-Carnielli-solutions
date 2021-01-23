Show that the function e(x)=x^x is primitive recursive. Describe the function f(n,x) obtained by iteration of e. Calculate f(3,2), f(3,3), f(10,10). Try to 
describe in informal mathematical notation the function g that arises by iteration of lambda(x)f(x,x). Calculate g(3).

<img src="http://latex.codecogs.com/gif.latex?e(x)=x^{x}=\cdot^{(x)}(x)"/>


<img src="http://latex.codecogs.com/gif.latex?f(n,x)=x"/>

<img src="http://latex.codecogs.com/gif.latex?f(n+1,x)=e(e(x))"/>

<img src="http://latex.codecogs.com/gif.latex?f(3,2)=((2^{2})^{2^{2}})^{(2^{2})^{2^{2}}}=(4^{4})^{4^{4}}=256^{256}"/>

<img src="http://latex.codecogs.com/gif.latex?f(3,3)=((3^{3})^{3^{3}})^{(3^{3})^{3^{3}}}=(27^{27})^{27^{27}}=(4,434264882\times{}10^{38})^{4,434264882\times{}10^{38}}"/>

<img src="http://latex.codecogs.com/gif.latex?f(10,10)=....Infinity"/>

<img src="http://latex.codecogs.com/gif.latex?f(x,x)=e^{(x)}(x)"/>

 If we iterate f(x) even further we will get:
 
 <img src="http://latex.codecogs.com/gif.latex?g(x)=e^{(e^{(x)}(x))}(x)"/>
 
Absolutely insane!!, but still primitive recursive.

 <img src="http://latex.codecogs.com/gif.latex?g(3)=e^{(4,434264882\times{}10^{38})^{4,434264882\times{}10^{38}}}(3)"/>
 
 I will leave the calculations of the actual number to dearest authors of this book.


