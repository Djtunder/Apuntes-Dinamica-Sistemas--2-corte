## Apuntes segundo corte
# Clase 3 : Sistemas Rotacionales aplicados al Trabajo, Energia y Potencia.
# Nombre: Kevin Nicolas Perez Tobar
# Curso: M6A

# SISTEMAS ROTACIONALES 
## 1. Introducción
En general, los sistemas rotacionales estan relacionados con el modelado de sistemas mecancicos ya que involucran caracteristicas similares, son un fenomeno mecanico que por naturaleza del movimiento cambia, ahora es un movimiento angular.Estos juegan un papel importantes, ya que van variando en el tiempo, se caracterizan por tener rotacion y movimiento. Sus magnitudes fisicas estan relaciondas con momentos de Inercia, velocidad angular,y demas. Este sistema se caracteriza por tener diferentes comportamientos y siempren se van a presentar errores de exactitud, por razones teoricas o practicas, por lo tanto estos sistemas estan asociados con el concepto de grados de Libertad.

# 2. Resumen
Exponiendo esta teoria, ya vista vamos a explicar su concepto, partiendo del modelado del sistema dinamico, teniendo en cuenta su Diagrama de Cuerpo Libre, su interpretación usando formulas, y conceptos fisicas, que nos llegran a entender su significado. Por otro lado vamos a estudiar el concepto de Trabajo, Energia y Potencia donde exponeremos casos con problemas, teniendo en cuenta sus variables, ecuaciones, y analizis para poder comprobar si es necesario usar los grados de Libertad.

# 3. Objetivos


# 4. Definiciones
🔑Sistemas Rotacionales: Los sistemas Rotacionales son un fenomeno mecanico, ya que estan relacionados con el concepto de Rotación. Estos modelos giran alrededor de un obejto y se aplican en robotica, control y mecanica.

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

5.#Fórmulas

$$\mathbf{F} = m \times a$$

🔑5.1 Energia: Capacidad para realizar un trabajo.
Se divide en dos tipos de enrgtia, las cuales son: Energia Cinetica y Energia Potencial.

🔑5.2 Energia Cinetica: La energía cinética es la energía que posee un objeto debido a su movimiento. Se calcula utilizando la fórmula:

$$E = \frac{1}{2} \times m \times v^2$$

🔑 5.3 Energia Potencial: En los sistemas mecancanicos le energia potencial cambia de acuerdo a la pocision con respecto a la referencia. 

$$U = \int_0^h mg \, dx = mgh$$

Cálculo de la energía

$$E = F \times \Delta x$$

# Importante
Solamente los elementos de inercia pueden almacenar energía cinética
Un cambio en la energía cinética es el trabajo realizado sobre una masa por la aplicación de una fuerza que representa este sistema.

# 6. Formulas y Ecuaciones 

$$T = \frac{1}{2} mv^2$$
$$T = \frac{1}{2} J \dot{\theta}^2$$

# 6.1 Demostración de la Energia Cinetica

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

 # 6.2 Potencia en el Amortiguador
 El Resorte, el amortiguador y la masa son los bloque funcionales que representan los sistemas mecanicos donde las fuerzas y desplazamientos lineales que estan representados por fuerzas y desplazamientos. Hay que tener en cuenta que tanto los amortiguadores y los resortes se oponen al movimiento. Entonces esto se representa de la siguiente manera.

 <div align="center">
 <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/a97c1323e79dc9bc381c4bdbb9c41176ce49c0ce/Build/potencia%20en%20amortiguador.png" width="300">
 </div>

 Fig 3. Representacion de Potencia en el amortiguador 
$$ P = \frac{dW}{dt} = F \frac{dx}{dt} = F \dot{x} = kx \dot{x} $$

Sabiendo que:

$$ P = kx \dot{x} = \dot{U} $$

# 6.3 Potencia almacenda en los Amortiguadores
Con un Amortiguador Giratorio un disco gira en un fluido resistivo T, es proporcional a la velocidad angular w y dado que la velocidad angular es la tasa de cambio del desplazamiento angular, es decir:

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/c06ccd0cb23da40ef50a0a685e2bc2fa28828cb9/Build/amortiguador%2019.jpg" width="300">
</div>

# 7. Tablas

| Momento de Inercia        | Ecuación descriptiva                                       | Energía de Potencia almacenada |
|---------------------------|------------------------------------------------------------|--------------------------------|
| **Energía Cinética**       | $$E = \frac{1}{2} \times m \times v^2$$                   | $$E = \frac{1}{2} \times J \times v^2$$ |
| **Energía Potencial**     | $$E = mgh$$                                               | $$E = \frac{1}{2} \times k \times x^2$$ |
| **Amortiguador Translacional** | $$F_{\text{amortiguador}} = -c \cdot v$$                 | $$P = c \times v^2$$          |
| **Amortiguador Rotacional** | $$T_{\text{amortiguador}} = c \cdot \theta \cdot v$$      | $$P = c \times \omega^2$$     |

