Show that for every n the constant function lambdax(n) is TM computable. (Hint: Modify Example 1. Does your modification also 
calculate lambdaxlambday(n)?)

It is TM computable, because we can write a code for a TM to compute it.

q1 1 R q2
q1 0 1 q1...
q(n-1) 1 R qn
q(n-1) 0 1 q(n-1)
qn 1 0 q(n+1)
q(n+1) 0 R qn
qn 0 L q(n+2)
q(n+2) 1 L q(n+2)
q(n+2) 0 R q(n+3)

No, it does not. 
