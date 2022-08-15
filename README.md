# Programming DSA-using-Python-week-1 quiz solutions July 2022

# What does h(27993) return for the following function definition?

def h(x):

(d,n) = (1,0)

while d <= x:

(d,n) = (d*3,n+1)

return(n)

Answer 10

# What is g(60) - g(48), given the definition of g below?

def g(n): 

s=0


for i in range(2,n):

if n%i == 0:

s = s+1

return(s)
    
    answer 2
   
# Consider the following function f.

def f(n): 

s=0

for i in range(1,n+1):

if n//i == i and n%i == 0:

s = 1

return(s%2 == 1)

Answer :  n is a perfect square.

# Consider the following function foo.

def foo(m):

if m == 0:

return(0)

else:

return(m+foo(m-1))

Answer : The function terminates for non­negative n with foo(n) = n(n+1)/2






