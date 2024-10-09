[[Fórmulas termodinámicas]]
[[Abstracción y Renderización]]
[[Introducción al patrón]]

El patrón bien puede pensarse como el portador de una especie de "energía interna" del modelo, conseguida a base del trabajo consistente en realizar cada una de las múltiples determinaciones en cada uno de los nodos que conforman el patrón. Así, la energía interna del patrón puede expresarse como U = sumWi, donde Wi es el trabajo realizado en cada determinación particular, y la energía interna, U, es el resultado de la sumatoria (no cuantitativa) de cada trabajo respectivo. Ahora bien, a qué se está llamando trabajo específicamente? 
Pensado el caso más simple posible, cuando un resultado es obtenido por dos métodos, la robustez ganada en este trabajo de determinación depende de qué tan independientes sean estos medios el uno del otro, y a la vez de la precisión del resultado, es decir cuánto confluyó el resultado de ambos métodos. Esto puede ser expresado con la fórmula **W = P dV**, donde **dV** es la variación entre los métodos, que es una medida de su mutua independencia, y **P** es la precisión del resultado obtenido.
De esto se sigue que a cada instancia de determinación el trabajo contribuye a la energía interna del patrón, y la ganancia en esta energía interna es expresada como entropía (**H**), de acuerdo a la siguiente fórmula: **dH = U + P dV**. Es trivial que, en ausencia de una nueva determinación, la entalpía se identifica con la energía interna del patrón.

