# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno:  David Alonso Romero Medina
## Actividad \#16 - Matrices doc


---
### Ejercicio 1 – Identificación de matrices

**Enunciado:**  
Identifica el tipo de cada matriz según sus características estructurales.

**Solución:**

$$
A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

→ **Matriz identidad**, porque la diagonal principal está compuesta por unos y los demás elementos son ceros.

$$
B =
\begin{pmatrix}
3 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}
$$

→ **Matriz diagonal**, ya que solo la diagonal principal tiene valores distintos de cero.

$$
C =
\begin{pmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

→ **Matriz simétrica**, porque cumple \(C = C^T\).

$$
D =
\begin{pmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6 \\
\end{pmatrix}
$$

→ **Matriz triangular superior**, porque todos los elementos por debajo de la diagonal son ceros.

---

### Ejercicio 2 – Operaciones básicas con matrices

**Enunciado:**  
Dadas las matrices

$$
A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
\quad
B =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$

realiza las operaciones solicitadas.

a) \(A + B\)

$$ A + B =
\begin{pmatrix}
2 + 5 & -1 +2 \\
3 + (-1) & 4 + 3 \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
7 & 1 \\
2 & 7 \\
\end{pmatrix}
$$

b) \(2A - B\)


$$ 2A =
\begin{pmatrix}
4 & -2 \\
6 & 8 \\
\end{pmatrix}
\quad
$$

$$2A - B =
\begin{pmatrix}
4 - 5 & -2 - 2 \\
6 - (-1) & 8 - 3 \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
-1 & -4 \\
7 & 5 \\
\end{pmatrix}
$$

c) \(AB\)

$$
AB =
\begin{pmatrix}
(2) (5)+(-1)(-1) & (2)(2)+(-1)(3) \\
(3)(5)+(4)(-1) & (3)(2)+(4)(3) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
11 & 1 \\
11 & 18 \\
\end{pmatrix}
$$

d) \(BA\)

$$
BA =
\begin{pmatrix}
(5)(2)+(2)(3) & (5)(-1)+(2)(4) \\
(-1)(2)+(3)(3) & (-1)(-1)+(3)(4) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
16 & 3 \\
7 & 13 \\
\end{pmatrix}
$$

e) Transpuesta \(A^T\)

$$
A^T =
\begin{pmatrix}
2 & 3 \\
-1 & 4 \\
\end{pmatrix}
$$

---

### Ejercicio 3 – Multiplicación en cadena

Enunciado:  
Verifica si la propiedad asociativa se cumple comprobando si \((AB)C = A(BC)\).

$$
A =
\begin{pmatrix}
1 & 2 \\
3 & 4 \\
\end{pmatrix}
\quad
B =
\begin{pmatrix}
2 & 0 \\
1 & 3 \\
\end{pmatrix}
\quad
C =
\begin{pmatrix}
1 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

Cálculos:

1) \(AB\)

$$
AB =
\begin{pmatrix}
(1)(2)+(2)(1) & (1)(0)+(2)(3) \\
(3)(2)+(4)(1) & (3)(0)+(4)(3) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
4 & 6 \\
10 & 12 \\
\end{pmatrix}
$$

2) \((AB)C\)

$$
(AB)C =
\begin{pmatrix}
(4)(1)+(6)(0) & (4)(1)+(6)(2) \\
(10)(1)+(12)(0) & (10)(1)+(12)(2) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

3) \(BC\)

$$
BC =
\begin{pmatrix}
(2)(1)+(0)(0) & (2)(1)+(0)(2) \\
(1)(1)+(3)(0) & (1)(1)+(3)(2) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
2 & 2 \\
1 & 7 \\
\end{pmatrix}
$$

4) \(A(BC)\)

$$
A(BC) =
\begin{pmatrix}
(1)(2)+(2)(1) & (1)(2)+(2)(7) \\
(3)(2)+(4)(1) & (3)(2)+(4)(7) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

Conclusión:  
\[
(AB)C = A(BC)
\]
Sí son iguales








