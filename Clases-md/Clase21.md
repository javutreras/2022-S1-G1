## Área y perímetro de un círculo

**Problema.** Determinar el área y el perímetro de un círculo no se deduce directamente de las herramientas desarrolladas hasta ahora. Todas estas herramientas sirven para trabajar con triángulos y, por extensión, polígonos.

---

### Problema auxiliar

Se trabajará en un círculo de radio $1$, para simplificar las cuentas.

Con dos radios de este círculo, más la cuerda que une sus extremos, se construye un triángulo isósceles agudo. Lo llamaremos el *primer triángulo*.

Se traza un radio que sea bisectriz del primer triángulo. Este radio, junto con uno de los radios originales y la cuerda que una sus extremos forman un nuevo triángulo. Lo llamaremos el *segundo triángulo*.

El problema es el siguiente: ¿cuál es la relación entre los lados y el área de estos dos triángulos? Más precisamente: a partir de las medidas de los lados del primer triángulo buscamos determinar
- el área del primer triángulo, y

- las medidas de los lados del segundo triángulo.

---

### Motivación

El estudio que se realizará sobre el círculo está basado en trabajos de Arquímedes. La idea será inscribir polígonos dentro del círculo con cantidades cada vez más grandes de lados; entonces el perímetro y el área de cada polígono serán aproximaxiones cada vez más precisas del perímetro y el área del círculo.

Pero cada polígono regular (todos los lados y ángulos iguales) que se inscriba en el círculo se puede pensar como una unión de triángulos isósceles con un vértice común en el origen. Y el acto de "construir polígonos con cantidades cada vez más grandes de lados" se puede pensar como construir polígonos cuyos triángulos isósceles tengan un ángulo central cada vez más pequeño.

El paso del *primer triángulo* al *segundo triángulo* es la forma en que se cuantificará este proceso de "construir polígonos con cantidades cada vez más grandes de lados".

---

### Solución al problema auxiliar

Si la cuerda del primer triángulo mide una cantidad $x$, definimos la cantidad $A=2-\sqrt{4-x^2}$. Entonces:

- el área del primer triángulo es $\frac{x\left(1-\frac{A}{2}\right)}{2}$;

- la cuerda del segundo triángulo mide $\sqrt{A}$.

La justificación de estos hechos está basada en los teoremas de Euclides para el triángulo rectángulo.

---

### Aplicación al círculo de radio 1

Tal como hizo Arquímedes, se empezará con el hexágono regular inscrito. El motivo para esto es muy simple: los triángulos centrales que forman el hexágono son todos equiláteros. Por consiguiente la cuerda del primer triángulo formado mide $x=1$.

A partir de este dato inicial se procede de forma recursiva: se pasa al polígono de doce lados, después usándolo como caso base al de veinticuatro lados, y así sucesivamente, duplicando siempre la cantidad de lados.

[Se llega a los siguientes valores en las primeras iteraciones.](https://github.com/javutreras/2022-S1-G1/blob/main/Clases/geo_circle.ipynb)
