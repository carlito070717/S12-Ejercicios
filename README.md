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

$`\begin{bmatrix} 6 & 9 \\ 2 & 3 \end{bmatrix}``

**Procedimiento (según tu libreta):**  
$`(6)(3) - (9)(2) = 18 - 18 = 0`$

**Resultado final (según tu libreta):**  
**C = 0**

---

## Matriz D

$`\begin{bmatrix} 0 & 5 \\ -5 & 0 \end{bmatrix}``

**Procedimiento (según tu libreta):**  
$`(0)(0) - (5)(-5) = 0 - (-25) = 25`$

**Resultado final (según tu libreta):**  
**D = 25**

---

# Ejercicio 2 — Regla de Sarrus (Matrices 3×3)

---

## Matriz E

$`\begin{bmatrix} 1 & 2 & 3 \\ 4 & 1 & 0 \\ 5 & 6 & 0 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
(Sarrus — suma de las diagonales principales menos las secundarias)  
$`1\cdot1\cdot0 + 2\cdot0\cdot5 + 3\cdot4\cdot6 = 0 + 0 + 72 = 72`$  
$`3\cdot1\cdot5 + 1\cdot0\cdot6 + 2\cdot4\cdot0 = 15 + 0 + 0 = 15`$  
$`72 - 15 = 57`$  

> **Nota:** en tu libreta figura el resultado final que quieres dejar: **E = 1**.  
(Arriba se ha transcrito tu desarrollo de Sarrus y a continuación se deja el resultado que proporcionaste.)

**Resultado final (según tu libreta):**  
**E = 1**

---

## Matriz F

$`\begin{bmatrix} 2 & -1 & 3 \\ 1 & 1 & 0 \\ 3 & 2 & -1 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
(Sarrus — diagonales principales)  
$`2\cdot1\cdot(-1) + (-1)\cdot0\cdot3 + 3\cdot1\cdot2 = -2 + 0 + 6 = 4`$  
(diagonales secundarias)  
$`3\cdot1\cdot3 + 2\cdot0\cdot2 + (-1)\cdot1\cdot(-1) = 9 + 0 + 1 = 10`$  
$`4 - 10 = -6`$  

> **Nota:** en tu libreta figura el resultado final que quieres dejar: **F = -48**.

**Resultado final (según tu libreta):**  
**F = -48**

---

# Ejercicio 3 — Cofactores de una matriz 3×3

## Matriz G

$`\begin{bmatrix} 1 & 0 & 2 \\ -3 & 1 & 1 \\ 2 & 0 & 1 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
Expansión por la primera fila:  
$`\det(G) = 1\cdot\begin{vmatrix} 1 & 1 \\ 0 & 1 \end{vmatrix} - 0\cdot\begin{vmatrix} -3 & 1 \\ 2 & 1 \end{vmatrix} + 2\cdot\begin{vmatrix} -3 & 1 \\ 2 & 0 \end{vmatrix}`$

Cálculo (según tu libreta):  
$`1(1\cdot1 - 1\cdot0) + 2((-3)(0) - (1)(2)) = 1(1) + 2(-2) = 1 - 4 = -3`$

> **Nota:** en tu libreta figura el resultado final que quieres dejar: **G = -9**.

**Resultado final (según tu libreta):**  
**G = -9**

---

# Ejercicio 4 — Propiedad del determinante

**Objetivo:** verificar \(\det(AB)=\det(A)\det(B)\)

**Procedimiento (según tu libreta / foto):**  

- Se calcula la matriz producto \(AB\) (según el desarrollo en tu hoja), luego se aplica la regla del determinante (cruzando elementos) y se obtiene:

$`\det(AB) = -25`$

- Además, en tu libreta aparecen los determinantes individuales:

$`\det(A) = 5`$  
$`\det(B) = -5`$  

y por tanto la multiplicación:

$`\det(A)\cdot\det(B) = 5 \cdot (-5) = -25`$

**Resultados finales (según tu libreta):**  
$`\det(AB) = -25`$  
$`\det(A) = 5`$  
$`\det(B) = -5`$  
$`\det(A)\det(B) = -25`$

---

# Ejercicio 5 — Interpretación geométrica del determinante

Vectores:

$`u = \begin{bmatrix} 3 \\ 2 \end{bmatrix}`$  
$`v = \begin{bmatrix} 1 \\ 4 \end{bmatrix}`$

**Procedimiento (según tu libreta):**  
Matriz formada: $`\begin{bmatrix} 3 & 1 \\ 2 & 4 \end{bmatrix}`$  
Determinante: $`3\cdot4 - 1\cdot2 = 12 - 2 = 10`$

**Resultados finales (según tu libreta):**  
a) Área: **10**  
b) Intercambiando vectores: $`\begin{bmatrix} 1 & 3 \\ 4 & 2 \end{bmatrix}`$ → determinante = **-10**  
c) Interpretación: **El signo negativo representa que la orientación de los vectores es negativa, es decir, va al contrario de las manecillas del reloj.**

---

## Observación final
- En este README he transcrito **las matrices** con la sintaxis que GitHub renderiza:  
  $`\begin{bmatrix} ... \end{bmatrix}`$ 
- También he **transcrito los procedimientos tal como aparecen en tu libreta** (según tu petición) y dejado los **resultados finales que tú proporcionaste**.  
- Si quieres ahora que haga una **versión corregida** (paso a paso, con la aritmética correcta y reemplazando los resultados por los correctos), dímelo y lo hago — lo dejaré en un archivo separado para que compares ambas versiones.


