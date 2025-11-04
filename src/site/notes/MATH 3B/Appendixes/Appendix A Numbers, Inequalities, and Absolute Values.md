---
{"dg-publish":true,"permalink":"/math-3-b/appendixes/appendix-a-numbers-inequalities-and-absolute-values/"}
---

- [ ] add \dots 
# [[Wiki/Real Numbers\|Real Numbers]]
All of the above are part of the real numbers denoted by the set $\mathbb{R}$.
## [[Wiki/Integer\|Integers]]
All whole numbers, including positive numbers, negative numbers, and zero. Denoted by the set $\mathbb{Z}$
$\dots,~-3,~-2,~-1,~0,~1,~2,~3,~\dots$
## [[Rational Numbers\|Rational Numbers]]
Ratios of integers. Denoted by the set $\mathbb{Q}$
$r=\frac{m}{n}$
where:
- $r$ is any rational number
- $m$ and $n$ are integers
- $n\neq0$
examples:
- $\frac{1}{2}$
- $-\frac{3}{7}$
- $46=\frac{46}{1}$
Decimal representation is repeating:
- $\frac{1}{2}=0.5000\dots=0.5\bar{0}$
- $\frac{9}{7}=1.285714285714\dots=1.\bar{285714}$
(bar indicates the sequence of digits repeats forever)
## [[MATH 3B/Appendixes/Irrational Numbers\|Irrational Numbers]]
Can't be expressed as a ratio of integers. Denoted by the set $\mathbb{R}-\mathbb{Q}$ or $\mathbb{R}\setminus\mathbb{Q}$
examples:
- $\sqrt{2}$
- $\sqrt[3]{2}$
- $\pi$
Decimal representation is nonrepeating. $\approx$ is used when the decimal expasion is stopped at a certain placed. It reads "is approximately equal to".
- $\pi=3.141592653589793\dots$
- $\pi\approx3.14159265$
# [[MATH 3B/Appendixes/Real Number Line\|Real Number Line]]
- [ ] create tikz number line
![Pasted image 20251024173857.png](/img/user/bs/Pasted%20image%2020251024173857.png)
This is called a coordinate line, real number line, or simply real line.
We start an arbitrary referance point, called the origin. In this case it is equal to 0
The positive direction is indicated by the arrow's direction. In this case to the right.
Each positive number x is represented by the point on the line x units to the right of the origin.
Each negative number -x is represented by the point on the line x units to the left of the origin
Therefore, every real number is represented on the line.
Every point P corresponds to exactly one real number. This number associated with P is called the coordinate.
# [[Wiki/Inequalities\|Inequalities]]
From the real line, we can see that the real numbers are ordered. Lets take two numbers,  and . If $b-a$ is a positive number, we know that *a is less than b*, and can represent this using the symbols $a<b$ . Therefore, *b is greater than a*, represented as $b>a$. This means $a$ lies to the left of $b$ on the real number line.
The symbols $\leq$ and $\geq$ combine the meanings of their previous counterparts with equality. If $a\leq{b}$, *a is less than or equal to b*. It means that either $a<b$ or $a=b$.
If $a$ lies to the right of $b$ on a real number line directed to the right, $a$ is greater than $b$.
If $b$ lies to the right of $a$ on a real number line directed to the right, $a$ is less than $b$.
Examples:
- $7<7.4<7.5$
- $-3>-\pi$
- $2\leq{2}$
## Strict Inequalities
### Greater Than
If $a-b$ is a positive number, $a~\textgreater~b$. This is read as "$a$ is greater than $b$". On a real number line, 
### Less Than
If $b-a$ is a positive number, $a~\textless~b$. This is read as "$a$ is less than $b$".
## Mixed Inequalities
### Greater Than or Equal to
If $a-b$ is a positive number or 0, $a~\geq~b$. This is read as " is greater than or equal to "
### Less Than or Equal to
If $b-a$ is a positive number or 0, $a~\leq~b$. This is read as "$a$ is less than or equal to $b$"
# [[Sets\|Sets]]
A [[Wiki/set\|set]] is a collection of objects, and these objects are called the [[Element\|elements]] of the set.
For a set $S$, $a\in{S}$ means that $a$ [[bs/∈\|is an element of]] the set $S$, while $a\notin{S}$ means that $a$ is not an element of the set $S$.
For sets $S$ and $T$, $S\cup{T}$ represents their [[Union\|union]], which is the set of all elements in $S$ or $T$ (or both). $S\cap{T}$ represents their [[Intersection\|intersection]], which is the set of all elements in both $S$ and $T$
The set containing no element is called the [[Wiki/Empty set\|empty set]], and is denoted by $\emptyset$.
## [[Wiki/Roster Notation\|Roster Notation]]
Some sets can be described through roster notation, which lists their elements between braces
For example, the empty set is represented as $\{\}$.
A set of all positive integers less than 7 is: $\{1,2,3,4,5,6\}$
## Set-Builder Notation
[[Wiki/Set-builder notation\|Set-builder notation]] stats the properties that it's elements must satifsy, rather than listing all elemtns indiviaually. It contains three parts, a variable, a verticle bar, and a [[Predicate\|predicate]].
A predicate is the logical statement that tells you which elements are included.
The previous example can be rewritten as:
$\{x\mid x\text{ is an integer and }0<x<7\}$
Another method is to specify the domain in the first part before the verticle bar. This is done using the prior mentioned symbol $\in$ and the symbol for a given [[Wiki/common number set\|common number set]].
$\{x\in\mathbb{Z}\mid 0<x<7\}$
# Intervals
An [[interval\|interval]] is a specific set of real numbers. These fixed endpoints are notated $a$ and $b$.
## Open Interval
An [[open interval\|Open Interval]] does not include the endpoints. It is denoted using parathenses.
$(a,b)=\{x\mid a\textless x \textless b\}$
## Closed Interval
An [[closed interval\|Closed Interval]] does include the endpoints. It is denoted using square brackets.
$[a,b]=\{x\mid a\leq x \leq b\}$
## Infinite Interval
An [[infinite interval\|Infinite Interval]] either has endpoint $a=-\infty$ or $b=\infty$. It can be viewed as the set of all numbers greater/less than a/b.
$(-\infty,b)=\{x\mid x\textless b\}$
$(a,\infty)=\{x\mid x\textgreater a\}$
## On the real number line
![Pasted image 20251025052201.png](/img/user/bs/Pasted%20image%2020251025052201.png)
# Inequalities
```tikz
\begin{document}
	\begin{tikzpicture}[
    scale=1.5,
    >=stealth,
    open_dot/.style={circle, draw=blue, thick, fill=white, inner sep=0pt, minimum size=6pt},
    line/.style={draw=blue, line width=2pt}
]

    % CONFIGURATION for x < a
    \def\xmin{-3}
    \def\xmax{5}
    \def\endpointA{3}
    \def\labelA{a}
    
    % Draw the main number line
    \draw[<->, thick] (\xmin, 0) -- (\xmax, 0);

    % Draw the tick mark and label for 'a'
    \draw (\endpointA, 0.1) -- (\endpointA, -0.1) node[below] {$\labelA$};

    % Draw the ray (line from min to 'a' with an arrow on the left)
    \draw[line, <-] (\xmin, 0) -- (\endpointA, 0);
    
    % Draw the open circle at 'a'
    \node [open_dot] at (\endpointA, 0) {};

	\end{tikzpicture}
\end{document}
```
\begin{document}



