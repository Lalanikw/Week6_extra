Module: Random()

This module impletes pseudo-random number generators for various distributions. 
For integers, uniform selection from a range. For sequences, uniform selection 
of a random element, a function to generate a random permutation of a list 
in-place, and a function for random sampling without replacement. 

On the real line, there are functions to compute uniform, normal (Gaussian), 
lognormal, negative exponential, gamma, and beta distributions. For generating 
distributions of angles, the von Mises distribution is available. 

Examples:
for integers:
random.randrange([start], stop [step]) - return a randomly selected element from range (start, stop, step). 

for sequences:
random.choice(seq) - return a random element from the non-empty sequence. 

>>> random.random()       
0.37444887175646646

>>> random.uniform(1, 10)  
1.1800146073117523

>>> random.randint(1, 10)  
7

>>> random.randrange(0, 101, 2)  
26

>>> random.choice('abcdefghij')  
'c'


