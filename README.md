# S12-Ejercicios

# Nombre: Carlos Alfonso Llanes
# Materia: Fundamentos de Álgebra
# Mtro: Jorge Javier Pedrozo
# Fecha: 7/11/2025
# Grupo: 1C

# Álgebra Lineal — Ejercicios de Matrices (07/11/2025)

---

## Objetivo de la documentación


## Ejercicios realizados

---

# Ejercicio 1 — Clasificar matrices
### Enunciado: Analizar y justificar el **tipo de matriz** que se presenta a continuación.

---

## Identificar Matriz
 
### Matriz 1
- **Tipo:** Matriz identidad.  
- **Justificación:** *Es matriz identidad porque los elementos de la diagonal son 1 y los demás elementos son 0.*  

Matriz:  
$`\begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}`$

---

### Matriz 2
- **Tipo:** Matriz diagonal.  
- **Justificación:** *Es matriz diagonal porque los elementos de la diagonal son diferentes y los valores afuera de la diagonal son 0.*  

Matriz:  
$`\begin{bmatrix} 3 & 0 & 0 \\ 0 & -2 & 0 \\ 0 & 0 & 5 \end{bmatrix}`$

---

### Matriz 3
- **Tipo:** Matriz simétrica.  
- **Justificación:** *Es matriz simétrica porque es igual a su transpuesta.*  

Matriz:  
$`\begin{bmatrix} 2 & 1 & 4 \\ 1 & 3 & 5 \\ 4 & 5 & 6 \end{bmatrix}`$

---

### Matriz 4
- **Tipo:** Matriz triangular superior.  
- **Justificación:** *Es matriz triangular superior porque todos los elementos debajo de la diagonal son 0.*  

Matriz:  
$`\begin{bmatrix} 1 & 2 & 3 \\ 0 & 4 & 5 \\ 0 & 0 & 6 \end{bmatrix}``

---

# Ejercicio 2 — Operaciones básicas

### Enunciado: Resuelve los ejercicios que se presentan a continuación y deja documentados los procedimientos realizados.

Matrices iniciales:  

$`\quad A = \begin{bmatrix} 2 & -1 \\ 3 & 4 \end{bmatrix}`$  
$`\quad B = \begin{bmatrix} 5 & 2 \\ -1 & 3 \end{bmatrix}`$

---

## a) $`A + B`$

$`(A+B) = \begin{bmatrix} 2+5 & -1+2 \\ 3+(-1) & 4+3 \end{bmatrix}`$  
$`= \begin{bmatrix} 7 & 1 \\ 2 & 7 \end{bmatrix}`$

---

## b) $`2A - B`$

$`2A = \begin{bmatrix} 4 & -2 \\ 6 & 8 \end{bmatrix}`$  

$`2A - B = \begin{bmatrix} 4-5 & -2-2 \\ 6-(-1) & 8-3 \end{bmatrix}`$  

$`= \begin{bmatrix} -1 & -4 \\ 7 & 5 \end{bmatrix}`$

---

## c) $`AB`$

$`AB = \begin{bmatrix} 2\cdot5 + (-1)\cdot(-1) & 2\cdot2 + (-1)\cdot3 \\ 3\cdot5 + 4\cdot(-1) & 3\cdot2 + 4\cdot3 \end{bmatrix}`$  

$`= \begin{bmatrix} 11 & 1 \\ 11 & 18 \end{bmatrix}`$

---

## d) $`BA`$

$`BA = \begin{bmatrix} 5\cdot2 + 2\cdot3 & 5\cdot(-1) + 2\cdot4 \\ (-1)\cdot2 + 3\cdot3 & (-1)(-1) + 3\cdot4 \end{bmatrix}`$  

$`= \begin{bmatrix} 16 & 3 \\ 7 & 13 \end{bmatrix}`$

> **Observación:**  
$`AB \neq BA`$ → la multiplicación de matrices **no es conmutativa**.

---

## e) $`A^T`$

$`A^T = \begin{bmatrix} 2 & 3 \\ -1 & 4 \end{bmatrix}`$

---

# Ejercicio 3 — Multiplicación en cadena (Asociatividad)

Matrices:  
$`A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}`$,  
$`B = \begin{bmatrix} 2 & 0 \\ 1 & 3 \end{bmatrix}`$,  
$`C = \begin{bmatrix} 1 & 1 \\ 0 & 2 \end{bmatrix}`$

---

## Paso 1: $`AB`$

$`AB = \begin{bmatrix} 4 & 6 \\ 10 & 12 \end{bmatrix}`$

---

## Paso 2: $`(AB)C`$

$`(AB)C = \begin{bmatrix} 4 & 16 \\ 10 & 34 \end{bmatrix}`$

---

## Paso 3: $`BC`$

$`BC = \begin{bmatrix} 2 & 2 \\ 1 & 7 \end{bmatrix}`$

---

## Paso 4: $`A(BC)`$

$`A(BC) = \begin{bmatrix} 4 & 16 \\ 10 & 34 \end{bmatrix}``

---

## Conclusión

$`(AB)C = A(BC)`$

Por lo tanto, **la multiplicación de matrices sí es asociativa.**

---

# Ejercicio 4 — Determinante de matriz 3×3 (Diagonales)

### Matriz F:

```
[ 2  -1   3 ]
[ 1   1   0 ]
[ 3   2  -1 ]
```

### Diagonales principales:

[ 2(1)(-1) + (-1)(0)(3) + 3(1)(2) = 4 ]

### Diagonales secundarias:

[ 3(1)(3) + 2(0)(2) + (-1)(1)(-1) = 10 ]

### Determinante (CORREGIDO)

$`\det(F) = 4 - 10 = \mathbf{-6}`$

---

# Ejercicio 5 — Cofactores y determinante

### Matriz G:

```
[  1   0   2 ]
[ -3   1   1 ]
[  2   0   1 ]
```

---

## Expansión por la primera fila (CORREGIDA)

$`
\det(G)=
1\begin{vmatrix} 1 & 1 \\ 0 & 1 \end{vmatrix}
- 0\begin{vmatrix} -3 & 1 \\ 2 & 1 \end{vmatrix}
+ 2\begin{vmatrix} -3 & 1 \\ 2 & 0 \end{vmatrix}
`$

---

## Cálculo (CORREGIDO)

$`1(1\cdot1 - 1\cdot0) + 2((-3)(0) - 1\cdot2)`$

$`= 1(1) + 2(-2) = \mathbf{-3}`$

---

