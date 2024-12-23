We present a basic tool for analysing algorithms by Solving Recurrences
#### Divide and Conquer Paradigm:
- Divide
- Conquer
- Combine

We use recurrences to characterise the running-time of a divide and conquer algorithm. Solving the recurrence gives us the asymptotic running time.

A recurrence is defined in terms of:
- 1+ Base cases
- Itself, with smaller arguments

#### EXAMPLES FOR RECURRENCES (1):
- lmao good luck idk what the fuck im looking at
- ![[Pasted image 20241223150355.png]]
- ![[Pasted image 20241223150406.png]]

#### MAIN TECHNICAL ISSUES WITH RECURRENCES:
- Exact VS Asymptotic Functions
	- Sometimes we want the exact analysis of an algorithm.
	- Mostly, we want an asymptotic analysis however.
- Boundary Conditions
	- Runtime on small inputs is bounded by a constant
		- T(n) = (-)(1) for small n.
	- We usually dont mention this constant however as it doesnt affect the rate of growth
	- These are only important if we care about exact solutions
- Floors and Ceilings
	- 