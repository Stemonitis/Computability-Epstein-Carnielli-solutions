Demonstrate that   <img src="http://latex.codecogs.com/gif.latex?\overline{sg}" border="0"/> and sg are primitive recursive.

Signature

<img src="http://latex.codecogs.com/gif.latex?sg(0)=0" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?sg(n+1)=1" border="0"/>

Formal:

<img src="http://latex.codecogs.com/gif.latex?sg(0)=Z(0)" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?sg(n+1)=S(Z(P^{1}_{1}(sg(n),n)))" border="0"/>

Zero-test

<img src="http://latex.codecogs.com/gif.latex?\overline{sg}(0)=1" border="0"/>

<img src="http://latex.codecogs.com/gif.latex?\overline{sg}(n+1)=0" border="0"/>

Formal:

<img src="http://latex.codecogs.com/gif.latex?\overline{sg}(0)=S(Z(0))" border="0"/>


<img src="http://latex.codecogs.com/gif.latex?\overline{sg}(n+1)=Z(P^{1}_{1}(\overline{sg}(n),n))" border="0"/>
