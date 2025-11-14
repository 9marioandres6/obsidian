#soporte #resumen #desarrollo 


...Aquel lector que no esté introducido a la teoría termodinámica podrá seguir el texto sin mayores problemas, aunque claramente se perderá el tono lúdico que irá implícito en la definición de cada parámetro en su correspondencia con los de esta teoría.

### Robustez del nodo (W)

Del capítulo 1A ha quedado claro que el análisis de robustez *a la* Wimsatt es una versión tal vez más metódica del ya conocido principio de determinación múltiple.

* Principio de determinación múltiple -> robustez del nodo **W**
* Variación o diversidad entre los distintos métodos de determinación. Considerando sólo dos métodos, es la variación entre ellos; considerando una estructura o un sistema, es la diversidad de métodos de ésta: **V**
* Precisión del resultado, que es una medida de la coincidencia entre los distintos métodos de determinación: **P** 
* Robustez del nodo a precisión constante:
$$
W ≡ ΣPΔV
$$

>[!Terminología]
>* Isométrico: a precisión constante
>* Isovárico: a variación o diversidad constante

En el esfuerzo por realizar un paralelo con la teoría termodinámica, conviene advertir que la robustez no es equivalente a la energía interna del sistema, sino al contrario. Un sistema más robusto debería interpretarse termodinámicamente como un sistema más frío, de menor temperatura, aunque rigurosamente hablando estos saltos entre ámbitos teóricos no son del todo lícitos.
En esta línea, W > 0 por un aumento en la cantidad de determinaciones V, implica un aumento en la robustez. Si se quiere mantener un paralelo con la teoría termodinámica, un aumento en el volumen V implica un trabajo realizado hacia el entorno y por lo tanto una pérdida de energía por parte del sistema. Esto es compatible con la propuesta actual siempre que no se entienda W como el trabajo de múltiple determinación realizado por el científico sobre la estructura.

### Densidad de red (T)

Es el grado de conexión entre nodos del patrón, una medida de su reticulación, dada una cantidad n de nodos. Es proporcional al producto PV, e inversamente proporcional a la cantidad de nodos del patrón.
$$
T ≡ PV / n
$$
$$
nΔT ≡ PΔV
$$
### Reticulación (Q)

Es una medida de la relación entre la robustez del patrón y la del sistema tecnológico en el que se encuentra. En general cuando el ambiente tiene una mayor densidad T de red respecto del patrón, éste acaba aumentando su densidad en detrimento de la de aquél (siguiendo el principio 0 de la termodinámica). A la inversa, si el patrón se encuentra en un ambiente poco denso, tenderá espontáneamente a disminuir su densidad hasta quedar equilibrado con la del ambiente.
Esto permitiría sugerir algo que en principio es poco intuitivo: que la estabilidad del patrón no depende de la precisión P ni de la diversidad V de sus nodos, sino de su nivel de reticulación en relación al ambiente en que se encuentra.
Cómo hace un aparato tecnológico, dada su alta densidad de red, para no desintegrarse cuando sale del laboratorio? Es recubierto de un aislante: la carcasa.
La principal diferencia con T es que T es una función de estado, mientras que Q es función del proceso, lo cual significa que su valor depende de la trayectoria o el camino específico que toma un sistema para pasar de un estado inicial a un estado final, en lugar de depender solo de esos estados.
Otra diferencia importante es que Q es un indicador directo de robustez entre el patrón y el ambiente, mientras que T es una medida indirecta de la robustez del patrón. Todas estas relaciones son relativamente intuitivas si se las comprende en su paralelo con los equivalentes termodinámicos respectivos.

### Solidez estructural (U)

Es la sumatoria de la robustez de cada uno de los nodos n de la estructura. 
$$
ΔU ≡ ΣW
$$
A V constante ΔU = Q, lo cual indica que el incremento en la precisión del patrón no ocurre puntualmente nodo por nodo, sino que (ante un cambio de tecnología, por ejemplo), ocurre aproximadamente en simultáneo en toda la red.

>[!Aclaración]
>En la comparación con el primer principio de la termodinámica, ΔU = Q - W, considérese que en termodinámica W se considera positivo si el sistema realiza un trabajo hacia el entorno (V<sub>2</sub> mahor que V<sub>1</sub>). Por eso para aumentar la energía interna U, el trabajo W debe decrecer. Aquí, la robustez del sistema aumenta conforme aumenta la robustez de cualquiera de sus nodos.

