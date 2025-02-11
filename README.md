# The O, Omega, and Theta

Each row in the table below specifies two functions $f(n)$ and $g(n)$.
Fill in the *number* from this list that best describes their relationship:

1. $f(n)\in O(g(n))$, but $f(n)\not \in \Omega(g(n))$
1. $f(n)\in \Omega(g(n))$, but $f(n)\not \in O(g(n))$
1. $f(n)\not\in O(g(n))$, and $f(n)\not \in \Omega(g(n))$
1. $f(n)\in \Theta (g(n))$

I have done the first one for you, as an example.

| $f(n)=\ldots$              | compared to | $g(n)=\ldots$          |
|----------------------------|:-----------:|------------------------|
| $f(n)=n$                   | 1           | $g(n)=2n^2 + n$        |
| $f(n)= 10n + 3\log_{15} n$ | 4           | $g(n)= 4n - 2\log_2 n$ |
| $f(n) = 2n^5$              | 2           | $g(n) = 5n^2$          |
| $f(n)=\log_{10} \left(n^{10}\right)$ | 1 | $g(n)=n$ |
| $f(n)= 4n^5 $ | 2 | $g(n)= 5n^4$ |
| $f(n) = 10^{256}$ | 1 | $g(n) = \log n$ |
| $f(n)= n^2 $ | 1 | $g(n)= 2^n$ |


### Sources and Plagiarism 

Sources: 

https://eng.libretexts.org/Bookshelves/Computer_Science/Programming_Languages/Think_Python_-_How_to_Think_Like_a_Computer_Scientist_(Downey)/13%3A_Appendix_B-_Analysis_of_Algorithms/13.01%3A_Order_of_Growth

https://www.geeksforgeeks.org/difference-between-big-oh-big-omega-and-big-theta/

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
