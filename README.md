# S12-Ejercicios

# Álgebra Lineal — Determinantes, Cofactores y Geometría  
**Fecha:** 07/11/2025  
**Materia:** Fundamentos de Álgebra  
**Alumno:** Carlos Alfonso Llanes  
**Grupo:** 1C  
**Profesor:** Jorge Javier Pedrozo  

---

## Objetivo
Documentar el proceso para calcular determinantes 2×2 y 3×3, regla de Sarrus, cofactores, propiedades y su interpretación geométrica.

---

# Ejercicio 1 — Determinantes 2×2

La fórmula general es:

\[
\det(A)=ad - bc
\]

---

### Matriz A

\[
A = \begin{bmatrix} 5 & 2 \\ 3 & 5 \end{bmatrix}
\]

\[
\det(A) = (5)(5) - (2)(3) = 25 - 6 = \mathbf{-1}
\]

---

### Matriz B

\[
B = \begin{bmatrix} -1 & 4 \\ 2 & -8 \end{bmatrix}
\]

\[
\det(B) = (-1)(-8) - (4)(2) = 8 - 8 = \mathbf{0}
\]

---

### Matriz C

\[
C = \begin{bmatrix} 6 & 9 \\ 2 & 3 \end{bmatrix}
\]

\[
\det(C) = (6)(3) - (9)(2) = 18 - 18 = \mathbf{0}
\]

---

### Matriz D

\[
D = \begin{bmatrix} 0 & 5 \\ -5 & 0 \end{bmatrix}
\]

\[
\det(D) = (0)(0) - (5)(-5) = \mathbf{25}
\]

---

# Ejercicio 2 — Regla de Sarrus (Matrices 3×3)

---

### Matriz E

\[
E = \begin{bmatrix}
1 & 2 & 3 \\
4 & 1 & 0 \\
5 & 6 & 0
\end{bmatrix}
\]

Sarrus:

Diagonales principales:

\[
1\cdot1\cdot0 + 2\cdot0\cdot5 + 3\cdot4\cdot6 = 72
\]

Diagonales secundarias:

\[
3\cdot1\cdot5 + 1\cdot0\cdot6 + 2\cdot4\cdot0 = 15
\]

\[
\det(E) = 72 - 15 = \mathbf{57}
\]

---

### Matriz F

\[
F = \begin{bmatrix}
2 & -1 & 3 \\
1 & 1 & 0 \\
3 & 2 & -1
\end{bmatrix}
\]

Diagonales principales:

\[
2(1)(-1) + (-1)(0)(3) + 3(1)(2) = 4
\]

Diagonales secundarias:

\[
3(1)(3) + 2(0)(2) + (-1)(1)(-1) = 10
\]

\[
\det(F) = 4 - 10 = \mathbf{-6}
\]

---

# Ejercicio 3 — Cofactores y determinante de una matriz 3×3

Matriz:

\[
G =
\begin{bmatrix}
1 & 0 & 2 \\
-3 & 1 & 1 \\
2 & 0 & 1
\end{bmatrix}
\]

Expansión por la primera fila:

\[
\det(G)=
1\begin{vmatrix} 1 & 1 \\ 0 & 1 \end{vmatrix}
- 0\begin{vmatrix} -3 & 1 \\ 2 & 1 \end{vmatrix}
+ 2\begin{vmatrix} -3 & 1 \\ 2 & 0 \end{vmatrix}
\]

Cálculo:

\[
1(1\cdot1 - 1\cdot0) + 2((-3)(0) - (1)(2))
\]

\[
= 1(1) + 2(-2) = \mathbf{-3}
\]

---

# Ejercicio 4 — Propiedad del determinante

\[
\det(AB)=\det(A)\det(B)
\]

Se verificó multiplicando matrices 2×2 dadas por el profesor.

---

# Ejercicio 5 — Interpretación geométrica

Vectores:

\[
u = \begin{bmatrix} 3 \\ 2 \end{bmatrix}, \quad
v = \begin{bmatrix} 1 \\ 4 \end{bmatrix}
\]

Matriz formada:

\[
M = \begin{bmatrix} 3 & 1 \\ 2 & 4 \end{bmatrix}
\]

\[
\det(M)=12-2= \mathbf{10}
\]

El determinante representa el **área del paralelogramo** generado por los vectores.

---

### Caso b — Vectores intercambiados

\[
M = \begin{bmatrix} 1 & 3 \\ 4 & 2 \end{bmatrix}
\]

\[
\det(M)=2 - 12 = \mathbf{-10}
\]

### Caso c — Signo

El signo negativo indica orientación **horaria**, en sentido contrario al giro anti–horario estándar.

---
