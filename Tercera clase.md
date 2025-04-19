## Apuntes segundo corte
# Clase 2 : Sistemas Rotacionales aplicados al Trabajo, Energia y Potencia.
# Nombre: Kevin Nicolas Perez Tobar
# Curso: M6A

# SISTEMAS ROTACIONALES 
## 1. Introducción
En general, los sistemas rotacionales estan relacionados con el modelado de sistemas mecancicos ya que involucran caracteristicas similares, son un fenomeno mecanico que por naturaleza del movimiento cambia, ahora es un movimiento angular.Estos juegan un papel importantes, ya que van variando en el tiempo, se caracterizan por tener rotacion y movimiento. Sus magnitudes fisicas estan relaciondas con momentos de Inercia, velocidad angular,y demas. Este sistema se caracteriza por tener diferentes comportamientos y siempren se van a presentar errores de exactitud, por razones teoricas o practicas, por lo tanto estos sistemas estan asociados con el concepto de grados de Libertad.

# 2. Resumen
Exponiendo esta teoria, ya vista vamos a explicar su concepto, partiendo del modelado del sistema dinamico, teniendo en cuenta su Diagrama de Cuerpo Libre, su interpretación usando formulas, y conceptos fisicas, que nos llegran a entender su significado. Por otro lado vamos a estudiar el concepto de Trabajo, Energia y Potencia donde exponeremos casos con problemas, teniendo en cuenta sus variables, ecuaciones, y analizis para poder comprobar si es necesario usar los grados de Libertad.


# 3. Definiciones
🔑 Sistemas Rotacionales: Los sistemas Rotacionales son un fenomeno mecanico, ya que estan relacionados con el concepto de Rotación. Estos modelos giran alrededor de un obejto y se aplican en robotica, control y mecanica.

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/98d69492801bb8a1894cc1039df89f9a485901db/Build/Figura-33-Sistema-rotacional-masa-resorte-amortiguador.png" width= "300">
</div>
Fig. 1 Imagen de concepto Sistema Rotacional

## 3.1 Leyes Comparables al movimiento Lineal 
# Segunda ley de Newton para la rotación
Si, sobre un cuerpo rígido actúa más de un torque en torno a un eje fijo, la suma de los torques es igual al momento de inercia por la aceleración angular:

$$\sum_i \tau_i = I \alpha$$

Angulo  de Torsión

🔑 Definición:  es un parámetro que describe la deformación rotacional que experimenta un objeto debido a la aplicación de un par de torsión (o momento torsional).

$$FR = k \cdot \varphi \quad \rightarrow \quad \varphi \text{ es ángulo de torsión}$$

Velocidad Angular

🔑 Definición: La velocidad angular es una magnitud física que describe el cambio de ángulo con respecto al tiempo, en el movimiento circular de un objeto.

$$F_F = b \cdot \frac{d\varphi}{dt} \quad \rightarrow \quad \frac{d\varphi}{dt} \text{ es la velocidad angular}$$

Momento de Inercia

🔑 Definición: El momento de inercia es una propiedad física de los objetos que mide su resistencia a los cambios en su estado de rotación alrededor de un eje. 


$$T = J \cdot \frac{d^2\varphi}{dt^2} \quad \rightarrow \quad J \text{ es el momento de inercia}$$

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/0908a0acdccdc2281b6dda5a65f1886a6c3df549/Build/Captura%20de%20pantalla%202025-04-19%20065029.jpg" width="300">
</div>
Fig 2 Imagen del sistema Rotacional

$$ k= constante Elastica $$
Diagrama de Bloques
Entrada → T(t) → Salida
F(t) → Entrada
T(t) → Salida

###  Caso General

$$T = F \times R = I \times \alpha \quad \text{(aceleración angular)}$$

### Particular

$$T(t) = F \times R = I \times \alpha \quad \text{(aceleración angular)}$$

$$T(t) = k \times \theta(t) - b \times \dot{\theta}(t) \quad \dot{\theta}(t) = J \times \frac{d^2 \theta(t)}{dt^2}$$


$$T = F \times R = J \times \alpha \quad \text{(aceleración angular)}$$
### Particular

$$T(t) = F \times R = J \times \alpha \quad \text{(aceleración angular)}$$

$$T(t) = k \times \theta(t) - b \times \frac{d \theta(t)}{dt} = J \times \frac{d^2 \theta(t)}{dt^2}$$

## Trabajo, Energia y Potencia 

# Definiciones
🔑 Trabajo: Es la medida de ceunta fuerza se realiza con esfuerzo.
Su formula general esta representada por: 

Fórmulas

$$
\mathbf{F} = m \times a
$$

🔑 Energia: Capacidad para realizar un trabajo.
Se divide en dos tipos de enrgtia, las cuales son: Energia Cinetica y Energia Potencial.

🔑 Energia Potencial: En los sistemas mecancanicos le energia potencial cambia de acuerdo a la pocision con respecto a la referencia. 

Cálculo de la energía
$$
E = F \times \Delta x
$$

 Fuerza aplicada
$$
F = m \times a
$$





