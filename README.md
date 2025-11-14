# S12-Ejercicios

\documentclass[12pt]{article}
\usepackage{amsmath}
\usepackage{geometry}
\geometry{margin=2.5cm}

\begin{document}

\begin{center}
\Large \textbf{Carlos Alfonso Llanes} \\[4pt]
\large Fundamentos de Álgebra \\[4pt]
Mtro: Jorge Javier Pedrozo \\[4pt]
Fecha: 7/11/2025 \\[4pt]
Grupo: 1C
\end{center}

\section*{Álgebra Lineal — Determinantes, Cofactores y Geometría (07/11/2025)}

\subsection*{Objetivo}
Documentar los procedimientos realizados para el cálculo de determinantes de matrices $2\times2$ y $3\times3$, regla de Sarrus, cofactores, propiedades del determinante y su interpretación geométrica.

\section*{Ejercicio 1 — Determinantes de matrices $2\times2$}

Se usa la fórmula:
\[
\det(A)=ad-bc
\]

\subsection*{Matriz A}
\[
A=\begin{pmatrix} 5 & 2 \\ 3 & 5 \end{pmatrix}
\]

Procedimiento:
\[
\det(A)=5\cdot5 - 2\cdot3 = 25 - 6 = 19
\]

Tu resultado: $-1$ \\
Resultado correcto: $\boxed{19}$

\subsection*{Matriz B}
\[
B=\begin{pmatrix} -1 & 4 \\ 2 & -8 \end{pmatrix}
\]

Procedimiento:
\[
\det(B)=(-1)(-8) - 4(2) = 8 - 8 = 0
\]

Tu resultado: $0$ \\
Resultado correcto: $\boxed{0}$

\subsection*{Matriz C}
\[
C=\begin{pmatrix} 6 & 9 \\ 2 & 3 \end{pmatrix}
\]

Procedimiento:
\[
\det(C)=6\cdot3 - 9\cdot2 = 18 - 18 = 0
\]

Tu resultado: $0$ \\
Resultado correcto: $\boxed{0}$

\subsection*{Matriz D}
\[
D=\begin{pmatrix} 0 & 5 \\ -5 & 0 \end{pmatrix}
\]

Procedimiento:
\[
\det(D)=0\cdot0 - 5(-5) = 25
\]

Tu resultado: $25$ \\
Resultado correcto: $\boxed{25}$

\section*{Ejercicio 2 — Regla de Sarrus (Matrices $3\times3$)}

\subsection*{Matriz E}
\[
E=\begin{pmatrix}
1 & 2 & 3\\
4 & 1 & 0\\
5 & 6 & 0
\end{pmatrix}
\]

Diagonales principales:
\[
1\cdot1\cdot0 + 2\cdot0\cdot5 + 3\cdot4\cdot6 = 0+0+72 = 72
\]

Diagonales secundarias:
\[
3\cdot1\cdot5 + 1\cdot0\cdot6 + 2\cdot4\cdot0 = 15+0+0 = 15
\]

\[
\det(E)=72 - 15 = 57
\]

Tu resultado: $1$ \\
Resultado correcto: $\boxed{57}$

\subsection*{Matriz F}
\[
F=\begin{pmatrix}
2 & -1 & 3\\
1 & 1 & 0\\
3 & 2 & -1
\end{pmatrix}
\]

Diagonales principales:
\[
2\cdot1\cdot(-1) + (-1)\cdot0\cdot3 + 3\cdot1\cdot2 = -2 + 0 + 6 = 4
\]

Diagonales secundarias:
\[
3\cdot1\cdot3 + 2\cdot0\cdot2 + (-1)\cdot1\cdot(-1) = 9 + 0 + 1 = 10
\]

\[
\det(F)=4 - 10 = -6
\]

Tu resultado: $-48$ \\
Resultado correcto: $\boxed{-6}$

\section*{Ejercicio 3 — Cofactores y determinante}

\[
G=\begin{pmatrix}
1 & 0 & 2\\
-3 & 1 & 1\\
2 & 0 & 1
\end{pmatrix}
\]

Expansión por la primera fila:

\[
\det(G)=
1\begin{vmatrix}1 & 1 \\ 0 & 1\end{vmatrix}
- 0\begin{vmatrix}-3 & 1 \\ 2 & 1\end{vmatrix}
+ 2\begin{vmatrix}-3 & 1 \\ 2 & 0\end{vmatrix}
\]

\[
=1(1\cdot1 - 1\cdot0) + 2((-3)(0)-(1)(2))
\]

\[
=1(1)+2(-2)=1-4=-3
\]

Tu resultado: $-9$ \\
Resultado correcto: $\boxed{-3}$

\section*{Ejercicio 4 — Propiedad del determinante}

\[
\det(AB)=\det(A)\det(B)
\]

(Se requiere ver las matrices que proporcionó el profesor para corregir esta parte.)

Tu resultado: $-25$ y $5$ \\
Resultado correcto: \textbf{pendiente por falta de datos.}

\section*{Ejercicio 5 — Interpretación geométrica del determinante}

\subsection*{Caso a}
\[
M=\begin{pmatrix}3 & 1 \\ 2 & 4\end{pmatrix}
\]

\[
\det(M)=12 - 2 = 10
\]

Tu resultado: $10$ \\
Correcto.

\subsection*{Caso b}
\[
M=\begin{pmatrix}1 & 3 \\ 4 & 2\end{pmatrix}
\]

\[
\det(M)=2 - 12 = -10
\]

Tu resultado: $-10$ \\
Correcto.

\subsection*{Caso c — Interpretación}
El signo negativo indica orientación horaria (contraria al giro estándar).

Tu explicación: correcta.

\end{document}