Figura 4.1 Tabla de Formulas- W.Bolton
# Sistemas Conservativos
Los Sistemas conservativos es toda la energia resultante de la Energia Potencial y la Energia Cinetica. Que hace parte del sistema en el trabajo mecanico, y no disipa la energia.
Se puede definir como:

$$(T+U)= W$$

$$T+U= constante$$

# 8. Ejemplo 1 💡

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

# Ejemplo 2 💡

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

$$U = mg(x_0 - x) + \frac{1}{2}k(\delta + x)^2$$

Desarrollando:

$$
\begin{align*}
U &= mgx_0 - mgx + \frac{1}{2}k\delta^2 + k\delta x + \frac{1}{2}kx^2 \\
  &= mgx_0 + \frac{1}{2}k\delta^2 - (mg - k\delta)x + \frac{1}{2}kx^2
\end{align*}
$$

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

# Casos frecuentes

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/53de396c6629f758b7847e4dbec54a348d60c87b/Build/Imagen1.png" width="300">
</div>

$$m \ddot{x} + \frac{2}{3} k x = 0$$

$$J = \text{depende de la figura}$$

$$\frac{1}{2} m x^2 + \frac{1}{2} m \left(\frac{dx}{dt}\right)^2 + \frac{1}{2} k x^2$$

$$\frac{3}{4} m x^2 + \frac{1}{2} k x^2 = \text{constante}$$


2. Trenes de Engranajes, Palancas y Bandas
<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/6c871e477acf0a51c78fb0111585621418b750bf/Imagen5.jpg" witdh="300">
</div>

$$r_1 N_1 = r_2 N_2 \quad \Rightarrow \quad \dot{\theta}_1 = \dot{\theta}_2$$

$$T_1 = \frac{N_1}{N_2} T_2$$

3. Movimiento de Rotación de una Masa Resorte
<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/a66cd8eef96604d5af09ae3be24cb561d0340bd6/Build/Imagen2.jpg" width="300">
</div>
   
$$T_m - T_r = B m \frac{d \theta}{dt} = J m \frac{d^2 \theta}{dt^2}$$

$$T_1 = M r^2 \frac{d^2 \theta}{dt^2}$$

$$T_m - M r^2 \frac{d^2 \theta}{dt^2} = B m \frac{d \theta}{dt}$$

4. Momento de Inercia

$$J = \frac{1}{2} m R^2 \quad \text{y} \quad x = R \theta$$

$$T + U = \frac{1}{2} m x^2 + \frac{1}{2} J \left( \frac{d \theta}{dt} \right)^2$$

6. 💡 Ejemplo - Sistema Mecánico

<div align= "center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/c3ad10f7e64121731514795f4f5b27b3efbcdb2c/Build/Imagen4.jpg" width="300"> 
</div>

$$T = \frac{1}{2} m x^2 + \frac{1}{2} J \left( \frac{d x}{dt} \right)^2$$

$$\text{Energía Potencial} \quad U = \frac{1}{2} k x^2$$

$$J = \frac{1}{2} m R^2$$

# 📚 8. Ejercicios Resueltos

4.10 El Diagrama esquemático de un sistema motor-carga se presenta en la Fig. p-101. Se definen los siguientes parámetros y variables:
𝑇𝑚(𝑡)Tm(t) es el par del motor, 𝜔𝑚(𝑡)ω m(t) es la velocidad angular, 𝜃𝑚(𝑡)θ m(t) es el desplazamiento del motor, 𝑤𝐿(𝑡)w L
​(t) es la velocidad de carga, 𝜃𝐿(𝑡)θL(t) es el desplazamiento de la carga, 𝑘 k es la constante del resorte torsional, 𝐽𝑚 Jm​
es la inercia del motor, 𝐵𝑚 Bm es el coeficiente de fricción viscosa del motor, y 𝐵𝐿 BL es el coeficiente de fricción viscosa de la carga.

Solución

<div align= "center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/485372a8724eb7e2e58dbc5aaedd725b00ce7406/Build/motor%20carga%20jl.jpg" width="300">
</div>
- \( T_m(t) \): es el par del motor.  

- \( \omega_m(t) \): es la velocidad angular del motor.  

- \( \theta_m(t) \): es el desplazamiento del motor.  

- \( w_L(t) \): es la velocidad de carga.  

- \( \theta_L(t) \): es el desplazamiento de la carga.  

