Consider the alphabet (,), ->,<img src="http://latex.codecogs.com/gif.latex?\mathbb{k}" border="0"/>, p0,p1,p2,... . We define
a word as follows:

i.(pi) is a word for i=0,1,2,...
ii.If A and B are words, so too are (A->B) and (<img src="http://latex.codecogs.com/gif.latex?\mathbb{k}" border="0"/>B)
iii. A string of symbols is a word if and only if it arises via application of (i) and (ii).

Number all words effectively. (Hint: Consider the numbering in C).

First lets number all the symbols, like (,) is 1, -> is 2 etc. Then, we use the fundametal theorem of arithmetic to number all 
the words in this alphabet. Prime number will indicate the position of symbol and the exponent of this prime number will 
indicate the symbol itself. For example, the word po,p1->p3, will be encoded as: <img src="http://latex.codecogs.com/gif.latex?2^{4}*3^{1}*5^{5}*7^{2}*11^{7}" border="0"/>
