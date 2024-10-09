[[Monomorfismo asintótico]]

En la lógica difusa, las proposiciones no solo son verdaderas o falsas, sino que pueden tener valores de verdad que oscilan entre 0 (totalmente falso) y 1 (totalmente verdadero). Para una entidad que existe "parcialmente" y cuya verdad también es "parcial", podemos usar un valor de verdad asociado a la existencia de dicha entidad.

Supongamos que quieres expresar que una entidad **A** existe en un grado **μ(A)** (donde **μ(A)** es un número entre 0 y 1). Entonces:

- **μ(A) = 1** significa que **A** existe completamente (100%).
- **μ(A) = 0** significa que **A** no existe en absoluto.
- **0 < μ(A) < 1** significa que **A** existe parcialmente.

Podrías escribir algo así:

- **Existencia Parcial:**
    - ∃μx(A(x))\exists_{μ} x (A(x))∃μ​x(A(x)), donde **μ** indica el grado de existencia. Si **μ(A) = 0.5**, entonces la entidad **A** existe parcialmente al 50%.

De manera similar, la verdad de una proposición sobre la entidad **A(x)** también puede tener un grado de verdad parcial:

- **Verdad Parcial:**
    - μ(T(A(x)))=vμ(T(A(x))) = vμ(T(A(x)))=v, donde **v** es un valor entre 0 y 1 que representa el grado de verdad de **A(x)**.