## Apuntes segundo corte
# Clase 3 : Sistemas Rotacionales aplicados al Trabajo, Energia y Potencia.
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

🔑 Energia Cinetica: La energía cinética es la energía que posee un objeto debido a su movimiento. Se calcula utilizando la fórmula:

$$E = \frac{1}{2} \times m \times v^2$$

🔑 Energia Potencial: En los sistemas mecancanicos le energia potencial cambia de acuerdo a la pocision con respecto a la referencia. 

$$U = \int_0^h mg \, dx = mgh$$

Cálculo de la energía

$$E = F \times \Delta x$$

# Importante
Solamente los elementos de inercia pueden almacenar energía cinética
Un cambio en la energía cinética es el trabajo realizado sobre una masa por la aplicación de una fuerza que 
# Formulas

$$T = \frac{1}{2} mv^2$$
$$T = \frac{1}{2} J \dot{\theta}^2$$

# Demostración de la Energia Cinetica

$$\Delta T = \Delta W = \int_{x_1}^{x_2} F \, dx = \int_{t_1}^{t_2} F \frac{dx}{dt} dt$$
$$ = \int_{t_1}^{t_2} Fv \, dt = \int_{t_1}^{t_2} m v v \, dt = \int_{v_1}^{v_2} m v \, dv$$
$$ = \frac{1}{2} m v_2^2 - \frac{1}{2} m v_1^2$$
$$\Delta T = \frac{1}{2} J \dot{\theta}_2^2 - \frac{1}{2} J \dot{\theta}_1^2$$

🔑 Potencia: Es la realización del trabajo respecto al tiempo:

$$ P = \frac{dW}{dt} $$

$$ \text{Potencia media} = \frac{\text{Trabajo realizado}}{(t_2 - t_1) \, \text{segundos}} $$  

# Energía potencial en un resorte
🔑 Definición: Es el trabajo neto hecho sobre él por las fuerzas que actúan en sus extremos cuando es comprimido o estirado

$$ U = \int_0^x F \, dx = \int_0^x kx \, dx = \frac{1}{2} kx^2 $$

De su forma general

$$ \Delta U = \int_{x_1}^{x_2} F \, dx = \int_{x_1}^{x_2} kx \, dx = \frac{1}{2} kx_2^2 - \frac{1}{2} kx_1^2 $$

 # Potencia en el Amortiguador
 El Resorte, el amortiguador y la masa son los bloque funcionales que representan los sistemas mecanicos donde las fuerzas y desplazamientos lineales que estan representados por fuerzas y desplazamientos. Hay que tener en cuenta que tanto los amortiguadores y los resortes se oponen al movimiento. Entonces esto se representa de la siguiente manera.

 <div align="center">
 <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/a97c1323e79dc9bc381c4bdbb9c41176ce49c0ce/Build/potencia%20en%20amortiguador.png" width="300">
 </div>
 
$$ P = \frac{dW}{dt} = F \frac{dx}{dt} = F \dot{x} = kx \dot{x} $$

Sabiendo que:

$$ P = kx \dot{x} = \dot{U} $$

# Potencia almacenda en los Amortiguadores
Con un Amortiguador Giratorio un disco gira en un fluido resistivo T, es proporcional a la velocidad angular w y dado que la velocidad angular es la tasa de cambio del desplazamiento angular, es decir:

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/c06ccd0cb23da40ef50a0a685e2bc2fa28828cb9/Build/amortiguador%2019.jpg" width="300">
</div>

# 4. Tablas

| Momento de Inercia        | Ecuación descriptiva                                       | Energía de Potencia almacenada |
|---------------------------|------------------------------------------------------------|--------------------------------|
| **Energía Cinética**       | $$E = \frac{1}{2} \times m \times v^2$$                   | $$E = \frac{1}{2} \times J \times v^2$$ |
| **Energía Potencial**     | $$E = mgh$$                                               | $$E = \frac{1}{2} \times k \times x^2$$ |
| **Amortiguador Translacional** | $$F_{\text{amortiguador}} = -c \cdot v$$                 | $$P = c \times v^2$$          |
| **Amortiguador Rotacional** | $$T_{\text{amortiguador}} = c \cdot \theta \cdot v$$      | $$P = c \times \omega^2$$     |

# Sistemas Conservativos
Los Sistemas conservativos es toda la energia resultante de la Energia Potencial y la Energia Cinetica. Que hace parte del sistema en el trabajo mecanico, y no disipa la energia.
Se puede definir como:

