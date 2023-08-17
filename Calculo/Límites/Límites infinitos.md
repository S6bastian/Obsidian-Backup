# Definición intuitiva
---
Sea $f$ una función definida por ambos lados de $a$, excepto posiblemente en la misma a. Entonces
$$\lim\limits_{x \to a} f(x) = \infty$$
significa que los valores de $f(x)$ pueden hacerse arbitrariamente grandes (tan grandes como se quiera), tomando $x$ suficientemente cerca de $a$, pero no igual a $a$.

![[Límites infinitos positivos.png|400]]

o
$$\lim\limits_{x \to a} f(x) = -\infty$$
significa que los valores de $f(x)$ pueden ser negativos arbitrariamente grandes, tomando $x$ suficientemente cerca de $a$, pero no igual a $a$.

![[Límites infinitos negativos.png|400]]

# Definición precisa
---
## Infinito positivo
---
Sea $f$ una función definida sobre algún intervalo abierto que contiene al número $a$, excepto posiblemente en $a$ misma. Entonces
$$\lim\limits_{x \to a} f(x) = \infty$$
significa que para todo número positivo $M$ existe un número positivo $\delta$ tal que
$$\text{si} \quad 0<|x-a|<\delta \quad \text{entonces} \quad f(x)>M$$

![[DPIP.png|400]]

## Infinito negativo
---
Sea $f$ una función definida sobre algún intervalo abierto que contiene al número $a$, excepto posiblemente en $a$ misma. Entonces
$$\lim\limits_{x \to a} f(x) = -\infty$$
significa que para todo número negativo $N$ existe un número $\delta$ positivo tal que
$$\text{si} \quad 0<|x-a|<\delta \quad \text{entonces} \quad f(x)<N$$

![[DPIN.png|400]]
