---
{"Class":"Pre-Calculus","Date":"01.10.23","Type":"Review / study guide","tags":["pre-calculus","wiki","S1"],"dg-publish":true,"permalink":"/pre-calculus/semester-1-wiki-pc/","dgPassFrontmatter":true}
---

#### Chapter 1
- ###### Domain & range  of different parent functions
	- **Constant**: $f(x)=c$ 
		- Domain: $\mathbb{R}$
		- Range: $[c,c]$
	 - **Linear**: $f(x)=x$ 
		- Domain: $\mathbb{R}$
		- Range: $\mathbb{R}$
	 - **Quadratic**: $f(x)=x^2$ 
		- Domain: ($-\infty,+\infty$)
		- Range: $[0,+\infty]$
	 - **Square root**: $f(x)=\sqrt{ x }$ 
		- Domain:  $(0,\infty)$
		- Range: $(0,\infty)$
	 - **Exponential**: $f(x)=e^x$ 
		- Domain: $\mathbb{R}$
		- Range: $(0,+\infty)$
	 - **Logarithmic**:  $f(x)=\log x$ 
		- Domain: $(0,+\infty)$
		- Range: $(-\infty,+\infty)$
- ###### Domain & range of composite functions 
	- Domain: the set of those inputs x in the domain of g for which g(x) is in the domain of f
	
	![Pasted image 20230117195048.png](/img/user/Et%20cetera/Images/Pasted%20image%2020230117195048.png)

- ###### Identifying transformations
	- no
- ###### Finding & verifying inverses
	- To find a function's inverse, switch the x + y variables and solve for y
	- Let $f(x)=\frac{x+1}{3}$ and $g(x)=3x-1$
 - When f(x) and g(x) compose each other & the simplification yields "x" as the answer, the functions are inverses 
	-  $\text{} f(g(x))=\frac{{g(x)+1}}{3}=\frac{{(3x-1)+1}}{3}=\frac{3x}{3}=\textcolor{green}{x}$	
	-  $g(f(x))=3f(x)-1=3(\frac{{x+1}}{3})-1 =x+1-1=\textcolor{green}{x}$
	
 <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Tmdrjs9xufc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- ###### !Notation, piecewise functions
	- For a piecewise graph to represent a function, **each x can only have one y** 
		- $<,> =\circ$
		- $\geq, \le =$ closed circle 
	- Endpoints are not max/min
	- When asked for the intervals via which a function is increasing/decreasing, give x values (function notation)
	- When asked for local max/minima, give y-value

![Pasted image 20230117221222.png|500](/img/user/Et%20cetera/Images/Pasted%20image%2020230117221222.png)

- ###### Asymptotes of rational functions 
	- Vertical asymptote: calculated by finding x-int of numerator
	- Horizontal asymptote - let $f(x)=\frac{{ax^n}}{{bx^m}}$
		- $m>n:\text{polynomial division → slant asymptote}$
		- $m<n: y=0$
		- $m=n: \frac{n}{m}$
#### Chapter 2 
- ###### Solving quadratics
	- ==Quadratic formula:==   $x= \frac{-b\pm\sqrt{ b^2-4ac }}{2a}$
	- ==Complete the square:== $x^2+bx+\left( \frac{b}{2} \right)^2=\left( x+\frac{b}{2} \right)$
		- TL;DR: $ax^2+bx+c=0\longrightarrow a(x+d)^2+e=0$
			- $d=\frac{b}{2a}$
			- $e=c-\frac{{b^2}}{4a}$
			
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/2ZzuZvz33X0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- ###### Polynomial & synthetic division to find roots of polynomials
	1. To find the formula of polynomial $\\\mathbf{f(x)=1x^4+3x^3+\frac{1}{2}x^2+x+20}$, first create a list of all POSSIBLE zeroes: ==rational root theorem== → $\frac{p}{q}= \frac{{\text{factor of last term}}}{\text{ factor of first term}}$
		- Possible zeroes of $f(x)=\frac{p}{q}= \frac{\pm_{1}} {\pm{1},\pm{2},\pm{4},\pm 5,\pm{10},\pm{20}}$
	2. Then plug every zero into the equation w/ synthetic division to find a zero
	3. Once you find a zero that works, take the reduced form & continue searching for more roots 
#### Chapter 8
- ###### Using geometric & arithmetic sum formulas 
	- **Arithmetic sequence**: $a_{n}=a_{1}+(n-1)d$ 
{ #dbf681}

	- **Partial arithmetic sum**: $S_{n}=\frac{n({a_{1}+a_{n}})}{2}$
	- **Geometric sequence**: $a_{n}r^{n-1}$
	- **Partial geometric sum**: $S_{n}=\frac{a_{1}({1-r^n})}{1-r}$
	- **Infinite geometric sum**: $S_{\infty}=\frac{{a_{1}}}{1-r}$
- $n \choose r$: $\frac{{n!}}{r!(n-r)!}$
- Binomial theorem: $(x+y)^n=\sum_{k=o}^{n}{n \choose k}{x^{n-k}}y^k$
![[Pasted image 20230117210305.png \| 500]]
#### Chapter 3 
- **Continuous growth**: $y=Pe^{rt}$
- **Half life**: $\frac{1}{2}=e^{kt}$
	- Example: the half-life of the radioactive element carbon-14 is 5700 years. Find the age of a sample at which 22% of carbon-14 have decay
		$0.5=	e^{kt}		\rightarrow 57000k=\ln{0.5} \rightarrow k=\frac{{\ln0.5}}{5700}\approx{-0.001216}$
		$\rightarrow.78=e^{0.00001216t}$
- **Compound interest**: $a=a_{0}\left( 1+\frac{r}{n} \right)^{nt}$
