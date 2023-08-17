# Definición intuitiva
---
## Infinito positivo
---
Sea $f$ una función definida en algún intervalo $(a,\infty)$. Entonces
$$\lim\limits_{x \to \infty}f(x)=L$$
significa que los valores de $f(x)$ se pueden aproximar arbitrariamente a $L$ tanto como se quiera, eligiendo a $x$ suficientemente grande.

## Infinito negativo
---
Sea $f$ una función definida en algún intervalo $(-\infty,a)$. Entonces
$$\lim\limits_{x \to -\infty}f(x)=L$$
significa que los valores de $f(x)$ se pueden aproximar arbitrariamente a $L$ tanto como se quiera, eligiendo a $x$ suficientemente negativa.

# Definición precisa
---
## Infinito positivo
---
Sea $f$ una función definida sobre algún intervalo $(a,\infty)$. Entonces
$$\lim\limits_{x \to \infty}f(x)=L$$
significa que para toda $\varepsilon > 0$ existe un correspondiente número $N$ tal que
$$\text{si} \quad x>N \quad \text{entonces} \quad |f(x)-L|<\varepsilon$$
![[Infinito positivo.png]]

## Infinito negativo
---
Sea $f$ una función definida sobre algún intervalo $(-\infty,a)$. Entonces
$$\lim\limits_{x \to \infty}f(x)=L$$
significa que para toda $\varepsilon > 0$ existe un correspondiente número $N$ tal que
$$\text{si} \quad x<N \quad \text{entonces} \quad |f(x)-L|<\varepsilon$$
![[Infinito negativo.png]]

# Teorema
---
Si $r>0$ es un número racional, entonces
$$\lim\limits_{x \to \infty} \frac{1}{x^r}=0$$
Si $r > 0$ es un número racional tal que $x^r$ está definida para toda $x$, entonces
$$\lim\limits_{x \to -\infty} \frac{1}{x^r}=0$$
## Ejemplo

![[Ejemplo.png|500]]

# Definición de un límite infinito al infinito
---
Sea f una función definida sobre algún intervalo $(a,\infty)$. Entonces
$$\lim\limits_{x \to \infty}f(x)=\infty$$
significa que para todo número positivo $M$ existe un correspondiente número positivo $N$ tal que
$$\text{si} \quad x>N \quad \text{entonces} \quad f(x)>M$$