### Robustez estructural (H)
* Indica cómo se incrementa la robustez del sistema ante el incremento en la robustez de un nodo. Esta fórmula es equivalente al primer principio de la termodinámica.

$$
H ≡ U + W
$$
$$
ΔH ≡ ΣPΔV
$$
Es intuitivo que a P constante ΔH = Q.

### Sensibilidad (S)

> [!Niveles de análisis]
> * Nodal: hace referencia a un nodo individual
> * Estructural: incluye los nodos **m** de un patrón
> * Sistémico: incluye la red de **n** patrones

* La robustez del nodo es siempre menor que la de los elementos del patrón:
$$
U/n > R
$$
* Sensibilidad estructural es una medida de la diferencia entre la robustez del nodo y la de los demás elementos del patrón:
$$
S ≡ U/n - R
$$
* Conforme aumenta la robustez R, la sensibilidad S va disminuyendo. Se sigue que a cada instancia de aumento de robustez, ΔS tendrá un valor negativo, lo cual indica una disminución de la sensibilidad de la estructura.
### Encuadre tecnológico (E)

* Es una medida de la robustez del área en la que se inserta el patrón.
$$
E≡-TS
$$
$$
ΔE≡-TΔS
$$
### Distintos niveles en que se analiza el incremento en la robustez:

| Nivel                            | Nombre               | Equivalente termodinámico | Símbolo |
| :------------------------------- | :------------------- | :------------------------ | :-----: |
| El resultado                     | Robustez del nodo    | Trabajo                   |    W    |
| El patrón                        | Solidez estructural  | Energía interna           |    U    |
| El patrón más un nuevo resultado | Robustez estructural | Entalpía                  |    H    |
| El ambiente                      | Encuadre tecnológico | --                        |    E    |
| El sistema incluido el patrón    | Robustez sistémica   | Energía libre de Gibbs    |    G    |

* Robustez sistémica. Cuando se agrega un nuevo método sin modificar la precisión de los elementos de la estructura o el sistema:
$$
ΔG ≡ ΔH + ΔE
$$
$$
ΔG ≡ ΔH - TΔS
$$
### Potencial robustecedor y potencial solidificante

En un proceso isométrico (a P constante), el potencial robustecedor C<sub>p</sub> indica cuánto se modifica la robustez de la estructura cuando aumenta la cantidad de interconexiones, que es una medida del producto nΔT.
$$
ΔH ≡ nC_{p} ΔT
$$
$$
C_{p} ≡ ΔH / nΔT
$$

En un proceso homeostático (a V constante), el potencial solidificante C<sub>v</sub> indica cuánto se modifica la solidez del sistema ante un aumento en la cantidad de interconexiones.
$$
ΔU ≡ nC_{v} ΔT
$$
$$
C_{v} ≡ ΔU / nΔT
$$

El índice de madurez γ indica la relación entre ambos potenciales. Se puede intuir que γ será siempre menor a 1, ya que siempre la robustez tiene más carrera para ser incrementada por un aumento en la reticulación que la solidez del entorno, que ya se encuentra en estado de mayor madurez. Por lo mismo, γ más cercano a 1 indica que la estructura es más madura y cada nueva determinación no verá gran diferencia entre ΔH y ΔU.

$$
	γ ≡ Cv/​Cp​​
$$
### Ciclo de Carnot-Popper


> [!Definiciones]
> * Proceso Tecnostático (isotérmico): T constante
> * Proceso Homeostático (adiabático): W = ΔU

##### 1. Expansión isométrica

* Se agrega un nuevo método aumentando V sin modificar la precisión. Partiendo de la fórmula de densidad: T = PV/n, y considerando la robustez del nodo W = ΣPΔV, se puede unificar ambas ecuaciones eliminando P:
$$
W ≡ Σ(nT_{H}/V)ΔV
$$
$$
≡nT_{H}​∫1/​​V​dV
$$
$$
≡nT_{H}ln(V_{2}/V_{1})
$$
##### 2. Expansión homeostática
* De la fórmula de densidad T = PV/n, se sigue que ante un cambio de V habrá un cambio de T:
$$
PΔV = nΔT
$$
* Tomando ahora la fórmula de robustez W = ΣPΔV y sustituyendo, queda:
$$
W ≡ nΔT
$$

$$
ΔU ≡ nC_{V}​(T_{C}−T_{H}​)
$$



