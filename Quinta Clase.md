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

💡 Ejemplo 1 
Solución 

\*{Amplificador no inversor}

<div>
 <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/984ae24ceb177f80da15cecd60534dfe512adf5f/Build/ampl%202.jpg" width="300">
</div>


$$ i_1 - i_2 = 0 $$


$$\frac{e_o - e_i}{R_2} = \frac{e_i}{R_1}$$


$$\frac{e_o}{R_2} = e_i \left( \frac{1}{R_2} + \frac{1}{R_1} \right)$$


$$e_o = e_i \left( 1 + \frac{R_2}{R_1} \right)$$

💡 Ejemplo 2

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

1. {Relación de caudales:}

$$[q_1 = \frac{h_1 - h_2}{R_1}\]$$

$$[q_2 = \frac{h_2}{R_2}\]$$

2. {Ecuaciones diferenciales para los tanques:}

$$[A_1 \frac{dh_1}{dt} = (q_i - q_1)\]$$

$$[A_2 \frac{dh_2}{dt} = (q_1 - q_2)\]$$

3. {Ecuaciones con derivadas de caudales:}

$$\[R_2 A_2 \frac{dq_2}{dt} = (q_1 - q_2)\]$$

$$[R_2 A_2 \frac{dq_2}{dt} + q_2 = q_1\]$$

4. {Ecuación general para el primer tanque:}

$$\[A_1 \frac{dh_1}{dt} = \left( (q_i - R_2 A_2 \frac{dq_2}{dt} + q_2) \right)\]$$

$$\[R_1 q_1 + h_2 = h_1\]$$

6. {Ecuación general para el segundo tanque:}

$$\[R_1 \left( R_2 A_2 \frac{dq_2}{dt} + q_2 \right) + R_2 q_2 = h_1\]$$

Reducimos la ecuación hasat el Final , para obtener el Modelo Matematico

1. {Ecuación general con derivadas:}

$$[\frac{d}{dt} \left( R_1 \left( R_2 A_2 \frac{dq_2}{dt} + q_2 \right) + R_2 q_2 \right) = \left( q_i - R_2 A_2 \frac{dq_2}{dt} + q_2 \right)\]$$

2. {Expansión de la ecuación:}

$$\[A_1 R_1 R_2 A_2 \frac{d^2 q_2}{dt^2} + (A_1 R_1 + A_1 R_2 + R_2 A_2) \frac{dq_2}{dt} - q_2 = q_i\]$$


##7. Tablas
   
 | Componente             	| Funcion Matematica 	| Ecuación en función del tiempo                        	|
|------------------------	|--------------------	|-------------------------------------------------------	|
| Flujo de Salida        	| $$q1, q2$$         	| $$q_1 = \frac{h_1}{R_1}$$                             	|
| Intercambio de Energia 	| $$A1, A2$$         	| $$A_1 \left( \frac{d h_1}{d t} \right) = q_i - q_1 $$ 	|
| Altura del Tanque      	| $$ h_1, h-2$$      	| $$ h_1=$${R_1}*{q_1}$$                                	|

#8. Ejericios 📚 

8.1 Desarrollar el Modelo h2 como salida

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/cd37648716037fe98bf3bbd154bb35f8ad03baa1/Build/Modelo%20h2%20como%20salida.jpg">
</div>

Solución 
{Desarrollo del modelo con \( h_2 \) como salida}

Queremos desarrollar el modelo de dos tanques interconectados con \( h_2 \) como salida. A continuación, se derivan las ecuaciones correspondientes:

{1. Relación de caudales}
Las relaciones para los caudales \( q_1 \) y \( q_2 \) son:

$$\[q_1 = \frac{h_1 - h_2}{R_1}\]$$

$$\[q_2 = \frac{h_2}{R_2}\]$$

{2. Ecuaciones diferenciales}
Las ecuaciones diferenciales para los tanques son:

$$\[A_1 \frac{dh_1}{dt} = (q_i - q_1)\]$$

