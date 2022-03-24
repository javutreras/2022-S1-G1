## Criterios de congruencia de triángulos

**Definición.** Un *criterio de congruencia* es una lista de propiedades que, de cumplirse, aseguran que dos triángulos son congruentes, sin tener que verificar cada una de las igualdades de la definición.

### Criterio LAL (lado-ángulo-lado)

**Teorema.** Sean $\triangle ABC$ y $\triangle DEF$ dos triángulos. Si se tienen las siguientes igualdades:
- $m\left(\overline{AB}\right)=m\left(\overline{DE}\right)$
- $m(\angle{B})=m(\angle{E})$
- $m\left(\overline{BC}\right)=m\left(\overline{EF}\right)$

entonces se puede concluir que $\triangle ABC\cong\triangle DEF$.

---

**Teorema (*pons asinorum*).** Sea $\triangle ABC$ un triángulo isósceles con $m\left(\overline{AB}\right)=m\left(\overline{AC}\right)$. Se tiene $m(\angle B)=m(\angle C)$.

*Demostración.*

*Plan de trabajo:* como nuestro objetivo es mostrar que dos ángulos tienen la misma medida, buscaremos encontrar dos triángulos congruentes en los cuales sean ángulos correspondientes.


<iframe scrolling="no"
src="https://www.geogebra.org/material/iframe/id/dqpwdedn/width/1600/height/715/border/888888/rc/false/ai/false/sdz/false/smb/false/stb/false/stbh/false/ld/false/sri/false/sfsb/true"
width="800"
height="357"
style="border:0px;" allowfullscreen>
</iframe>

||Afirmación / construcción | Justificación |
|---|---|---|
|**(C1)**| Se traza la bisectriz por el vértice $A$ | |
|**(C2)**| El punto $D$ es la intersección entre la bisectriz de **(C1)** &nbsp;y el lado $\overline{BC}$
|**(A3)**| $m\left(\overline{AB}\right)=m\left(\overline{AC}\right)$ | Dato del problema: el triángulo $\triangle ABC$ es isósceles.
|**(A4)**| $m(\angle BAD)=m(\angle DAC)$ | $\overline{AD}$ es bisectriz de $\angle A$, ver **(C1)**
|**(A5)**| $m\left(\overline{AD}\right)=m\left(\overline{AD}\right)$ | Evidente por el significado de igualdad
|**(A6)**| $\triangle ABD\cong\triangle ACD$ | Criterio LAL por **(A3)**, **(A4)**, **(A5)**
|**(A7)**| $m(\angle B)=m(\angle C)$ | Deducción a partir de la congruencia **(A6)**

<!--
*Ejercicio.* A partir de la construcción anterior, obtener las siguientes conclusiones:

- $\overline{AD}$ es transversal de gravedad de $\triangle ABC$
- $\overline{AD}$ es altura de $\triangle ABC$
- $\overline{AD}$ es simetral de $\triangle ABC$

*Ejercicio.* La siguiente afirmación sirve para obtener otra forma de demostrar el teorema anterior (sin necesidad de la bisectriz!) :

> $\triangle ABC \cong \triangle ACB$

Escribir los pasos necesarios para obtener esa afirmación, y cómo utilizarla para mostrar el teorema.
-->

---

### Criterio ALA (ángulo-lado-ángulo)

**Teorema.** Sean $\triangle ABC$ y $\triangle DEF$ dos triángulos. Si se tienen las siguientes igualdades:
- $m(\angle A)=m(\angle D)$
- $m\left(\overline{AB}\right)=m\left(\overline{DE}\right)$
- $m(\angle B)=m(\angle E)$

entonces se puede concluir que $\triangle ABC\cong\triangle DEF$.

**Teorema (recíproco del *pons asinorum*).** Sea $\triangle ABC$ un triángulo con dos ángulos interiores iguales, $m(\angle B)=m(\angle C)$. Entonces es un triángulo isósceles con $m\left(\overline{AB}\right)=m\left(\overline{AC}\right)$.

*Demostración.*

*Plan de trabajo:* como nuestro objetivo es mostrar que dos segmentos tienen la misma medida, buscaremos encontrar dos triángulos congruentes en los cuales sean lados correspondientes.

||Afirmación / construcción | Justificación |
|---|---|---|
|**(A1)** | $m(\angle B)=m(\angle C)$ | Dato del problema |
|**(A2)** | $m\left(\overline{BC}\right)=m\left(\overline{BC}\right)$ | Evidente por el significado de igualdad |
|**(A3)** | $\triangle ABC\cong\triangle ACB$ | Criterio ALA por **(A1)**, **(A2)**, **(A1)**
|**(A4)** | $m\left(\overline{AB}\right)=m\left(\overline{AC}\right)$ | Deducción a partir de la congruencia **(A3)**

---

### Relación con triángulos equiláteros

Las siguientes conclusiones se deducen de los teoremas anteriores recordando que los triángulos equiláteros cumplen también la definición de isósceles.

**Corolario.** En un triángulo equilátero todos los ángulos interiores son iguales.

**Corolario.** Si en un triángulo todos los ángulos interiores son iguales entonces el triángulo es equilátero.