```tikz
\begin{document}
  \begin{tikzpicture}
    % Draw the bounded number line
    \draw (0,0) -- (6,0);  % no arrows, just a line
    
    % Draw major ticks and labels for integers 0 to 6
    \foreach \x in {0,1,2,3,4,5,6} {
      \draw (\x,0.15) -- (\x,-0.15) node[below] {\x};
    }
    
    % Draw minor ticks every 0.5 using step
    \foreach \x in {0.5,1.5,...,5.5} {
      \draw (\x,0.1) -- (\x,-0.1);
    }
    
    % Optional: highlight bounds
    \node[above] at (0,0.15) {$0$};
    \node[above] at (6,0.15) {$6$};
    
    % Optional: highlight specific points
    \filldraw[red] (2.5,0) circle (2pt) node[above] {2.5};
    \filldraw[blue] (4,0) circle (2pt) node[above] {4};
  \end{tikzpicture}
\end{document}
```
![Pasted image 20251025062034.png](/img/user/bs/Pasted%20image%2020251025062034.png)
![Pasted image 20251025062046.png](/img/user/bs/Pasted%20image%2020251025062046.png)
- [ ] finish App A inequality rule

# Absolute Value
The [[Wiki/absolute value\|absolute value]] of a number $a$ is the distance from a to 0 on the real number line. It is denoted with $|a|$. Distances are always positive, meaning $|a|\geq0$ for every number $a$.
## Properties
- $|a|=a$ if $a\geq0$
- $|a|=-a$ if $a~\textless~0$