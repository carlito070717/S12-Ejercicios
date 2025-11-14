# S12-Ejercicios

# Nombre: Carlos Alfonso Llanes  
# Materia: Fundamentos de Álgebra  
# Mtro: Jorge Javier Pedrozo  
# Fecha: 7/11/2025  
# Grupo: 1C  

# Álgebra Lineal — Determinantes, Cofactores y Geometría (07/11/2025)

---

## Objetivo de la documentación
Documentar los procedimientos realizados para el cálculo de determinantes de matrices 2×2 y 3×3, aplicación de la regla de Sarrus, cofactores, propiedades del determinante y su interpretación geométrica.

---

# Ejercicio 1 — Determinantes de matrices 2×2

Se calcularon determinantes usando la fórmula:

\[
\det(A)=ad-bc
\]

---

## Matriz A
\[
A = \begin{bmatrix} 5 & 2 \\ 3 & 5 \end{bmatrix}
\]

\[
\det(A) = (5)(5) - (2)(3) = 25 - 6 = -1
\]

---

## Matriz B
\[
B = \begin{bmatrix} -1 & 4 \\ 2 & -8 \end{bmatrix}
\]

\[
\det(B) = (-1)(-8) - (4)(2) = 8 - 8 = 0
\]

---

## Matriz C
\[
C = \begin{bmatrix} 6 & 9 \\ 2 & 3 \end{bmatrix}
\]

\[
\det(C) = (6)(3) - (9)(2) = 18 - 18 = 0
\]

---

## Matriz D
\[
D = \begin{bmatrix} 0 & 5 \\ -5 & 0 \end{bmatrix}
\]

\[
\det(D) = (0)(0) - (5)(-5) = 25
\]

---

# Ejercicio 2 — Regla de Sarrus (Matrices 3×3)

La regla de Sarrus consiste en extender las dos primeras columnas y sumar las diagonales principales menos las diagonales secundarias.

---

## Matriz E
\[
E = \begin{bmatrix}
1 & 2 & 3 \\
4 & 1 & 0 \\
5 & 6 & 0
\end{bmatrix}
\]

Aplicando Sarrus:

Suma de diagonales principales:

\[
1\cdot1\cdot0 + 2\cdot0\cdot5 + 3\cdot4\cdot6 = 0 + 0 + 72 = 72
\]

Suma de diagonales secundarias:

\[
3\cdot1\cdot5 + 1\cdot0\cdot6 + 2\cdot4\cdot0 = 15 + 0 + 0 = 15
\]

\[
\det(E) = 72 - 15 = 57
\]

(En tu desarrollo aparece \(-1\), pero el cálculo correcto es \(57\).)

---

## Matriz F
\[
F = \begin{bmatrix}
2 & -1 & 3 \\
1 & 1 & 0 \\
3 & 2 & -1
\end{bmatrix}
\]

Sarrus:

Diagonales principales:

\[
2\cdot1\cdot(-1) + (-1)\cdot0\cdot3 + 3\cdot1\cdot2 = -2 + 0 + 6 = 4
\]

Diagonales secundarias:

\[
3\cdot1\cdot3 + 2\cdot0\cdot2 + (-1)\cdot1\cdot(-1) = 9 + 0 + 1 = 10
\]

\[
\det(F) = 4 - 10 = -6
\]

(En tu libreta aparece \(-48\), pero el cálculo correcto es \(-6\).)

---

# Ejercicio 3 — Cofactores y determinante de una matriz 3×3

## Matriz G

\[
G = \begin{bmatrix}
1 & 0 & 2 \\
-3 & 1 & 1 \\
2 & 0 & 1
\end{bmatrix}
\]

Expansión por la primera fila:

\[
\det(G) =
1\cdot\begin{vmatrix} 1 & 1 \\ 0 & 1 \end{vmatrix}
- 0\cdot\begin{vmatrix} -3 & 1 \\ 2 & 1 \end{vmatrix}
+ 2\cdot\begin{vmatrix} -3 & 1 \\ 2 & 0 \end{vmatrix}
\]

\[
= 1(1\cdot1 - 1\cdot0) + 2((-3)(0) - (1)(2))
\]

\[
= 1(1) + 2(-2) = 1 - 4 = -3
\]

---

# Ejercicio 4 — Propiedad del determinante

\[
\det(AB) = \det(A)\det(B)
\]

Demostrado multiplicando matrices 2×2 dadas por el profesor.

---

# Ejercicio 5 — Interpretación geométrica del determinante

Dado un par de vectores:

\[
u = \begin{bmatrix} 3 \\ 2 \end{bmatrix}, \quad
v = \begin{bmatrix} 1 \\ 4 \end{bmatrix}
\]

La matriz formada es:

\[
M = \begin{bmatrix} 3 & 1 \\ 2 & 4 \end{bmatrix}
\]

\[
\det(M) = (3)(4) - (1)(2) = 12 - 2 = 10
\]

### Interpretación:
El determinante representa el **área del paralelogramo** generado por los vectores.

---

## Caso b  
Si intercambiamos los vectores:

\[
M = \begin{bmatrix} 1 & 3 \\ 4 & 2 \end{bmatrix}
\]

\[
\det(M) = (1)(2) - (3)(4) = 2 - 12 = -10
\]

---

## Caso c — Interpretación del signo

El signo negativo indica que la orientación de los vectores es **horaria**, es decir, en el **sentido contrario al giro estándar anti–horario**.

---

