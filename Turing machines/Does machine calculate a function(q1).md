a. Does the machine of Example 2 calculate a function?

Yes. f(n)=2n

b. Define a TM (i.e., give a collection of quadruples) that for every n duplicates a string of the form 1^n, creating 1^n01^n.
Does this machine calculate any function?

q1 1 0 q2
q2 1 R q2
q2 0 R q3
q3 0 1 q4
q4 1 L q4
q4 0 L q5
q5 1 L q5
q5 0 R q1
q1 0 1 q6
q6 1 L q6

No, because it takes one input and gives two outputs. 

