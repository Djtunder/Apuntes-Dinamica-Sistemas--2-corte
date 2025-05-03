## Apuntes segundo corte
# Clase 5 : Amplificadores Operacionales y Sistemas Hidraulicos. 
# Nombre: Kevin Nicolas Perez Tobar
# Curso: M6A

 ## 1. Introducción
 Circuitos con Aplificadores operacionales

 Los Amplificadores Operacionales se utlizan en las Leyes de kirchoff, y en circuitos electricos. Se aplican en la automatización y control de procesos. Los sistemas hidráulicos utilizan líquidos como medio para transmitir energía y controlar mecanismos,os sistemas hidráulicos se basan en el principio de que un fluido incomprensible, generalmente aceite, puede transmitir fuerza y energía a través de tuberías y componentes. Estos sistemas permiten generar movimientos de precisión y gran fuerza con relativamente poco esfuerzo. 

## 2. Resumen
   
En   la   clase se vio las caracteriticas de los   fenómenos físicos  reales por  medio de amplificadores   operacionales   formando   circuitoselectrónicos   dinámicos,   permitiendo   conocer   laimportancia   de   los   circuitos   electrónicos   a   la   hora  desimular un sistema, aplicando leyes de Khirchoff. En la segunda parte de la clase vimos los sistemas de Tanques, sus ecuaaciones y sus diferentes caracteriticas cuando estan interconectados entre si, aplicando ecuaciones diferenciales.

## 3. Objetivos
3.1 Objetivos Generales

3.11 Objetivos Generales
3.12 Comprender y analizar los principios fundamentales de los sistemas hidráulicos y su aplicación en la automatización y control de procesos, con el fin de diseñar soluciones mecatrónicas eficientes que integren actuadores hidráulicos en sistemas dinámicos.

3.13 Estudiar el funcionamiento y las aplicaciones de los amplificadores operacionales, con el propósito de emplearlos en el diseño de circuitos electrónicos para el control preciso de señales, y su integración en sistemas de control de maquinaria y actuadores hidráulicos.

3.14 Objetivos Específicos
3.14.1  Desarrollar la capacidad para modelar y simular sistemas hidráulicos, utilizando ecuaciones de control y análisis dinámico, con el fin de optimizar el diseño de mecanismos hidráulicos en sistemas automatizados.

3.15.1 Diseñar y aplicar circuitos electrónicos utilizando amplificadores operacionales, para la amplificación de señales y el control de sistemas mecatrónicos, mejorando la precisión y eficiencia en sistemas de retroalimentación y control.

 ## 4. Definiciones
   4.1 🔑 Amplificador Operacional: Es un componente electrónico de propósito general que amplifica la diferencia de voltaje entre dos entradas, conocidas como entrada no inversora (+) y entrada inversora (-). Los amplificadores operacionales son elementos clave en una gran cantidad de circuitos electrónicos debido a su versatilidad y características de alta ganancia.

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/1216cc60d2708ca1ce8c709a64a24b948c062c70/Build/amplificador%20operacional.png" width="300"> 
</div>
Figra 4.1 Imagen de la estructura de un amplificador operacional 

 ## 4.2 Caracteristicas de los Amplificadores Operacionales

## 4.21 Entradas:

Entrada no inversora (+ Vin): La señal que se introduce en esta entrada no cambia de signo en la salida. Es decir, si la señal de entrada se aumenta, la salida también lo hace de manera proporcional.

Entrada inversora (- Vin): En esta entrada, la señal de entrada se invierte en la salida. Si la señal de entrada aumenta, la salida disminuirá en la misma proporción, pero con signo opuesto.

## 4.22 Suministro de Voltaje (Vs):

Los amplificadores operacionales requieren una alimentación positiva (+Vs) y negativa (-Vs) para funcionar correctamente, lo que les permite amplificar señales dentro de un rango determinado. La salida no puede exceder estos valores de voltaje.

## 4.23 Salida (Vout):

La salida de un amplificador operacional se basa en las señales de las entradas, multiplicadas por el factor de ganancia del amplificador (dependiendo de la configuración del circuito). La señal puede ser positiva o negativa dependiendo de las entradas y la configuración del amplificador (inversora o no inversora).

## 4.24 Configuración del amplificador:

El amplificador operacional puede usarse en diversas configuraciones (inversora, no inversora, seguidor de voltaje, etc.), y su comportamiento depende de cómo se conecten las resistencias en el circuito. En el caso de la configuración mostrada en la imagen, el amplificador tiene dos entradas (una inversora y una no inversora) y puede amplificar la señal según sea necesario.

## 4.25 Ganancia:

La ganancia de un amplificador operacional ideal es muy alta, lo que significa que cualquier diferencia de voltaje entre las entradas, por pequeña que sea, se amplificará de manera significativa. En la práctica, la ganancia se controla a través de la retroalimentación externa en el circuito.

