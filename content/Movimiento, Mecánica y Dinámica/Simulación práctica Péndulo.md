#### Autores: Geraldine Londoño Torres y Juan G. Saurith Moreno.
#### Materia: Principios de Física.

A continuación, se presenta la resolución paso a paso de cada uno de los ejercicios dispuestos en la [guía](https://drive.google.com/file/d/1Wcs9X5ZEoCg9ZWKYTkhSaDli10mkmdPh/view). Para la realización de esta simulación se utilizó un [simulador virtual](https://phet.colorado.edu/sims/html/pendulum-lab/latest/pendulum-lab_es.html) con el fin de observar y analizar variables como [[Movimiento#Periodo (T)| periodo]], [[Distancia#Longitud|longitud]], [[Tiempo|tiempo]], y [[Masa|masa]].

---
# Punto 1.

Tomando una cuerda de distancia $(l)$, varíe el valor de la longitud del péndulo y mida con el cronómetro presente, el tiempo que demora en realizar el movimiento de ida y vuelta, ¿ Qué tipo de relación encuentra?. Genere una tabla de datos de tiempos ida y vuelta (T = Periodo), versus longitudes de la cuerda, con ellos construya una gráfica, describa y determine el tipo de relación entre las variables (T vs L).
### Explicación

En la simulación se utilizó un péndulo con distinta longitud de cuerda, con un ángulo inicial siempre de 90°, se registró el periodo que el péndulo demoró en realizar un movimiento de ida y vuelta y se registró todo en una tabla:

| Longitud (L) | Periodo (T) |
| ------------ | ----------- |
| 0.40         | 1.60        |
| 0.60         | 1.90        |
| 0.80         | 2.25        |
| 1.00         | 2.45        |

La relación entre la longitud (L) del péndulo y su período (T) está descrita por la fórmula,
$$T=2\pi\sqrt\frac{L}{g}$$
donde:
- $T$ es el período en segundos.
- $L$ es la longitud del péndulo en metros.
- $g$ es la aceleración de la gravedad.

Esta fórmula lo que nos dice es que, si la longitud se cuadriplica, el periodo se va a duplicar, por lo que la proporción es no lineal. En la práctica, se notó que cuando la longitud de la cuerda aumenta, el péndulo se demora más en dar un ciclo ya que la trayectoria es más larga, por lo que su periodo también aumenta. Por el contrario, si la longitud es más corta el péndulo va a completar el ciclo más rápido ya que tiene un menor recorrido. Con los datos que se tomaron se hizo la siguiente gráfica:

![[grafica péndulo.png|grafica péndulo ]]
Gráfica 1: Relación entre el periodo y la longitud de un péndulo 

Para revisar los cálculos del ajuste puede ir a: https://docs.google.com/spreadsheets/d/1disIiEvX2eVT39P8aSMXKHR1N2YU1uTvRTEdmZdfHaU/edit?usp=sharing

 Lo que se hizo fue usar el método de mínimos cuadrados, con el fin de encontrar una función que se ajuste a los datos sacados de la simulación. El objetivo de este método es que la curva que se obtiene ($y=2.42x^{0.438}$) pase lo más cerca que se pueda de los puntos para que las diferencias entre los valores de los datos y los valores de la curva sean lo más pequeños posible. En este caso el ajuste se realizó utilizando una función que sigue la forma $y = ax^n$ que es de tipo potencial.

# Punto 2.

Ahora observe cómo afecta el tiempo de ida y vuelta, el cambio de la aceleración gravitacional del planeta, manteniendo la longitud constante, ¿Será que el péndulo oscila diferente si está en la tierra o en la luna? ¿el tiempo de ida y vuelta será el mismo si el péndulo está en el Ecuador terrestre o en el polo norte de la tierra?. Genere una tabla de datos del tiempo ida y vuelta (T=Periodo) versus la aceleración de la gravedad del sitio donde está el péndulo, con ellos construya una gráfica, describa y determine el tipo de relación entre las
variables (T vs g).

## Explicación 

En la simulación se utilizó un péndulo con una longitud de cuerda de 0.80m en todos los casos, con un ángulo inicial siempre de 90°. Se registró el periodo que el péndulo demoró en realizar un movimiento de ida y vuelta con distinta aceleración gravitacional y se registró todo en la siguiente tabla:

| Planeta | A. Gravitacional (g) | Periodo (T) |
| ------- | -------------------- | ----------- |
| Luna    | 1.62                 | 5.12        |
| Tierra  | 9.80                 | 2.25        |
| Júpiter | 26.39                | 1.37        |

Considerando de nuevo la fórmula del periodo del péndulo, la cual es $T=2\pi\sqrt\frac{L}{g}$; se puede observar que hay una relación inversa entre el periodo y la aceleración gravitacional, lo que implica que al aumentar la aceleración gravitacional el periodo disminuye y viceversa. En la tabla vemos que la Luna tiene una gravedad muy baja de $1.62m/s^2$, lo que resulta en un periodo más alto de $5.12s$ en comparación con los demás, mientras que en Júpiter, al tener luna mayor aceleración gravitacional con $26.39m/s^2$, el periodo es el menor con $1.37s$.
Esto sucede porque una mayor gravedad acelera el movimiento del péndulo, haciendo que tarde menos tiempo en completar las oscilaciones, es como si la gravedad "apresurara" al péndulo para regresar a su punto inicial. Mediante la tabla se hizo la siguiente gráfica:

![[img 2.png|img]]
Gráfica 2: relación entre gravedad y periodo

La gráfica nos muestra que evidentemente el periodo y la gravedad son inversamente proporcionales, por lo que mientras uno aumenta el otro disminuye, evidenciando que la simulación es correcta, además esto se comprobó también con la fórmula del periodo de un péndulo donde nos dicen matemáticamente la relación entre periodo y aceleración gravitacional.

# Punto 3.

¿Qué sucede si se varía la masa del cuerpo en oscilación? ¿será que el péndulo oscila diferente si se suspende una bola de boliche o una bola de billar? Genere una tabla de datos del tiempo ida y vuelta (T=Periodo) versus la masa del cuerpo, teniendo fija la longitud y la aceleración de la gravedad del sitio, con ellos construya una gráfica, describa y determine el tipo de relación entre las variables (T vs m).
### Explicación

En la simulación se utilizó un péndulo con una longitud siempre de $0.80m$, una gravedad constante de $9.8m/s^2$, y con un ángulo inicial siempre de 90°. Se registró el periodo del péndulo de ida y vuelta cambiando su masa con el fin de determinar la relación que hay entre la variación de masa con el periodo del péndulo. Esto se registró en una tabla:

| Masa (m) | Periodo (T) |
| -------- | ----------- |
| 1.5      | 2.149       |
| 1.2      | 2.150       |
| 1        | 2.152       |
| 0.8      | 2.153       |

Analizando la tabla, se notó que el periodo cambia muy levemente de acuerdo a las distintas masas del péndulo, sin embargo, esto se debe a errores experimentales al momento de usar el cronometro, puesto que la masa no está relacionada con el periodo. El péndulo no oscila diferente si usamos objetos de distintas masas y esto lo podemos confirmar trayendo de nuevo la fórmula del periodo de un péndulo: $T=2\pi\sqrt\frac{L}{g}$. Como se puede observar la masa no aparece en esta fórmula, ya que el periodo depende es de la longitud y de la aceleración gravitacional, si estos permanecen constantes el periodo del péndulo permanecerá igual independientemente de la masa.

![[masa péndulo.png|variación]]
Gráfica 3: relación entre masa y periodo

La gráfica número 3 nos muestra la relación entre la masa y el periodo del péndulo, notamos que el periodo es "constante", es decir que no cambia respecto a los cambios en la masa.

# Punto 4.

¿Según su criterio, existirán otras fuentes que generen variación del Periodo T?, si es así, para
comprobar dicha variación ¿Qué información podría obtenerse con la simulación?

### Explicación

Después de experimentar con las variables del simulador llegamos a la conclusión de que la variación del periodo de un péndulo también se ve afectada por la [[Fuerza#Fuerza de rozamiento|fricción]], ya que esta lo que hace es generar una especie de resistencia que afecta el movimiento de oscilación del péndulo, lo que hace que el periodo cambie de acuerdo a la fuerza de rozamiento.

También notamos que si no hay una fuerza de fricción el péndulo seguiría oscilando infinitamente, mientras que cuando hay rozamiento este va frenando poco a poco, esto lo podemos explicar con una de las leyes de la fuerza de rozamiento que dice: Tiene una dirección opuesta al movimiento del objeto. Lo que significa que si por ejemplo, empujamos una caja hacia la derecha, la fuerza de fricción va a actuar hacia la izquierda, porque siempre se va a oponer al movimiento.

En la simulación nos fijamos que a mayor fricción menos oscilaba el péndulo y con menos fuerza, es decir su amplitud disminuía mientras más fricción se le aplicaba, esto ocurre porque el péndulo necesita más energía para vencer esa fuerza de fricción, lo que hace que recorra una menor distancia y por esto mismo entre más fricción más rápido va a dejar de oscilar y volver a su estado de reposo.

# Punto 5.

¿Qué efecto tendrá en el movimiento del péndulo, si se suelta de un ángulo de 45°?
### Explicación

Cuando soltamos el péndulo desde un ángulo de 45° podemos notar que la velocidad tanto para el eje X, como para el eje Y es la misma, esto porque:
$$V=\sqrt {V_x^2+V_y^2}$$
y sabiendo que la velocidad en el eje X está dada por la ecuación:
$$V_x=V_0sen\theta$$
Sabiendo que el seno del ángulo de 45° es $\frac{\sqrt{2}}{2}$

y que la velocidad en el eje Y está dada por la ecuación:
$$V_y= V_0cos\theta$$
Sabiendo que el coseno del ángulo de 45° es $\frac{\sqrt{2}}{2}$

Por lo tanto $V_x=V_y$

Así que la ecuación original quedaría como $V = \sqrt{\left(V \cdot \left(\frac{\sqrt{2}}{2} \right)^2\right)^2 + \left(V \cdot \left(\frac{\sqrt{2}}{2} \right)^2\right)^2}$

$V = \sqrt{2 \cdot \left(V \cdot \left(\frac{\sqrt{2}}{2} \right)^2\right)^2}$

$V = \sqrt{2 \cdot \frac{V^2}{2}}$

$V = \sqrt{V^2}$

$V=V$

Lo que confirma que tanto el movimiento en el eje horizontal como en el vertical será igual.