$$(T+U)= W$$

$$T+U= constante$$

# 5. Ejercicios

1. Enunciado:

Considere un sistema masa-resorte compuesto por una masa 𝑚conectada a un resorte de constante k como se muestra en la figura. El resorte está fijado a una pared y la masa 
m puede moverse a lo largo de la dirección 𝑥. La energía cinética 𝑇 y la energía potencial 𝑈 del sistema están dadas por las siguientes expresiones.

La energía cinética
T de la masa es:

$$T= \frac{1}{2}\times m \times v^2$$

es la velocidad de la masa.

La energía potencial 
𝑈 almacenada en el resorte es:

$$ U= \frac{1}{2}\times k\times x^2$$

donde 
𝑥
x es la elongación o compresión del resorte con respecto a su posición de equilibrio.

2. Ahora sabemos que segun la ley de sistemas conservativos debemos sumar la energia potencial y la energia cinetica

   $$W= (\frac{1}{2}\times m \times v^2)+ (\frac{1}{2}\times k\times x^2)$$

 3. Despues derivamos toda la energia total
    
Entonces tenemos:

$$Derivando esta expresión con respecto al tiempo \( t \):

$$\frac{d}{dt} (T + U) = \frac{d}{dt} \left( \frac{1}{2} m \dot{x}^2 + \frac{1}{2} k x^2 \right)$$

Esto nos da:

$$\frac{d}{dt} (T + U) = m \dot{x} \ddot{x} + k x \dot{x}$$

### Paso 2: Factorización

Al factorizar \( \dot{x} \), obtenemos:

$$\frac{d}{dt} (T + U) = \dot{x} (m \ddot{x} + k x)$$

 Paso 3: Ecuación de movimiento

De acuerdo con el principio de conservación de energía o la ecuación de movimiento del sistema, sabemos que:

$$\frac{d}{dt} (T + U) = 0$$

Esto implica que:

$$\dot{x} (m \ddot{x} + k x) = 0$$

Ya que \( \dot{x} \) no puede ser cero en todo momento (excepto en puntos específicos donde la velocidad es cero), debemos tener:

$$m \ddot{x} + k x = 0$$

# Ejemplo 2

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/60f471af7e3ed7eeb7304d63b049fd9158a87bdc/Build/Imagen3.jpg" width="300">
</div>

Solucion

# Análisis de la Energía en un Oscilador Armónico

## Paso 1: Energía Potencial Inicial

La energía potencial inicial del sistema es:

$$
U_0 = mgx_0 + \frac{1}{2}k\delta^2
$$

Donde:

- \( m \): masa  
- \( g \): gravedad  
- \( x_0 \): posición inicial  
- \( \delta \): elongación inicial del resorte  
- \( k \): constante del resorte  

---

## Paso 2: Energía Potencial Total en Función de \( x \)

La energía potencial total es:

$$
U = mg(x_0 - x) + \frac{1}{2}k(\delta + x)^2
$$

Desarrollando:

$$U &= mgx_0 - mgx + \frac{1}{2}k\delta^2 + k\delta x + \frac{1}{2}kx^2 \\
  &= mgx_0 + \frac{1}{2}k\delta^2 - (mg - k\delta)x + \frac{1}{2}kx^2$$

## Paso 3: Energía Cinética

La energía cinética está dada por:

$$T = \frac{1}{2}m\dot{x}^2$$

## Paso 4: Energía Total del Sistema

La energía total es:

$$T + U = \frac{1}{2}m\dot{x}^2 + U_0 + \frac{1}{2}kx^2 = \text{constante}$$

Recordando que:

$$U_0 = mgx_0 + \frac{1}{2}k\delta^2$$


## Paso 5: Derivada de la Energía Total

Derivando la energía total con respecto al tiempo:

$$\frac{d}{dt}(T + U) = \frac{d}{dt} \left( \frac{1}{2}m\dot{x}^2 + \frac{1}{2}kx^2 \right)$$

Aplicando la regla de la cadena:

$$\frac{d}{dt}(T + U) = m\dot{x}\ddot{x} + kx\dot{x}$$

Factorizando:

$$(m\ddot{x} + kx)\dot{x} = 0$$

## Paso 6: Ecuación de Movimiento

Para que se conserve la energía, debe cumplirse:

$$m\ddot{x} + kx = 0$$

Esta es la ecuación del movimiento armónico simple.




