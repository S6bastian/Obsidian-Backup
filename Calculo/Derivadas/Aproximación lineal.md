# Definición
---
La aproximación lineal es un método para estimar el valor de una función en un punto cercano a otro punto conocido en la función. Se basa en la idea de que, en pequeñas distancias, muchas funciones pueden aproximarse por una recta (una línea recta).

La idea es que puede resultar fácil calcular un valor $f(a)$ de una función, pero difícil (o aun imposible) calcular valores cercanos de $f$. Por tanto, se recurre a los valores calculados fácilmente de la función lineal $L$ cuya gráfica es la recta tangente de $f$ en $(a, f(a))$.

![[Aproximación lineal.png|400]]

En otras palabras, se utiliza la recta tangente en $(a, f(a))$ como una aproximación a la curva $y = f(x)$ cuando $x$ está cerca de $a$.
$$f(x) \approx f(a)+f'(a)(x-a)$$
se conoce con el nombre de **aproximación lineal** o **aproximación de la recta tangente** de $f$ en $a$. A la función lineal cuya gráfica es esta recta tangente, es decir
$$L(x)=f(a)+f'(a)(x-a)$$
se le llama **linealización** de $f$ en $a$.