- \( k \): la constante del resorte torsional.  

- \( J_m \): es la inercia del motor.  

- \( B_m \): es el coeficiente de fricción viscosa del motor.  

- \( B_L \): es el coeficiente de fricción viscosa de la carga.


$$J = \frac{1}{2} M r^2$$

$$T(t) = J \cdot \alpha(t)$$

$$T(t) = J \cdot \frac{d \omega(t)}{dt} = J \cdot \frac{d^2 \theta(t)}{dt^2}$$

Por Ejemplo:

$$T(t) = k \cdot \theta(t)$$

Por Fricción:

$$T(t) = B \cdot \frac{d \theta(t)}{dt}$$

Ecuación del Sistema:
$$
$$\sum F = J_m \cdot \alpha$$
$$J \cdot \alpha(t) - B \cdot \frac{d \theta(t)}{dt} - k \cdot \theta(t) = 0$$

Sabemos que:

$$J \cdot \alpha(t) = B m \cdot \frac{d \theta(t)}{dt} + k \cdot \theta(t) = 0$$

$$J \cdot \alpha(t) = J_m \cdot \frac{d \omega(t)}{dt} + J_m \cdot \frac{d^2 \theta(t)}{dt^2}$$

**Coeficiente del resorte:**

$$k \cdot \theta(t) = k \left[ \Delta m(t) - \Delta \theta(t) \right]$$

**Coeficiente de fricción:**

$$B_m \cdot \frac{d \Delta m(t)}{dt}$$

**Ecuación Final:**

$$J_m \cdot \frac{d^2 \Delta m(t)}{dt^2} = - B_m \cdot \frac{d \Delta m(t)}{dt} - k \left[ \Delta m(t) - \Delta \theta(t) \right] + T_m(t)$$

Resouesta: La Ecuacion Final del Motor rwswpecto al motor- union del sistema es de: $$J_m \cdot \frac{d^2 \Delta m(t)}{dt^2} = - B_m \cdot \frac{d \Delta m(t)}{dt} - k \left[ \Delta m(t) - \Delta \theta(t) \right] + T_m(t)$$

# 📚Ejercicio 2
La imagen que muestra de la figura 4.7 muestra un sistema con Tren de Engranajes con una relacion de engranajes n= N1/N2. El par de motor es Tm(t), y T2(t) representa el par de carga.

a) Encuentre una relacion de Engranjes optima n,tal que la aceleracion de la carga 
$$\Delta(L) = \frac{d(\theta(t))}{dt}$$

Solucion


Consideramos las siguientes ecuaciones para el sistema motor-carga:

\subsection{Ecuaciones Generales}
\begin{align*}
    \sum M &= J \cdot \ddot{\theta} \\
    \theta_1 &= \frac{\theta_m}{n} \\
    w_1 &= \frac{w_m}{n} \quad (w = \frac{d\theta}{dt})
\end{align*}

Derivando nuevamente respecto al tiempo, obtenemos la relación entre las aceleraciones angulares:

\subsection{Ecuaciones de Aceleración}
\begin{align*}
    \text{Motor: } J_m \cdot a_m &= T_m(t) - T_L(t) \\ 
    \text{Carga: } a_1 &= \frac{a_m}{n^2} = \frac{T_L(t)}{J_t + T_L(t)}
\end{align*}

Donde \( T_1 \) y \( T_2 \) son los pares transmitidos a través de los engranajes. Debido a la transmisión ideal (sin pérdidas):

\subsection{Relación de Pares}
$$
T_1 = n \cdot T_2
$$

## 9. Conclusiones
   1. Los sistemas mecanicos se pueden representar con modelos matematicos que permiten encontrar una funcion que modele dicho sistema.
   2. Las Ecuaciones Difereanciales permiten solucionar cualquier sistema para describir el movimiento en cualquier instante de tiempo
   3. La Energia Cinetica, La Energia Potencial y el Concepto del Trabajo, son sistemas similiares a los sitemas masa-resorte pero sus ecuaciones y modelos cambian en el dominio del tiempo.

## 10. Referencias
   
Jorge Eduardo Cote Ballesteros. (2025). Sistemas Rotacionales aplicados al trabajo ETITC.

[Ingeniería de Control - W Bolton Segunda Edición]: Este es el texto que se mostrará como el enlace.
(https://dn790007.ca.archive.org/0/items/IngenieraDeControlBolton/Ingenier%C3%ADa%20de%20Control%20-%20Bolton.pdf): 
[Sistemasde Control Automático de Benjamin Cubo

https://drive.google.com/file/d/1kDlTA1YEpmfSzMMv44MKI4-2bzA9wbDg/view


 


   



