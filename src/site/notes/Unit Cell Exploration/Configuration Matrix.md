---
{"dg-publish":true,"permalink":"/unit-cell-exploration/configuration-matrix/"}
---

A [[Unit Cell Exploration/Matrix\|matrix]] in which the [[Unit Cell Exploration/Matrix#row\|rows]] and [[Unit Cell Exploration/Matrix#columns\|columns]] correspond to elements of a [[Unit Cell Exploration/Polyhedron\|polyhedron]] - the [[Unit Cell Exploration/Vertex\|vertices]], [[Unit Cell Exploration/Edge\|edges]], and [[Unit Cell Exploration/Face\|faces]]. It describes the [[Unit Cell Exploration/Incidence Relations\|incidence relations]] between these elements, meaning how they are connected.
With these 3 element types, a $3\times 3$ matrix is formed. Both the rows and columns are ordered as vertices (V), Edges (E) then faces (F).
The rows represent the element being described, while the corresponding columns represent the element being counted. Each entry in the matrix represents how many of the column's elements are incident to each row’s element.
The [[Unit Cell Exploration/Diagonal Entry\|diagonal entries]] represent the total number of each element in the polyhedron. The [[Unit Cell Exploration/Off-Diagonal Entry\|off-diagonal entries]] represent the incident counts.
$$
\begin{bmatrix}
\#V & \text{edges/vertex} & \text{faces/vertex} \\
\text{vertices/edge} & \#E & \text{faces/edge} \\
\text{vertices/face} & \text{edges/face} & \#F
\end{bmatrix}
$$
$$
\begin{array}{c|ccc}
 & \text{Vertices (V)} & \text{Edges (E)} & \text{Faces (F)} \\ \hline
\text{Vertices (V)} & \#V & \text{edges/vertex} & \text{faces/vertex} \\
\text{Edges (E)}    & \text{vertices/edge} & \#E & \text{faces/edge} \\
\text{Faces (F)}    & \text{vertices/face} & \text{edges/face} & \#F \\
\end{array}
$$