# Definición intuitiva de un límite
---
Suponga que $f(x)$ está definida cuando $x$ está cerca del número $a$. (Esto significa que $f$ está definida en algún intervalo abierto que contiene a $a$, excepto posiblemente en a misma.) Entonces se escribe
$$\lim\limits_{x \to a} f(x) = L$$
y se dice que  “el límite de $f(x)$, cuando $x$ tiende a $a$, es igual a $L$” si se puede hacer que los valores de $f(x)$ estén arbitrariamente cercanos a $L$ (tan cercanos a $L$ como se quiera), tomando valores de $x$ suficientemente cerca de $a$ (por ambos lados de $a$), pero no iguales a $a$.

Una notación alternativa para
$$\lim\limits_{x \to a} f(x) = L$$
es
$$f(x) \to L \quad \text{cuando} \quad x \to a$$
que suele leerse “$f(x)$ tiende a $L$ cuando $x$ tiende a $a$”.

# Definición precisa de un límite
---
Sea $f$ la función definida sobre algún intervalo abierto que contiene el número $a$, excepto posiblemente en $a$ misma. Entonces, se dice que el límite de $f(x)$ cuando $x$ tiende a $a$ es $L$, y se expresa como
$$\lim\limits_{x \to a} f(x) = L$$
si para todo $\varepsilon > 0$ existe un  $\delta > 0$ tal que
$$0<|x-a|<\delta \quad \text{de modo que} \quad|f(x)-L|<\varepsilon$$

![[Definición del precisa del límite.png|400]]

>[!question] Parafraseo
>
Básicamente en este $\lim\limits_{x \to a}f(x) = L$, se establece $\varepsilon$ el cual podría verse como un "error", la cual se usa para crear las rectas horizontales$$y=L+\varepsilon \quad \text{y} \quad y=L-\varepsilon$$ ![[DPL1.png|400]]
>
Luego se trazan las rectas perpendiculares a las  ya mencionadas, en el punto donde interceptan la gráfica las cuales nos dan dos $\delta$ distintas de las cuales tomamos la más pequeña y a partir de ese valor podemos crear las rectas verticales $$x=a-\delta \quad \text{x} \quad x=a+\delta$$![[DPL2.png|400]]
>
Por último este sería un resultado similar al anterior al ajustar $\varepsilon$, el error, a un numero más pequeño, dando un valor a $f(x)$ más ajustado.
>
![[DPL3.png|400]]
>
Explicación: https://youtu.be/pYVVPqphPS0?t=3642
# Anexos
- Documentos
	- [[CALCULO_TRASCENDENTES_TEMPRANAS_8va_Edi.pdf#page=137]]
- Videos
	- LÍMITES - Clase Completa: Explicación desde Cero | El Traductor: https://youtu.be/pYVVPqphPS0