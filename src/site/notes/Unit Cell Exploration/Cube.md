---
{"dg-publish":true,"permalink":"/unit-cell-exploration/cube/"}
---

```tikz
\begin{document}
\begin{tikzpicture}[scale=2]
\draw[gray, thick] (0,0,0) -- (1,0,0) -- (1,1,0) -- (0,1,0) -- cycle;
\draw[gray, thick] (0,0,1) -- (1,0,1) -- (1,1,1) -- (0,1,1) -- cycle;
\draw[gray, thick] (0,0,0) -- (0,0,1);
\draw[gray, thick] (1,0,0) -- (1,0,1);
\draw[gray, thick] (1,1,0) -- (1,1,1);
\draw[gray, thick] (0,1,0) -- (0,1,1);
\end{tikzpicture}
\end{document}
```
A cube is a [[Unit Cell Exploration/Polyhedron\|polyhedron]] with six sides ([[Unit Cell Exploration/Face\|faces]]. It is also a [[[Platonic Solid\|platonic solid]].
# Properties
[[Unit Cell Exploration/Vertex\|Vertices]]: 8
[[Unit Cell Exploration/Edge\|Edges]]: 12
[[Unit Cell Exploration/Face\|Faces]]: 6
[[Unit Cell Exploration/Schläfli Symbol\|Schläfli symbol]]: $\{4, 3\}$
# [[Unit Cell Exploration/Configuration Matrix\|Configuration Matrix]]
$$
\mathbf{A} = 
\begin{bmatrix}  
8 & 3 & 3 \\  
2 & 12 & 2 \\  
4 & 4 & 6 \\ 
\end{bmatrix}
$$