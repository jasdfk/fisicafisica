#### Autores: Geraldine Londoño Torres y Juan G. Saurith Moreno.
#### Materia: Principios de Física.

A continuación, se presenta la resolución paso a paso de cada uno de los ejercicios dispuestos en el [taller 2](https://drive.google.com/file/d/1v7llQi9ZQ1w2xrZPNq6MvekPOFZH_ph2/view) práctico para el parcial. Para realizar la solución a cada uno de los incisos, se utilizaron múltiples ecuaciones de **cinemática** en dos dimensiones; empleando el uso de conceptos como la [[Velocidad|velocidad]], [[aceleración]], [[tiempo]], [[Trayectoria|trayectoria]] y otros más. (Realizado en Obsidian)

---

## Punto 1.
Un pez que nada en un plano horizontal tiene velocidad $\vec{v}_i = (4.00 \hat{\imath} + 1.00 \hat{\jmath}) ~\text{m/s}$ en un punto en el océano donde la [[Posición|posición]] relativa a cierta roca es  $\vec{r}_i = (10.0 \hat{\imath} - 4.00 \hat{\jmath}) ~\text{m}$. Después que el pez nada con aceleración constante durante $20.0$ s, su velocidad es $\vec{v} = (20.0 \hat{\imath} - 5.00 \hat{\jmath}) ~\text{m/s}$.

### **a. ¿Cuáles son las componentes de la aceleración del pez?**

Lo primero que tenemos que saber es que para definir las componentes de aceleración del pez que actúan en este movimiento de dos dimensiones necesitaremos calcular el $\Delta v$; para ello haremos la resta de ambas velocidades dadas por el ejercicio; esto es $\vec{v}_i - \vec{v}$; restando componente a componente de la siguiente manera:

$$
\Delta v = (20.0 \hat{\imath} - 5.00 \hat{\jmath}) - (4.00 \hat{\imath} + 1.00 \hat{\jmath})
$$
$$
\Delta v = (16.0 \hat{\imath} - 6.00 \hat{\jmath})
$$

Ahora lo que tenemos que hacer es multiplica este $\Delta v$ por $1/t$; lo que equivaldría a dividir cada una de las componentes entre 20.

$$
\Delta a = \frac{1}{20.0} \cdot (16.0 \hat{\imath} - 6.00 \hat{\jmath})
$$
$$
\Delta a =  \left( \frac{16.0}{20.0} \hat{\imath} - \frac{6.00}{20.0} \hat{\jmath} \right)
$$
$$
\Delta a = \left(\frac{4}{5} \hat{\imath} - \frac{3}{10} \hat{\jmath}\right)
$$

Por lo que tenemos que las componentes para la aceleración están dadas por $\frac{4}{5}$ para el eje $x$ y $-\frac{3}{10}$ para el eje $y$.

### **b. ¿Cuál es la dirección de su aceleración  respecto del vector unitario $\hat{\imath}$?**

Para calcular la dirección de la aceleración con respecto al vector unitario del eje $x$ se utilizará la arcotangente de la relación entre las ambas componentes del vector aceleración de la siguiente manera:

$$
\theta = \arctan \left(\frac{a_y}{a_x}\right)= \arctan \left(-\frac{\frac{3}{10}}{\frac{4}{5}}\right) = \arctan \left(-\frac{15}{40}\right) = \arctan \left(-\frac{3}{8}\right) 
$$
$$
\theta \approx -20.556°
$$

Por lo que la aceleración posee una dirección de aproximadamente $20.556°$ por debajo del eje positivo $\hat{\imath}$.


### **c. Si el pez se mantiene con aceleración constante, ¿Dónde estará en $t = 25 ~\text{s}$ y en que dirección se mueve?**

Utilizaremos la ecuación que permite calcular la posición de un móvil en un movimiento uniformemente acelerado, la cual es:

$$
x(t) = x_o + v_o \cdot t + \frac{1}{2 }\cdot a \cdot t^2
$$

En este caso específico, los valores de $x_o, v_o$ y $a$ son vectores bidimensionales, por lo que tendríamos que escribirlo como una combinación lineal de estos de la siguiente manera:

$$
x(t)_{\text{2D}}=(x_o, ~y_o) + v(\hat{\imath}, ~\hat{\jmath}) \cdot t + \frac{1}{2} \cdot a(\hat{\imath}, ~\hat{\jmath}) \cdot t^2
$$

Reemplazando estos valores tendríamos:

$$
x(25)_{\text{2D}}=(10.0 \hat{\imath} - 4.00 \hat{\jmath}) + (4.00 \hat{\imath} + 1.00 \hat{\jmath}) \cdot (25) + \frac{1}{2} \cdot \left(\frac{4}{5} \hat{\imath} - \frac{3}{10} \hat{\jmath}\right) \cdot (25)^2
$$

Resolviendo: 

$$
x(25)_{\text{2D}}=(10.0 \hat{\imath} - 4.00 \hat{\jmath}) + (100 \hat{\imath} + 25 \hat{\jmath}) + \frac{1}{2} \cdot \left(\frac{4}{5} \hat{\imath} - \frac{3}{10} \hat{\jmath}\right) \cdot 625
$$
$$
x(25)_{\text{2D}}=(10.0 \hat{\imath} - 4.00 \hat{\jmath}) + (100 \hat{\imath} + 25 \hat{\jmath}) + 312.5 \cdot \left(\frac{4}{5} \hat{\imath} - \frac{3}{10} \hat{\jmath}\right) 
$$
$$
x(25)_{\text{2D}}=(10.0 \hat{\imath} - 4.00 \hat{\jmath}) + (100 \hat{\imath} + 25 \hat{\jmath}) +\left(250 \hat{\imath} - 93.75 \hat{\jmath}\right) 
$$
$$
x(25)_{\text{2D}}=(360 \hat{\imath} - 72.75\hat{\jmath}) 
$$

Para calcular la dirección de la velocidad calcularemos la velocidad hasta ese punto, que en este caso se calculará como:

$$
v(25) =(4.00\hat{\imath} + 1.00\hat{\jmath}) + \left(\frac{4}{5} \hat{\imath} - \frac{3}{10} \hat{\jmath}\right) \cdot 25
$$
$$
v(25) =(4.00\hat{\imath} + 1.00\hat{\jmath}) + \left(20.00 \hat{\imath} - 7.50\hat{\jmath}\right)
$$
$$
v(25) =(24.00\hat{\imath} - 6.50 \hat{\jmath})
$$

Por lo que la dirección estará dada por:

$$
\alpha =  \arctan \left(-\frac{6.50}{24.00}  \right)
$$
$$
\alpha \approx −15.1°
$$

---
## Punto 2.
Un estudiante se encuentra de pie en el borde de un acantilado y lanza una piedra horizontalmente sobre el borde con una velocidad de $v_i = 18.0 ~\text{m/s}$. El acantilado tiene $h = 50.0 ~\text{m}$ arriba del agua. 

### **a. ¿Cuáles son las coordenadas de la posición inicial de la piedra?**

Siguiendo el empirismo, podemos decir que está en la coordenada:

$$
x_0 = (0, ~50\hat{\jmath})
$$

Pues inicialmente no se ha desplazado y se encuentra a una altura de 50 m.s.n.m.

### **b. ¿Cuáles son las componentes de la velocidad inicial de la piedra?**

Nuevamente, el ejercicio nos da la *velocidad horizontal* con la que es lanzada la piedra, que en este caso sería igual a $18 ~\text{m/s}$. Para la *velocidad vertical* tenemos que tomar en cuenta que viene dada por el producto del tiempo y la aceleración (la [[Fuerza de Gravedad|gravedad]] en este caso). Al estar trabajando en el instante $t=0$, la velocidad vertical es nula, por lo que tendremos que el vector de velocidad estará dado por:

$$
\vec{v}_o = \left(18\hat{\imath}, ~0\right)
$$

Contando con velocidad únicamente en el componente de las $x$.

### **c. ¿Cuál es el análisis del modelo adecuado para el movimiento vertical de la piedra?**

El movimiento vertical que tiene la piedra es un movimiento uniformemente acelerado por la gravedad; al estar el cuerpo sometido a una caída.

### **d. ¿Cuál es el análisis del modelo adecuado para el movimiento horizontal de la piedra?**

Análogamente para el movimiento horizontal, la piedra posee un movimiento con velocidad constante; al no haber resistencia con el aire o impulso durante el vuelo.


### **e. Escriba ecuaciones simbólicas para las componentes $x$ y $y$ de la velocidad de la piedra como función del tiempo**

Para la componente $x$ al ser un movimiento uniforme con velocidad constante; su función de velocidad será constante (limitada únicamente por su dominio, que es el tiempo de vuelo).

$$
v_x(t) = 18 ~\text{m/s}
$$

Para la velocidad en $y$, al ser un movimiento uniformemente acelerado y con velocidad inicial a 0; su formula será:

$$
v_y(t) = 9.8 ~\text{m/s$^2$} \cdot t
$$

### **f. Escriba ecuaciones simbólicas para la posición de la piedra como una función del tiempo**

Para este apartado es importante saber como va evolucionando la posición para cada una de las componentes ($x$ y para $y$ que en este ejemplo está relacionado a la altura de la piedra). Para describir la posición en $x$ tendremos el siguiente razonamiento:

$$
x_x(t) = 18 ~\text{m/s} \cdot t
$$

Y para la altura tendríamos la siguiente:

$$
x_h(t) = 50 ~\text{m} - \frac{1}{2}\cdot(9.8 ~\text{m/s$^2$}) \cdot t^2 ~\
$$

### **g. ¿Cuánto tiempo después de ser lanzada la piedra golpeó el agua debajo del acantilado?** 

Para calcular el tiempo en el que la piedra está en el aire y finalmente golpea el agua utilizaremos la siguiente ecuación:

$$
t = \sqrt{\frac{2 h}{g}}
$$

Reemplazando con nuestros valores:

$$
t = \sqrt{\frac{2(50)}{9.8}} \approx 3.2 \text ~{\text{s}}
$$

Por lo que el tiempo hasta la colisión con el agua será de aproximadamente 3.2 segundos.


### **h. ¿Con qué velocidad y ángulo de impacto pegó la piedra?** 

Para esto lo que realizaremos será calcular la velocidad final en la componente $y$, pues es la que es variable a lo largo del tiempo para luego calcular la velocidad total (resultante) y su ángulo de inclinación.

$$
v_{fy} = 9.8 \cdot 3.2 = 31.36 ~\text{m/s$^2$} 
$$

Y pues lo que haremos será calcular la velocidad total:

$$
\vec{v} = \sqrt{(18)^2 + (31.36)^2} = \sqrt{1307.4496}
$$
$$
\vec{v} \approx 36.15 ~\text{m/s}
$$

Finalmente calculamos el ángulo:

$$
\beta = \arctan{\left(\frac{31.36}{18}\right)}
$$
$$
\beta \approx60.14°
$$
---
## Punto 3.

Un atleta batea una pelota, conectada al extremo de una cadena, en un círculo horizontal. El atleta es capaz de girar la bola con una rapidez de 8.00 rev/s cuando la longitud de la cadena es 0.600 m. Cuando aumenta la longitud a 0.900 m, puede rotar la pelota solo 6.00 rev/s.
### **a. ¿Cuál es la rapidez de rotación que da la mayor rapidez a la pelota?** 

Para determinar cuál es la rapidez de rotación que produce la mayor rapidez tangencial, utilizamos la fórmula de la rapidez tangencial: 

$$ 
v = 2 \pi r f 
$$

Donde: 
- $v$ es la rapidez tangencial, 
- $r$ es el radio de la trayectoria ($r = 0.600 \, \mathrm{m}$ o $r = 0.900 \, \mathrm{m}$), 
- $f$ es la frecuencia de rotación en $\mathrm{rev/s}$. 

**Caso 1: Longitud $r = 0.600 \, \mathrm{m}$ y $f = 8.00 \, \mathrm{rev/s}$** 

$$
v_1 = 2 \pi (0.600)(8.00)
$$ 

$$
v_1 = 2 \pi (4.8)
$$

$$
v_1 \approx 30.16 \, \mathrm{m/s}
$$

**Caso 2: Longitud $r = 0.900 \, \mathrm{m}$ y $f = 6.00 \, \mathrm{rev/s}$** 

$$
v_2 = 2 \pi (0.900)(6.00)
$$

$$
v_2 = 2 \pi (5.4)
$$

$$
v_2 \approx 33.93 \, \mathrm{m/s}
$$

Por lo tanto, la rapidez de rotación que produce la mayor rapidez tangencial es $f = 6.00 \, \mathrm{rev/s}$ con $r = 0.900 \, \mathrm{m}$.
### **b. ¿Cuál es la aceleración centrípeta de la bola a $8.00 \, \mathrm{rev/s}$?** 

La aceleración centrípeta se calcula con la fórmula: 

$$
a_c = \frac{v^2}{r}
$$ 

De la parte (a), sabemos que para $f = 8.00 \, \mathrm{rev/s}$ y $r = 0.600 \, \mathrm{m}$: 

$$
v_1 \approx 30.16 \, \mathrm{m/s}
$$

Sustituimos los valores: 

$$
a_c = \frac{(30.16)^2}{0.600}
$$
$$
a_c \approx \frac{910.62}{0.600}
$$
$$
a_c \approx 1517.70 \, \mathrm{m/s^2}
$$

Por lo tanto, la aceleración centrípeta de la bola a $8.00 \, \mathrm{rev/s}$ es: 

$$
a_c \approx 1517.70 \, \mathrm{m/s^2}.
$$ 
### **c. ¿Cuál es la aceleración centrípeta en $6.00 \, \mathrm{rev/s}$?** 

De la parte (a), sabemos que para $f = 6.00 \, \mathrm{rev/s}$ y $r = 0.900 \, \mathrm{m}$:

$$
v_2 \approx 33.93 \, \mathrm{m/s}
$$

Sustituimos en la fórmula de la aceleración centrípeta: 

$$
a_c = \frac{v^2}{r}
$$
$$
a_c = \frac{(33.93)^2}{0.900}
$$
$$
a_c \approx \frac{1151.12}{0.900}
$$
$$
a_c \approx 1279.02 \, \mathrm{m/s^2}
$$

Por lo tanto, la aceleración centrípeta de la bola a $6.00 \, \mathrm{rev/s}$ es: 

$$
a_c \approx 1279.02 \, \mathrm{m/s^2}.
$$

---

## Punto 4

Un tren frena mientras entra a una curva horizontal cerrada, y frena de $90.0$ km/h a $50.0$ km/h en los $15.0$ s que tarda en cubrir la curva. El radio de la curva es de 150 m.

### a. Calcule la aceleración en el momento que la rapidez del tren alcanza 50.0 km/h. Suponga que continúa frenando a este tiempo con la misma rapidez. 

Lo primero convertimos las unidades de kilómetros por hora a metros por segundo para hacer los cálculos con medidas estandarizadas. Para esto, tenemos que recordar que $1 ~\text{km/h} \approx 0.2778 ~\text{m/s}$; por lo tanto:

$$
v_i = 90 \times 0.2778 = 25 ~\text{m/s}
$$
$$
v_f = 50 \times 0.2778 = 13.89 ~\text{m/s}
$$

El siguiente paso es calcular las aceleraciones (tangencial y centrípeta) para calcular al aceleración total; para la aceleración tangencial tenemos la siguiente fórmula:

$$
a_t = \frac{\Delta v}{\Delta t}
$$

Reemplazando:

$$
a_t = \frac{13.89 - 25}{15} = -\frac{11.11}{15}
$$
$$
a_t \approx -0.74 ~\text{m/s$^2$}
$$

Para la aceleración centrípeta tenemos la siguiente fórmula:

$$
a_c = \frac{v_f^2}{r}
$$

Reemplazando:


$$
a_c = \frac{(13.89)^2}{150} = \frac{192.9321}{150}
$$
$$
a_c \approx 1.286214 ~\text{m/s$^2$}
$$

Finalmente, calcularemos la aceleración total de la siguiente forma:

$$
a_T = \sqrt{a_c^2 + a_t^2} 
$$

Reemplazando:

$$
a_T = \sqrt{(1.286)^2 + (-0.74)^2} \approx \sqrt{2.2}
$$
$$
a_T = 1.48 ~\text{m/s$^2$}
$$

---
## Punto 5.
Un proyectil es disparado hacia arriba en una pendiente (ángulo de inclinación $\phi$) con una velocidad inicial $V_i$ a un ángulo $\theta_i$ con respecto a la horizontal ($\theta_i$ > $\phi$).

### **A. demuestre que el proyectil viaja una distancia $d$ hacia arriba de la pendiente**

$$d= \frac {2V_i^2 cos\theta_isen(\theta_i-\phi)}{gcos^2\phi}$$

Lo primero que hacemos es ver la posición del proyectil (x,y) en $t$.

$$x(t)= V_icos\theta_it$$
$$y(t)=V_isen\theta_it-\frac{1}{2}gt^2$$

Calculamos la pendiente del proyectil:

$Tan\varphi=\frac{y}{x}$, $y=tan\varphi (x)$

Ahora calculamos el tiempo($t$) de vuelo horizontal de $x(t)= V_icos\theta_it$ 
$$t=\frac {x}{V_icos\theta_i}$$
y reemplazamos esta ecuación en las ecuaciones iniciales de posición del proyectil:

$$y= V_isen\theta(\frac {x}{V_icos\theta_i})=\frac{1}{2}g(\frac{x}{V_icos\theta_i})^2$$
Simplificando queda que: $y=xtan\theta-\frac{gx^2}{2V_i^2cos^2\theta}$
Como tenemos $y=tan\varphi (x)$, reemplazamos en la ecuación $y= V_isen\theta(\frac {x}{V_icos\theta_i})=\frac{1}{2}g(\frac{x}{V_icos\theta_i})^2$, quedando:

$$xtan\varphi= xtan\theta-\frac{gx^2}{2V_i^2cos^2\theta}$$
se factoriza x:
$x(tan\theta_i-tan\varphi)=\frac{gx^2}{2V_i^2cos^2\theta_i}$

$$x=\frac{2V_i^2cos^2\theta_i(tan\theta_i-tan\varphi)}{g}$$

Ahora: $d=\frac{x}{cos\varphi}$

Reemplazando:

$$d = \frac{\frac{2 v_i^{2} \cos^{2}\theta \left( \tan \theta_i - \tan \varphi \right)}{g}}{\cos \varphi}$$

Tenemos que $tan\theta_i-tan\varphi= \frac{sen(\theta_i-\varphi)}{cos\theta_icos\varphi}$, como una identidad trigonométrica se reemplaza en la ecuación:
$$d=\frac{2V_i^2cos^2\theta(\frac{sen(\theta_i-\varphi)}{cos\theta_icos\varphi})}{gcos\varphi}$$

que simplificando da: $$d=\frac{2V_i^2cos\theta sen(\theta_i-\varphi)}{gcos^2\varphi}$$
Queda demostrado que el proyectil viaja a una distancia $d$ hacia arriba de la pendiente.

### **B. ¿para qué valor de $\theta_i$ es $d$ un máximo, y cuál es ese valor máximo?**

Tomamos del valor de $d$ el término $cos\theta sen(\theta-\varphi)$, y utilizando la identidad trigonométrica $sen(\theta_i-\varphi)= sen\theta_icos\varphi-cos\theta_isen\varphi$ 
y, $cos(\theta_i-\varphi)= cos\theta_i(sen\theta_icos\varphi-cos\theta_isen\varphi)$ 

Si expandimos tenemos que:
$$cos\theta sen(\theta-\varphi)= cos\varphi sen\theta cos\theta- sen\varphi cos^2\theta_i$$
Como nos piden el valor máximo de $\theta$ derivamos respecto a $\theta_i$:

$$\frac{d}{d\theta_i} (cos\varphi sen\theta_i cos\theta_i- sen\varphi cos^2\theta_i)= d$$
$cos\varphi sen\theta_i cos\theta_i$ TÉRMINO 1
$sen\varphi cos^2\theta_i$ TÉRMINO 2

- término 1(T1):
$$\frac{d}{d\theta}= cos\varphi sen\theta cos\theta=cos\varphi \frac{d}{d\theta}(sen\theta cos\theta)$$
$$\frac{d}{d\theta}(sen\theta cos\theta)= cos\theta \frac{d}{d\theta_i}(sen\theta)+sen\theta \frac{d}{d\theta}(cos\theta)$$
$$\frac{d}{d\theta_i}(sen\theta cos\theta)= cos\theta cos\theta- sen\theta sen\theta= cos^2\theta- sen^2\theta$$
$$\frac{d}{d\theta_i}T1= cos\theta (cos^2\theta- sen^2\theta)$$
Siendo este el resultado del término uno.

- término 2(T2):
$$T_2=-sen\varphi cos^2\theta$$
Se aplica la regla potencia derivada Cos:
$$\frac{d}{d\theta_i}(-sen\varphi cos^2\theta)= -sen\varphi \frac{d}{d\theta_i}() cos^2\theta_i$$
como sabemos que:
$$\frac{d}{d\theta_I}()cos^2\theta= 2cos\theta \frac{d}{d\theta}(cos\theta)$$
y como:
$$\frac{d}{d\theta_i}(cos\theta=-sen\theta)$$
entonces, $$\frac{d}{d\theta}(cos2\theta)=2cos\theta(-sen\theta)=-2cos\theta sem\theta$$
Sustituyendo en la derivada T2 tenemos:
$$\frac{d}{d\theta_i}t_2=-sen\varphi(-2cos\theta sen\theta)= 2en\varphi cos\theta sen\theta$$
Reescribiendo T1 y T2 tenemos que:
$$\frac{d}{d\theta_i}()cos\varphi sen\theta_I cos\theta_i- sen\varphi cos^2\theta_i= 0$$
$$\frac{d}{d\theta_i}d= cos\varphi(cos^2\theta- sen^2\theta)+ 2sen\varphi cos\theta sen\theta$$
igualando a 0 tenemos:

$$cos\varphi(cos^2theta-sen^2\theta) + 2sen\varphi cos\theta sen\theta=0$$
factorizando nos queda que:
$$cos^2\theta-sen^2\theta=cos(2\theta)$$
$$2cos\theta sen\theta= sen(2\theta)$$
sustituyendo nos queda que:
$$cos\varphi cos(2\theta)+ sen\varphi sen(2\theta)=0$$
tenemos:
$$cos\varphi cos(2\theta)+ sen\varphi sen(2\theta)= cos(2\theta-\varphi)$$

resolvemos para 0:
$$cos(2\theta-\varphi)=0 $$
entonces 
$$2\theta-\varphi=\frac{\pi}{2}+n\pi...$$
n=0
$$2\theta_i-\varphi=\frac{\pi}{2}$$
nos queda que el valor máximo de $\theta_i$ es:
$$\theta_i=\frac{\pi}{4}+\frac{\varphi}{2}$$


---

## Punto 6.

Un acelerómetro simple se construye dentro de un auto al colgar un objeto de masa $m$ de una cuerda de longitud $L$ fijada al techo del automóvil. Conforme el auto acelera el sistema cuerda-objeto hace un ángulo constante de $\theta$ con la vertical.

### **a. Obtener la aceleración del auto en términos de $\theta$ y demostrar que es independiente de $m$ y $L$**

Para realizar esto pensemos en este tipo de sistemas donde la masa forma una tensión con cuerda la cual llamaremos $\vec{T}$, y está asociada al peso del objeto que llamaremos $\vec{F}$.

Es decir, tenemos que:

$$
\vec{F} = m\cdot g
$$

Ahora bien, la tensión es un vector que forma el ángulo $\theta$ con la vertical y podemos descomponerlo en sus dos componentes de la siguiente manera:

$$
T_x = T \sin\theta
$$
$$
T_y = T \cos\theta
$$

Y pues asumiendo que el sistema cuerda-objeto se encuentra sin movimientos ni perturbaciones en su eje vertical, sino que su movimiento es enteramente en el horizontal podemos establecer que hay un equilibro para la vertical $y$ de la siguiente manera:

$$
T \cos \theta = m \cdot g
$$

Mientras que para la componente horizontal $x$ hay variaciones con respecto a la aceleración del automóvil:

$$
T \sin\theta = m \cdot a
$$


Ahora podemos dividir estas ecuaciones entre si para eliminar la tención, quedando lo siguiente:

$$
\frac{T \sin\theta }{T \cos\theta }=\frac{m \cdot a}{m \cdot g}
$$
$$
\frac{\sin\theta }{\cos\theta }=\frac{a}{g}
$$
$$
\tan\theta=\frac{ a}{g}
$$
De aquí podemos despejar la aceleración del automóvil quedando la siguiente expresión:

$$
a = \tan\theta \cdot g
$$

Y como podemos observar, la aceleración es independiente de $m$ y de $L$.


### **b. Determinar la aceleración del automóvil cuando $\theta = 23$°**

Aquí únicamente reemplazamos con el valor del ángulo y el valor de la gravedad:

$$
a = \tan 23° \cdot 9.8 ~\text{m/s$^2$}
$$
$$
a = 0.424 \cdot 9.8 ~\text{m/s$^2$}
$$
$$
a \approx 4.16 ~\text{m/s$^2$}
$$


---

## Punto 7
Dos bloques, cada uno de masa $m=3.50$ kg, cuelgan del techao de un elevador.

### **a. Si el elevador se mueve hacia arriba con aceleración $\vec{a}$ de magnitud 1.6, encuentre las tensiones $T_1$ y $T_2$**

Lo que tenemos que tener en cuenta es que en este caso la gravedad (o aceleración) final es de 
$9.8 - 1.6$, lo que corresponde a $8.2$. Pues hay aceleraciones en sentidos contrarios.

Por otro lado, la tensión $T_1$ está asociada a las dos masas, por lo que la tensión en este caso particular será igual a:

$$
T_1 = 2m \cdot 8.2
$$
$$
T_1 = 2(3.5) \cdot 8.2 = 57.4
$$

Mientras que para la tensión $T_2$ hay asociada una única masa, por lo que:

$$
T_2 = 3.5 \cdot 8.2 = 28.7
$$

### **b. Si las cuerdas pueden soportar una tensión máxima de 85 N, ¿qué aceleración máxima puede tener el ascensor antes de que las cuerdas se rompan?**

Para hacer esto, establecemos que la $T_1$ será igual a 85 N, para ver a que aceleración tendría que ir el ascensor para evitar que se rompa.

$$
85 = 2m \cdot (g +a)
$$
$$
85 = 2(3.5) \cdot (9.8 +a)
$$
$$
85 = 7 \cdot (9.8 +a)
$$
$$
\frac{85}{7} =  9.8 +a
$$
$$
a = \frac{85}{7} -9.8 
$$
$$
a \approx 2.34 ~\text{m/s$^2$}
$$

Por lo que el ascensor tendría que ir descendiendo y tener una aceleración máxima de 2.34 m/s$^2$. 


---

## Punto 8
Dos bloques de masa $m_1 = 3.50 ~\mathrm{kg}$ y $m_2 = 8.00 ~\mathrm{kg}$ están conectados mediante una cuerda sin masa que pasa por una polea sin fricción. Los planos inclinados carecen de fricción y forman un ángulo de $35.0^\circ$ con la horizontal.

### **a. Encuentre la magnitud de la aceleración de cada bloque.**

Para resolver este problema, consideremos las fuerzas que actúan sobre cada bloque:

- Para el bloque $m_1$, las fuerzas son:
  1. El componente de la fuerza gravitatoria a lo largo del plano inclinado: $F_{\text{g1}} = m_1 g \sin \theta_1$.
  2. La tensión en la cuerda: $T$.

  La ecuación de movimiento para $m_1$ es:
  $$
  T - m_1 g \sin \theta_1 = m_1 a
  $$

- Para el bloque $m_2$, las fuerzas son:
  1. El componente de la fuerza gravitatoria a lo largo del plano inclinado: $F_{\text{g2}} = m_2 g \sin \theta_2$.
  2. La tensión en la cuerda: $T$.

  La ecuación de movimiento para $m_2$ es:
  $$
  m_2 g \sin \theta_2 - T = m_2 a
  $$

Donde:
- $g = 9.8 \, \mathrm{m/s^2}$ es la aceleración de la gravedad.
- $a$ es la aceleración común para ambos bloques.

Sumamos las dos primeras ecuaciones para eliminar $T$:
$$
m_2 g \sin \theta_2 - m_1 g \sin \theta_1 = (m_1 + m_2)a
$$

Despejamos $a$:
$$
a = \frac{m_2 g \sin \theta_2 - m_1 g \sin \theta_1}{m_1 + m_2}
$$

Sustituimos los valores:
$$
a = \frac{(8.00)(9.8)(\sin 35.0^\circ) - (3.50)(9.8)(\sin 35.0^\circ)}{3.50 + 8.00}
$$

Calculamos:
$$
\sin 35.0^\circ \approx 0.5736
$$
$$
a = \frac{(8.00)(9.8)(0.5736) - (3.50)(9.8)(0.5736)}{3.50 + 8.00}
$$
$$
a = \frac{(45.01) - (19.68)}{11.50}
$$
$$
a \approx \frac{25.33}{11.50}
$$
$$
a \approx 2.20 \, \mathrm{m/s^2}
$$

Por lo tanto, la magnitud de la aceleración de cada bloque es:
$$
a \approx 2.20 \, \mathrm{m/s^2}.
$$


### **b. Encuentre la tensión en la cuerda.**

Sustituyendo el valor de $a$ en la ecuación:
$$
T = m_1 g \sin \theta_1 + m_1 a
$$

Sustituimos los valores:
$$
T = (3.50)(9.8)(\sin 35.0^\circ) + (3.50)(2.20)
$$
$$
T = (3.50)(9.8)(0.5736) + (3.50)(2.20)
$$
$$
T = (19.68) + (7.70)
$$
$$
T \approx 27.38 \, \mathrm{N}.
$$

Por lo tanto, la tensión en la cuerda es:

$$
T \approx 27.38 \, \mathrm{N}.
$$