## 4.26 Uso común:

Se utilizan para amplificar señales débiles, realizar operaciones matemáticas (como sumas, restas, integrales y derivadas), y en muchos circuitos de control y procesamiento de señales.

# 5. Amplificador no inversor
   5.1 🔑 Amplificador Operacional: El amplificador no-Inversor es una configuración que permite amplificar una señal electrónica. Entonces su caracteristica, no altera la fase de entrada. Recordemos que un amplificador operacional tiene 2 entradas y una salida, la entrada positiva o no-inversora y la negativa o entrada inversora.

<div>
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/6b7f7f606ce645862ed106ae9d6083cf8ab14279/Build/Amplificador%20no%20inversor.jpg" width="300">
</div>

Figra 5.1 Imagen  Amplificador No Inversor

5.2 Caracteristicas
 5.11 La tension de entradas del amplificador son iguales de V+=V-
 5.12 La corriente del Amplificador es 0
 5.13 La impedancia de entrada es muy grande
 5.14 La impedancia de salida es muy pequeña
 La resistencia es muy grande, va haber mas impedancia.
Impedancias = 0

Ejemplo 1 
Solución 

\*{Amplificador no inversor}

<div>
 <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/984ae24ceb177f80da15cecd60534dfe512adf5f/Build/ampl%202.jpg" width="300">
</div>


$$ i_1 - i_2 = 0 $$


$$\frac{e_o - e_i}{R_2} = \frac{e_i}{R_1}$$


$$\frac{e_o}{R_2} = e_i \left( \frac{1}{R_2} + \frac{1}{R_1} \right)$$


$$e_o = e_i \left( 1 + \frac{R_2}{R_1} \right)$$

Ejemplo 2

Con Elementos Almacenadores de energia

<div align = "center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/f980f5dfe173d0ad6f3a85ce30f1f684e3e921d9/Build/amplificador%20carga%20rlc.jpg" width="300">
</div>

$$i_1 = i_2 + i_3$$

$$\frac{e'}{R_1} = i_1$$

$$ i_2 = C \frac{d e'}{dt}$$

$$ i_3 = \frac{e'}{R_2}$$

$$ e_o = e' $$

# Actividad
Obetner el Modelo matematico del siguiente Amplificador Operacional

<div align ="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/f980f5dfe173d0ad6f3a85ce30f1f684e3e921d9/Build/amplificador%20carga%20rlc.jpg" width="300">
</div>

Solucion del Ejercicio 

$$C * d(ei)/dt + (ei - e')/R1 + C * d(e')/dt + (e' - eo)/R2 = 0;$$
$$ei = e'; % Condición inicial de la salida$$
$$e = 0;$$

# 5.3 Sistemas Hidraulicos
"Se califica en sistemas hidráulicos y neumáticos de tanques.
En sistemas industriales de taque que es deseable mantener el flujo a nivel constante."
<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/a9bd062221fea9417f5f37f5f62bc644d871e143/Build/tanques%201.jpg" width="300">
</div>
q₁, q₀; Flujos de entrada y salida de líquido
R₁; Resistencia al flujo
A₁; Área transversal del tanque
h₁; Nivel de líquido en el tanque

Modelado de sistemas de ecuaciones

Flujo de salida del tanque
$$q₁ = h₁/R₁$$

Intercambio de energía
$$A₁(dh₁/dt) = qᵢ - q₁$$


Modelo qᵢ como entrada y h₁ como salida
$$q₁ = h₁/R₁ $$
$$A₁(dh₁/dt) = qᵢ - q₁$$
$$A₁(dh₁/dt) = qᵢ - h₁/R₁$$

Modelo qᵢ como entrada y q₁ como salida

$$ q₁ = h₁/R₁ $$
$$ A₁(dh₁/dt) = qᵢ - q₁$$

$$h₁ = q₁ * R₁$$

$$R₁A₁(dq₁/dt) = qᵢ - q₁$$



# Casos de Tanques Interconectados

# 2 Tanques

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/2cb5892d66e4682f77fdf9301c60b0b155fa9067/Build/2%20tanques.jpg" width="300"> 
</div>


1. {Ecuaciones generales}:

$$\[\frac{dh_1}{dt} = q_1 - q_2\]$$

$$\[\frac{dh_2}{dt} = q_2 - q_3\]$$

2. {Para el primer tanque}:

$$[R_1 \cdot A_1 \cdot \frac{dh_1}{dt} = q_1 - q_2\]$$

3. {Para el segundo tanque}:

$$[R_2 \cdot A_2 \cdot \frac{dh_2}{dt} = q_2 - q_3\]$$

4. {Relación de caudales}:

$$[q_1 = q_2 = q_3\]$$



