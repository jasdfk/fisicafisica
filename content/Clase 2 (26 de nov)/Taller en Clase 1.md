A continuación, se presenta la resolución paso a paso de cada uno de los ejercicios dispuestos en la [guía](https://drive.google.com/file/d/1snwBY7RKFqNlSfp_sxXq5GegcO-5Fe96/view) de trabajo número uno. Para realizar la solución a cada uno de los incisos, se utilizaron múltiples ecuaciones de **cinemática**; empleando el uso de conceptos como la [[Velocidad|velocidad]], [[aceleración]], [[tiempo]], [[Trayectoria|trayectoria]] y otros más.

---


## Punto 1.
Pensemos en una pelota que es lanzada horizontalmente y la cual choca frontalmente con una pared que se encuentra a $5$ m de distancia del sitio origen desde el cual se lanzó. La altura del punto en que la pelota choca contra la pared es $1$ m más baja que la altura desde la cual la pelota fue lanzada. 
%% 
**Diagrama:**

![[ej1.png|500]]
 %%
### **1. ¿Con qué velocidad $v_o$ fue lanzada la pelota?**

El primer paso para hacer la solución, fue hallar el tiempo en que sucedió este evento. Para ello, aplicamos la siguiente ecuación:

$$
t = \sqrt{\frac{2}{g}} \approx 0.45~\text{s}
$$

Según esto, el tiempo hasta la colisión fue de aproximadamente $0.45 ~\text{s}$. Con este valor, podemos despejar la velocidad inicial ($v_o$) y teniendo en cuenta la distancia entre la pelota y la pared a partir de la siguiente expresión:

$$
x = v_o \cdot t ~\longrightarrow ~v_o = \frac{x}{t} 
$$
$$
\therefore v_o = \frac{5 ~\text{m}}{0.45 ~\text{s}} =11.\bar{1} ~\text{m/s}
$$




### **2. ¿Qué ángulo $\varphi$ formó la trayectoria de la pelota con la superficie de la pared al llegar a ella? En todo el problema se desprecia la resistencia del aire.**


Para calcular el ángulo que forma la trayectoria de la pelota con la superficie de la pared, es importante tener en cuenta la velocidad (vertical) con la que esta llega a la pared, para que luego, utilizando la tangente, lleguemos a la solución. Dando así el siguiente razonamiento:

$$

	v_y = g\cdot t \rightarrow 9.8 ~\text{m/s$^2$} \cdot 0.45 ~\text{s}

	 

$$
$$
\therefore v_y = 4.41 ~\text{m/s}
$$



Una vez calculado nuestra velocidad vertical, podemos pasar a utilizar la tangente (utilizando ambas velocidades) para el calcular el ángulo de impacto. Pues, tendremos los _catetos_ al ser los [[Vector|vectores]] de cada componente. Lo cual lo cual nos llevó al siguiente razonamiento:

$$
\tan{\varphi} = \frac{v_y}{v_o}= \frac{4.41 ~\text{m/s}}{11.\bar{1} ~\text{m/s}} \approx 0.3969
$$


Una vez calculada la tangente, lo único que haremos será utilizar la arcotangente para despejar el valor del ángulo.


$$

	\varphi = \arctan{(0.3969)}

	
$$
$$
\therefore \varphi = 21.648°
$$

---



## Punto 2.
Pensemos que el río Guatapurí a la altura de Hurtado tiene un ancho de 50 m y una corriente que es igual a 5 km/h. Si tenemos que cruzarlo en 1 min desde un punto en la orilla hasta el punto enfrentado directamente en la otra orilla.

 ### **1. ¿Con qué velocidad debemos movernos desde A para poder llegar a B?**

Del anterior enunciado, pudimos obtener la distancia entre ambos puntos (que está regida por el ancho del río). Para este caso, la distancia es $x = 50 ~\text{m}$; por otro lado, se necesita cruzarlo en un minuto, por lo que el tiempo que trabajaremos será $t = 60 ~\text{s}$.

Con estos datos, podemos pasar a calcular con qué velocidad tendríamos que pasar inicialmente el río para poder recorrer los 50 metros en un minuto ($v_y$) y se realiza una conversión de unidades entre kilómetros por hora a metros por segundo (únicamente hay que multiplicar el valor por $3.6$). Una vez realizados estos análisis, tendríamos 


$$

v_y= \frac{x}{t} = \frac{50~\text{m}}{60~\text{s}}= 0.833~\text{m/s}

$$
$$
v_{\text{rio}}= 5 ~\text{km/h} \longrightarrow 1.388 ~\text{m/s}
$$


> [!WARNING] Advertencia!
> Es importante mencionar que $v_y$ es la velocidad que se requeriría si existiese una **ausencia** en la corriente del agua.


Para calcular la velocidad requerida utilizaremos la siguiente ecuación:

 $$
 v_{req}= \sqrt{(v_{y})^{2}+(v_{\text{rio}})^{2}}
 $$
 
 Reemplazando:


$$
v_{req}= \sqrt{(0.833~\text{m/s})^{2}+(1.388~\text{m/s})^{2}}
$$
$$
\therefore v_{req} = 1.618~\text{m/s}
$$

  Por lo tanto, la velocidad a la que debemos movernos desde el punto A debe ser igual a $1.618~\text{m/s}$.
   
 ### **2. ¿Qué ángulo con respecto a la orilla debemos tomar para compensar la corriente y alcanzar B directamente?"**

Para darle solución a la pregunta, se utilizaremos la tangente de manera similar que el punto anterior, pues podemos construir otro triángulo y calcular, en este caso, esta razón trigonométrica para poder hallar el ángulo de interés.

Para este caso, llamaremos al ángulo $\alpha$, y pues tendremos como catetos para calcularlo; la velocidad del río y la velocidad vertical necesaria para cruzar la amplitud del río. Esquematizando todo obtenemos lo siguiente:
   
$$
   \tan(\alpha)=\frac{v_{y}}{v_{\text{rio}}}=\frac{0.833~\text{m/s}}{1.388 ~\text{m/s}}= 0.6
$$

Una vez calculada la tangente, lo único que haremos será utilizar la arcotangente para despejar el valor del ángulo.  

$$
\alpha=\arctan(0.6)
$$
$$
 \alpha \approx 30.963°
$$



---



## Punto 3.
Continuando con ríos; esta vez en el Rio Cesar, tenemos una pequeña embarcación la cual es arrastrada por una corriente de $3$ km/h dirigida hacia el Este. La velocidad de la embarcación en ausencia de corriente es de $15$ km/h.

### **1. Indicar cuál es el rumbo (ángulo) que debería seguir la embarcación para dirigirse al Nordeste (45°) de su posición actual**

Tras leer el enunciado, podemos extraer información clave; dentro de ellas está la velocidad que presenta la corriente que afecta la embarcación, la cual corresponde a $3$ km/h. Además está la velocidad a la que se está moviendo la embarcación que es $15$ km/h; con un rumbo ajustable. Y por último tenemos la dirección hacia la cual queremos dirigirnos, que sería hacia 45° apuntando al Nordeste. 

Entendiendo que el Este corresponde al eje positivo en la componente $x$ y que la embarcación sigue un rumbo con ángulo $\theta$ respecto al Este, podemos calcular las componentes de velocidad de la embarcación para cada uno de los ejes según las siguientes ecuaciones:

$$
v_{\text{emb, $x$}} = v_{\text{emb}} \cos \theta, \quad\quad v_{\text{emb, $y$}} = v_{\text{emb}} \sin \theta
$$

Para que la resultante sea Nordeste a $45°$, la relación de las componentes $x$ y $y$ del vector velocidad para la embarcación tiene que seguir el siguiente criterio:

$$
\tan (45°) = \frac{\text{Componentes en $y$}}{\text{Componentes en $x$}} = 1
$$

Por lo que las componentes para $y$ son iguales a las componentes en $x$.


> [!HINT] Nota
> La componente en $x$ de la velocidad total está dada por la **suma** de la velocidad de la corriente del río y la componente $x$ de la velocidad de la embarcación. Esta última se obtiene multiplicando la velocidad de la embarcación por el coseno del ángulo de dirección.
> 
> Por otro lado, la componente en $y$ solo depende de la velocidad propia de la embarcación, ya que la corriente del río no tiene efecto sobre el movimiento en el eje $y$.
> 

Por lo anterior, podemos expresar la siguiente igualdad:

$$
v_{\text{emb}} \sin \theta = 3 ~\text{km/h}+v_{\text{emb}} \cos \theta
$$

Re-organizando y simplificando esta expresión, obtendremos esto:

$$
v_{\text{emb}} \sin \theta - v_{\text{emb}} \cos \theta= 3 ~\text{km/h}
$$
$$
v_{\text{emb}} (\sin \theta - \cos \theta)= 3 ~\text{km/h}
$$
$$
\sin \theta - \cos \theta= \frac{3 ~\text{km/h}}{v_{\text{emb}}} = \frac{3 ~\text{km/h}}{15 ~\text{km/h}}
$$
$$
\sin \theta - \cos \theta= 0.2
$$

> [!EXAMPLE] ¿$\sin\theta - \cos\theta$?
> Para proseguir con el cálculo del ángulo, es importante poder seguir simplificando esta expresión. Para poder resolverla, nos apoyamos en una **propiedad trigonométrica** que combina el seno y el coseno en una sola función sinusoidal. Dicha propiedad dice:
> 
> $$
> a \sin \theta + b \cos\theta = R \sin(\theta + \phi)
> $$
> 
> Donde:
> - $R := \sqrt{a^2 +b^2}$ ; conocido como amplitud resultante.
> - $\phi = \arctan(\frac{b}{a})$ ; conocido como el ángulo de desfase.
>   
> Para el caso específico de $\sin\theta - \cos\theta$ tenemos que:
> - $a = 1$ ; que es el coeficiente que acompaña al seno.
> - $b = -1$ ; que es el coeficiente que acompaña al coseno.
>   
> Empleando la ecuación para calcular $R$:
> 
> $$
> R = \sqrt{a^2 +b^2} = \sqrt{1^2 + (-1)^2} = \sqrt{2}
> $$
> 
> El calculo del desfase se muestra a continuación:
> 
> $$
> \phi = \arctan(\frac{b}{a}) = \arctan(\frac{-1}{1}) = \arctan(-1)
> $$
> 
> Se conoce que:
> 
> $$
> \tan(-45°) = -1
> $$
> 
> Por lo tanto:
> 
> $$
> \phi = -45°
> $$
> 
> Con el cálculo de $R$ y $\phi$ podemos concluir que:
> 
> $$
> \sin\theta - \cos\theta = \sqrt{2}\sin(\theta - 45°)
> $$


Ahora podemos continuar con el despeje:

$$
\sqrt{2}\sin(\theta - 45°)= 0.2
$$
$$
\sin(\theta - 45°)= \frac{0.2}{\sqrt{2}} \approx 0.1414
$$
$$
\theta - 45° = \arcsin(0.1414) \approx 8.1°
$$
$$
\theta =  8.1° + 45°
$$
$$
\theta =  53.1°
$$

Por lo que el rumbo que debe fijar el barco es de $53.1°$ con respecto al eje Este.

### **2. Cálculo de la velocidad total al tener el rumbo correcto fijado.** 
Lo primero que realizaré será calcular cada una de las componentes de velocidad para la embarcación ahora que sabemos que ángulo utilizaremos:

$$
v_{\text{emb, $x$}} = v_{\text{emb}} \cos \theta, \quad\quad v_{\text{emb, $y$}} = v_{\text{emb}} \sin \theta
$$
$$
v_{\text{emb, $x$}} = 15 ~\text{km/h} \cdot \cos (53.1°), \quad\quad v_{\text{emb, $y$}} = 15 ~\text{km/h}  \cdot\sin (53.1°)
$$
$$
v_{\text{emb, $x$}} \approx 9 ~\text{km/h}, \quad\quad v_{\text{emb, $y$}} = 12 ~\text{km/h}
$$

Ahora, haremos la componente total $x$, sumando la velocidad de la embarcación en este eje con la velocidad de la corriente. La componente total $y$ permanecerá igual a la de la embarcación.

$$
v_{\text{T, $x$}} = 9~\text{km/h} + 3 ~\text{km/h}, \quad\quad v_{\text{T, $y$}} = 12 ~\text{km/h}
$$
$$
v_{\text{T, $x$}} = 12 ~\text{km/h}, \quad\quad v_{\text{T, $y$}} = 12 ~\text{km/h}
$$

Para calcular la velocidad total, lo que haremos será elevar cada una de estas velocidades totales por componente al cuadrado, sumarlas y sacarle la raíz al total.

$$
v_{total} = \sqrt{v_{\text{T, $x$}}^2 + v_{\text{T, $y$}}^2 }
$$
$$
v_{total} = \sqrt{(12 ~\text{km/h})^2 + (12 ~\text{km/h})^2 }
$$
$$
v_{total} = \sqrt{144 ~\text{km$^2$/h$^2$} + 144 ~\text{km$^2$/h$^2$} }
$$
$$
v_{total} = \sqrt{288 ~\text{km$^2$/h$^2$} }
$$
$$
v_{total} \approx 16.97  ~\text{km/h}
$$

Por lo que la velocidad total una vez situado el rumbo será de $\approx 16.97  ~\text{km/h}$.

---


## Punto 4.
Pensemos que lanzamos un balón dentro de un campo de fútbol con un ángulo de elevación de $30°$ y con una velocidad inicial de $20 ~\text{m/s}$.


> [!HINT] Nota
> Para la resolución de este ejercicio se utilizaron las ecuaciones del **movimiento parabólico**.

### **1. ¿Cuánto tiempo permaneció el balón en el aire?**

Para hallar el tiempo en el que el balón permanece en el aire, utilizamos la siguiente fórmula:

$$
t_{\text{vuelo}}= \frac{2 v_{o} \cdot \sin\theta}{g}
$$

Reemplazando nos da que,

$$
t_{vuelo}= \frac{(2\times 20 ~\text{m/s})\cdot  \sin (30°) }{9.8~\text{m/s$^2$}}= \frac{40 ~\text{m/s}\cdot  \frac{1}{2} }{9.8~\text{m/s$^2$}} = \frac{20 ~\text{m/s}}{9.8~\text{m/s$^2$}}
$$
$$
\therefore t_{\text{vuelo}} \approx 2.04 ~\text{s} 
$$


Por lo anterior, el tiempo que el balón permanece en el aire es de $2.04$ segundos.

### **2. ¿Qué altura máxima alcanza el balón?**

Para hallar la altura máxima alcanzada del balón se utilizó la siguiente igualdad:

$$
h_{\text{max}}=\frac{v_{o}^2 \cdot \sin^{2}\theta}{2g}
$$
Reemplazando:

$$
h_{\text{max}}=\frac{(20 ~\text{m/s})^2 \cdot \sin^{2}(30°) }{2\cdot 9.8 ~\text{m/s$^2$}}=\frac{(400 ~\text{m$^2$/s$^2$}) \cdot \frac{1}{4} }{19.6 ~\text{m/s$^2$}} = \frac{100 ~\text{m$^2$/s$^2$}}{19.6 ~\text{m/s$^2$}}
$$
$$
\therefore h_{\text{max}} \approx 5.102 ~\text{m} 
$$

Por lo que la altura máxima alcanzada por la pelota fue de $5.102$ metros.

### **3. ¿Cuánto fue la distancia recorrida en todo el recorrido?**

Para hallar la distancia recorrida por el balón se usó la fórmula:

$$
x_{rec}=\frac{v_{o}^2 \cdot \sin(2 \theta )}{g}
$$

Que al reemplazar nos da,      

$$
x_{rec}=\frac{(20 ~\text{m/s})^2\cdot \sin(2\cdot30° )}{9.8 ~\text{m/s$^2$}} = \frac{(400 ~\text{m$^2$/s$^2$})\cdot \sin(60° )}{9.8 ~\text{m/s$^2$}}= \frac{(400 ~\text{m$^2$/s$^2$})\cdot \frac{\sqrt{3}}{2}}{9.8 ~\text{m/s$^2$}}
$$
$$
\therefore x_{\text{rec}} \approx 35.35 ~\text{m}
$$

Por lo tanto, la distancia recorrida fue de 35.35 metros.

## Punto 5.
Pensemos en una rueda cuyo radio es de $10$ cm y que está girando a una velocidad angular de $120$ r.p.m. A esta rueda se le aplican los frenos y se detiene en 4 segundos.

### **1. ¿Cuál es la aceleración angular si se supone como constante la fuerza de frenado?**

Para determinar la aceleración angular de la rueda lo primero que se hizo fue convertir los 120 r.p.m a Hertz para hallar la [[Movimiento#Frecuencia (f)|frecuencia]] y luego con eso hallar la velocidad angular inicial ($\omega_{o}$), donde $T$ es el periodo y se calcula como $1/\text{Frecuencia}$ ($f_i$). A continuación se muestra el cálculo de las frecuencias:

$$
f_{i}= \frac{120 ~\text{rpm}}{60}= 2 ~\text{Hz}
$$
$$
\therefore T= \frac{1}{2 ~\text{Hz}} 
$$

Con esta información, calculamos la velocidad angular inicial:

$$
\omega_o=\frac{2\pi}{T}=\frac{2\pi}{\frac{1}{2}}=4\pi
$$

Conociendo la velocidad angular, se calcula la aceleración angular a partir de la siguiente expresión:

$$
a=-\frac{\omega_{o}}{t}
$$

Reemplazando:

 $$
 a=-\frac{4\pi}{4}=-\pi \, \text{rad/s}^2
 $$

Por lo anterior, se concluye que existe una aceleración negativa de $-\pi$ a la velocidad cada segundo. Por lo que efectivamente al transcurrir los 4 segundos, la velocidad se vuelve 0.

### **2. ¿Cuál es la aceleración normal en un punto de la rueda después de 1 segundo después de aplicar los frenos?**

Para encontrar la aceleración normal se utilizó la siguiente fórmula:

$$
a_n=\frac{(\omega_o)^2}{r}
$$

Teniendo en cuenta que en el planteamiento de la pregunta nos dicen que debemos tomar la velocidad angular un segundo después de aplicar los frenos, se resta ese segundo a la velocidad angular total, quedando como $3\pi$ el valor de su velocidad y se establece que $r$ es el radio de la rueda. Por lo que al reemplazar obtenemos lo siguiente:

$$
a_n=\frac{(3\pi)^2}{10}= 8.88m/s^2
$$

### **3. ¿Cuál es el ángulo de giro que tiene la rueda hasta detenerse?**

Para hallar el ángulo de giro de la rueda usamos la siguiente fórmula:
 
 $$
 \theta= \omega_o\cdot t+\frac{1}{2}\cdot a\cdot t^2
 $$
 
 Reemplazando tenemos que:
 
 $$
 \theta=(4\pi)(4)+\frac{1}{2}(-\pi)(4)^2= 8\pi\approx 25.13 ~\text{rad}
 $$
 
 El ángulo de giro que tiene la rueda hasta detenerse es de 25.13 rad.