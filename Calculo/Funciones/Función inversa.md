## Definición
---
**[[Funciones]] inversas**, en el sentido más amplio, son funciones que hacen lo "contrario" de cada una. Se denota por $f^{-1}$ y se lee “$f$ inversa”.

![[Inversa.png|300]]

## Condición
---
Sea $f$ una [[Función inyectiva|función inyectiva]] con dominio $A$ y rango $B$. Entonces, la función inversa $f^{-1}$ tiene dominio $B$ y rango $A$ y está definida por 
$$f^{-1}(y) = x \Leftrightarrow f(x) = y$$
para cualquier $y$ en $B$.

Por lo tanto:
$$\begin{array}{rl}
\text{dominio de} f^{-1} &=& \text{rango de $f$}  \\ 
\text{rango de} f^{-1} &=& \text{dominio de $f$}
\end{array}$$
![[Inversa.jpg|400]]

## Cómo encontrar la función inversa de una función $f$ [[Función inyectiva|inyectiva]]
---
1. Escribir $y = f(x)$.
2. Resolver esta ecuación para $x$ en términos de $y$ (si es posible).
3. Para expresar $f^{-1}$ en función de $x$, intercambiar $x$ por $y$. La ecuación resultante es $y = f^{-1}(x)$.

## Ecuaciones de cancelación
---
$$\begin{array}{}
f^{-1} (f (x)) = x & \text{para todo $x$ en $A$} \\
f (f^{-1} (x)) = x & \text{para todo $x$ en $B$}
\end{array}$$
![[Cancelación.png]]

## Advertencia
---
No cometa el error de pensar en $-1$ en $f^{-1}$ como un exponente. Es decir,
$$f^{-1}(x) \quad \text{no signifca} \quad \frac{1}{f(x)}$$
Sin embargo, la función recíproca, $1/f(x)$, podría escribirse como $[f(x)]^{-1}$.




