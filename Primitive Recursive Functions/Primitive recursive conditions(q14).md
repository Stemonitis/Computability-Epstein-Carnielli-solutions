Show that if P and Q are primitive recursive conditions, then so are 
<img src="http://latex.codecogs.com/gif.latex?P\wedge{Q},P\vee{Q},\neg{P}\thinspace{and}\thinspace{P}\rightarrow{Q}" />.


<img src="http://latex.codecogs.com/gif.latex?P\wedge{Q}" /> means P and Q, or if P is true and Q is true, so in this case we can 
deploy a test function, which we have shown to be primitive recursive. Here is the definition: sg(sg(P)*sg(Q)). Then this 


<img src="http://latex.codecogs.com/gif.latex?P\vee{Q}" /> P is true or Q is true. So the proof is : sg(sg(P)+sg(Q))


<img src="http://latex.codecogs.com/gif.latex?\neg{P}"/>is simply <img src="http://latex.codecogs.com/gif.latex?\overline{sg}(P)" />


<img src="http://latex.codecogs.com/gif.latex?P\rightarrow{Q}"/>, which is <img src="http://latex.codecogs.com/gif.latex?\neg{P}\wedge{Q}" />
which is composition of functions we have proven to be primitive recursive. 