$$[A_2 \frac{dh_2}{dt} = (q_1 - q_2)\]$$
{3. Sustitución de las ecuaciones de caudal}
Sustituimos las expresiones de \( q_1 \) y \( q_2 \) en la ecuación de \( h_2 \):

$$\[A_2 \frac{dh_2}{dt} = \left( \frac{h_1 - h_2}{R_1} - \frac{h_2}{R_2} \right)\]$$

{4. Despeje de la derivada de \( h_2 \)}
Despejamos \( \frac{dh_2}{dt} \):

$$\[\frac{dh_2}{dt} = \frac{1}{A_2} \left( \frac{h_1 - h_2}{R_1} - \frac{h_2}{R_2} \right)\]$$

\subsection*{5. Ecuación final}
La ecuación diferencial que describe la variación de \( h_2 \) con respecto al tiempo es:

$$\[\frac{dh_2}{dt} = \frac{1}{A_2} \left( \frac{h_1 - h_2}{R_1} - \frac{h_2}{R_2} \right)\]$$

#8. Ejericios 📚 
8.2 Ejercicio 2 
<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/8223443bb585fc9334e5e122a8f1d2f1fda5f28c/Build/Ejercicios%20amplificador%20Operacional.jpg" width="300">
</div>
# Solucion

# Cálculo de \( V_o \) y Ganancia del Amplificador

Para calcular \( V_o \) y la ganancia \( \frac{V_o}{V_i} \) del amplificador, consideramos el siguiente análisis:

## Paso 1: Aplicar la regla de la retroalimentación negativa
La retroalimentación negativa implica que \( V_+ = V_- \), es decir, la terminal inversora se mantiene a un potencial igual al de la terminal no inversora, que en este caso está a tierra.

## Paso 2: Análisis de corriente y la relación de voltaje
Aplicamos la ley de Kirchhoff para corrientes (KCL) en el nodo de la terminal inversora:

$$\[\frac{V_i}{R_1} = \frac{V_o}{R_2} + \frac{V_o}{R_3}\]$$

## Paso 3: Despejar \( V_o \)
Despejamos \( V_o \) de la ecuación:

$$\[\frac{V_i}{R_1} = V_o \left( \frac{1}{R_2} + \frac{1}{R_3} \right)\]$$

$$\[V_o = V_i \left( \frac{R_2 + R_3}{R_1 R_2} \right)\]$$

## Paso 4: Ganancia del amplificador
La ganancia \( \frac{V_o}{V_i} \) es:

$$\[\frac{V_o}{V_i} = \frac{R_2 + R_3}{R_1 R_2}\]$$

Este es el resultado final para la ganancia del amplificador.

# 9. Conclusiones
Los Amplificadores operacional son de gran utlidad en sistemas industriales y en control, y gracias 

# 10. Conclusiones

Desde la teoría de dinámica de sistemas, los sistemas hidráulicos y los amplificadores operacionales muestran respuestas similares frente a entradas escalón, impulso o seno, como retardo, ganancia y régimen permanente. Esto permite aplicar técnicas de análisis y control como el ajuste de parámetros para mejorar la estabilidad o el tiempo de respuesta del sistema.

Al modelar ambos casos con ecuaciones diferenciales, se pueden diseñar controladores PID, filtros o sistemas de regulación más precisos, tanto en circuitos hidráulicos (tanques, válvulas) como electrónicos (amplificadores, filtros activos), optimizando así su comportamiento ante perturbaciones externas.

# 11. Referencias

Jorge Eduardo Cote Ballesteros- Clase 4:(file:///C:/Users/hp/Downloads/5.%20Sistemas%20el%C3%A9ctricos.pdf)

Sistemas de Control Automatico- Benjamin Cubo-1996: https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/sistemas-de-control-automatico-benjamin-c-kuo.pdf

Dinamica de Sistemas- Ogata K: https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/dinamica_de_sistemas.pdf


