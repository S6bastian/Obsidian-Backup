Dos funciones f y g pueden combinarse para formar funciones nuevas $f + g$, $f - g$, $fg$ y $f/g$ en forma similar a la suma, resta, multiplicación y división de números reales.

# Suma y diferencia de funciones
---
$$
(f+g)(x)=f(x)+g(x) \quad \quad
(f-g)(x)=f(x)-g(x)
$$
Si el [[#Dominio|dominio]] de $f$ es $A$ y el [[#Dominio|dominio]] de $g$ es $B$, el [[#Dominio|dominio]] de $f + g$ es la intersección $A \cap B$ porque $f(x)$ y $g(x)$ tienen que estar definidas.

# Producto y cociente de funciones
---
$$
(fg)(x)=f(x)g(x) \quad \quad
\left(\frac{f}{g} \right )(x)=\frac {f(x)}{g(x)}
$$
El [[#Dominio|dominio]] de $fg$ es $A \cap B$, pero no se puede dividir entre 0, por lo que el [[#Dominio|dominio]] de $f/g$ es $\{ x \in A \cap B \mid g(x) \neq 0 \}$.

# Composición de funciones
---
$$(f \circ g)(x)=f(g(x))$$
El [[#Dominio|dominio]] de $f \circ g$ es el conjunto de todas las $x$ en el [[#Dominio|dominio]] de $g$ tales que $g(x)$ está en el [[#Dominio|dominio]] de $f$. En otras palabras, $(f \circ g)$(x) está definida siempre que $g(x)$ y $f(g(x))$ estén definidas.

![[Composición de funciones.png|300]]
*La máquina $f \circ g$ se compone de la máquina g (primero) y luego de la máquina $f$.*
