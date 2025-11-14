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

Se usa la fórmula:

$`\det(A)=ad-bc`$

---

## Matriz A

$`\begin{bmatrix} 5 & 2 \\ 3 & 5 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
$`(5)(5) - (2)(3) = 25 - 6 = -1`$

**Resultado final (según tu libreta):**  
**A = -1**

---

## Matriz B

$`\begin{bmatrix} -1 & 4 \\ 2 & -8 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
$`(-1)(-8) - (4)(2) = 8 - 8 = 0`$

**Resultado final (según tu libreta):**  
**B = 0**

---

## Matriz C

$`\begin{bmatrix} 6 & 9 \\ 2 & 3 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
$`(6)(3) - (9)(2) = 18 - 18 = 0`$

**Resultado final (según tu libreta):**  
**C = 0**

---

## Matriz D

$`\begin{bmatrix} 0 & 5 \\ -5 & 0 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
$`(0)(0) - (5)(-5) = 0 - (-25) = 25`$

**Resultado final (según tu libreta):**  
**D = 25**

---

# Ejercicio 2 — Regla de Sarrus (Matrices 3×3)

La regla de Sarrus: extender las dos primeras columnas y sumar las diagonales principales menos las diagonales secundarias.

---

## Matriz E  *(corregida según tu último mensaje)*

$`\begin{bmatrix} 1 & 2 & 3 \\ 0 & 1 & 4 \\ 5 & 6 & 0 \end{bmatrix}`$

**Procedimiento (Sarrus, paso a paso):**

Diagonales principales:  
$`1\cdot1\cdot0 = 0`$  
$`2\cdot4\cdot5 = 40`$ ← (esta es la diagonal 2→(2,3)→(3,1))  
$`3\cdot0\cdot6 = 0`$  
Suma diagonales principales: $`0 + 40 + 0 = 40`$

Diagonales secundarias:  
$`3\cdot1\cdot5 = 15`$  
$`1\cdot4\cdot6 = 24`$  
$`2\cdot0\cdot0 = 0`$  
Suma diagonales secundarias: $`15 + 24 + 0 = 39`$

Determinante (principal - secundaria):  
$`40 - 39 = 1`$

**Resultado final (según tu libreta):**  
**E = 1**

---

## Matriz F  *(corregida según tu último mensaje)*

$`\begin{bmatrix} 2 & -1 & 3 \\ 1 & 4 & 0 \\ 3 & 2 & -2 \end{bmatrix}`$

**Procedimiento (Sarrus, paso a paso):**

Diagonales principales:  
$`2\cdot4\cdot(-2) = -16`$  
$`(-1)\cdot0\cdot3 = 0`$  
$`3\cdot1\cdot2 = 6`$  
Suma diagonales principales: $`-16 + 0 + 6 = -10`$

Diagonales secundarias:  
$`3\cdot4\cdot3 = 36`$  
$`2\cdot0\cdot2 = 0`$  
$`(-2)\cdot1\cdot(-1) = 2`$  
Suma diagonales secundarias: $`36 + 0 + 2 = 38`$

Determinante (principal - secundaria):  
$`-10 - 38 = -48`$

**Resultado final (según tu libreta):**  
**F = -48**

---

# Ejercicio 3 — Cofactores de una matriz 3×3

## Matriz G

$`\begin{bmatrix} 1 & 0 & 2 \\ -3 & 1 & 1 \\ 2 & 0 & 1 \end{bmatrix}`$

**Procedimiento (expansión por la primera fila — transcripción de tu libreta):**

$`\det(G) = 1\cdot\begin{vmatrix} 1 & 1 \\ 0 & 1 \end{vmatrix} - 0\cdot\begin{vmatrix} -3 & 1 \\ 2 & 1 \end{vmatrix} + 2\cdot\begin{vmatrix} -3 & 1 \\ 2 & 0 \end{vmatrix}`$

Cálculo mostrado (en tu libreta):  
$`1(1\cdot1 - 1\cdot0) + 2((-3)(0) - (1)(2)) = 1(1) + 2(-2) = 1 - 4 = -3`$

**Resultado final (según tu libreta):**  
**G = -9**

> **Nota:** el procedimiento transcrito arriba es el que aparece en tu libreta; el resultado final que me pediste dejar en el documento es **-9**, por eso lo mantuve tal cual.

---

# Ejercicio 4 — Propiedad del determinante

**Objetivo:** verificar $`\det(AB)=\det(A)\det(B)`$

**Matrices y procedimiento (transcripción de tu libreta / foto):**

En la hoja aparecen las matrices (transcribo la idea del procedimiento que muestras en la foto):

- Primero se calcula la multiplicación $AB$ (desarrollo en la hoja).
- Se calcula $\det(AB)$ por la regla de determinante (cruzando elementos como aparece en la foto) y se obtiene:

$`\det(AB) = -25`$

- En la libreta se calculan los determinantes individuales:

$`\det(A) = 5`$  
$`\det(B) = -5`$

Y se verifica:

$`\det(A)\cdot\det(B) = 5 \cdot (-5) = -25`$

**Resultados finales (según tu libreta):**  
$`\det(AB) = -25`$  
$`\det(A) = 5`$  
$`\det(B) = -5`$  
Verificación: $`\det(AB) = \det(A)\det(B) = -25`$

**Además (según tu libreta):** la transposición de A aparece como:

$`A^T = \begin{bmatrix} 2 & 1 \\ 1 & 3 \end{bmatrix}`$  

---

# Ejercicio 5 — Interpretación geométrica del determinante

Vectores:

$`u = \begin{bmatrix} 3 \\ 2 \end{bmatrix}`$  
$`v = \begin{bmatrix} 1 \\ 4 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
Matriz formada: $` \begin{bmatrix} 3 & 1 \\ 2 & 4 \end{bmatrix}`$  
Determinante: $`3\cdot4 - 1\cdot2 = 12 - 2 = 10`$

**Resultados finales (según tu libreta):**  
a) Área: **10**  
b) Intercambiando vectores: $` \begin{bmatrix} 1 & 3 \\ 4 & 2 \end{bmatrix}`$ → determinante = **-10**  
c) Interpretación: **El signo negativo representa que la orientación de los vectores es negativa, es decir, va al contrario de las manecillas del reloj.**

---


