# Definición
---
Implícitamente una función $f$ es continua en un número $a$ si
$$\lim\limits_{x \to a}f(x)=f(a)$$
Lo cual significa explícitamente en estas 3 reglas:
1. $f(a)$ está definida ($a$ está en el dominio de $f$).
2. $\lim\limits_{x \to a}f(x)$ existe.
3. $\lim\limits_{x \to a}f(x)=f(a)$.

![[Continuidad.png|400]]

En caso de no cumplirse ninguna se dice que la función es discontinua en $a$.

# Continuidad vista en limites laterales
---
Una función $f$ es continua por la derecha en un número $a$ si
$$\lim\limits_{x \to a^+}f(x)=f(a)$$
y $f$ es continua por la izquierda en $a$ si
$$\lim\limits_{x \to a^-}f(x)=f(a)$$

# Continuidad en un intervalo
---
Una función $f$ es continua en un intervalo si es continua en cada
número en el intervalo. (Si $f$ está definida solo en un lado de un punto final del intervalo, entienda que continua en el punto final significa continua por la derecha o continua por la izquierda.)

# Teorema
---
Si $f$ y $g$ son continuas en $a$, y $c$ es una constante, entonces las funciones siguientes son también continuas en $a$:

1. $f+g$
2. $f-g$
3. $cf$
4. $fg$
5. $\frac{f}{g}$ si $g(a)\neq 0$ 