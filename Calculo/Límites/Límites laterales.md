>[!tip] Importante
$$\lim\limits_{x\to a}f(x) = L \quad \leftrightarrow \quad \lim\limits_{x\to a^-}f(x) = L = \lim\limits_{x\to a^+}f(x)$$
Se dice el [[Límites|límite]] existe, si y solo si, ambos [[Límites laterales|límites laterales]] existen y son iguales.
>> [!question] Parafraseando
Si los límites por la izquierda $\lim\limits_{x \to a^-}f(x)$ y por la derecha $\lim\limits_{x \to a^+}f(x)$ son diferentes, se llega a la conclusión de que $\lim\limits_{x \to a}f(x)$ no existe.
# Definición intuitiva
---
Cuando se escribe
$$\lim\limits_{x \to a^-} f(x) = L$$
se expresa que el límite por la izquierda de $f(x)$ cuando $x$ se aproxima a $a$ es igual a $L$ si se puede hacer que los valores de $f(x)$ se acerquen arbitrariamente a $L$, tanto como se quiera, tomando $x$ suficientemente cercanos a $a$, pero menores que $a$.

![[Límite por la izquierda.png|400]]

Y
$$\lim\limits_{x \to a^+} f(x) = L$$
el límite por la derecha de $f(x)$ cuando $x$ tiende a $a$ es igual a $L$.

![[Límite por la derecha.png|400]]

# Definición precisa
---
Esta es la definición de los límites laterales usando la [[Límites#Definición precisa de un límite|definición precisa del límite]].
## Límite por la izquierda
---
$$\lim\limits_{x \to a^-}f(x)=L$$
Si para todo número $\varepsilon > 0$ existe un número $\delta > 0$ tal que
$$\text{si} \quad a - \delta < x < a \quad \text{entonces} \quad |f(x) - L | < \varepsilon$$
## Límite por la derecha
---
$$\lim\limits_{x \to a^+}f(x)=L$$
Si para todo número $\varepsilon > 0$ existe un número $\delta > 0$ tal que
$$\text{si} \quad a < x < a + \delta  \quad \text{entonces} \quad |f(x) - L | < \varepsilon$$
