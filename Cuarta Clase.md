## Apuntes segundo corte
# Clase 3 : Sistemas Electricos
# Nombre: Kevin Nicolas Perez Tobar
# Curso: M6A

 ## 1. Introducción
 Los Sistemas Electricos, los hemos aplicados en nuestra vida cotidiana, ya sea en instalaciones electricas, en Analisis de Circuitos DC y AC, aqui vamos analizar los Circuitos RLC, y sus elementos que los componenen con metodologias de solucion ya antes vistas que son importantes para solucinar estos sitemas.
   
 ## 2.Objetivos
 
   ## 2.1 Objetivos Generales
   
  2.11 Reconcer los elementos basicos en un circuito RLC, como una resistencia, y un Inductor.
  
   2.13 Identificar como se representan las conexiones basicas de un cicruito RLC.
   
## 2.12 Objetivos Especificos

   2.12.1 Resolver por metodo de Mallas y Nodos Circuitos RLC, teniendo en cuenta sus caracteristicas para encontrar voltajes y voltajes segun se requiera.
   
   2.13.1 Identificar los modelos matematicos necesarios para resolver problemas que involucren la solucion de circuitos Electricos.
   
   2.14.1 Aplicar Ecuaciones Diferenaciales, para reducir sistemas de ecuaciones de Segundo Orden a primer Orden, para encontrar la funcion de dicho circuito.
   

 ##   3.  Resumen
 
  Los sistemas eléctricos están presentes en nuestra vida cotidiana, desde instalaciones eléctricas hasta el análisis de circuitos DC y AC. En este contexto, se abordarán los circuitos RLC y sus componentes, aplicando metodologías de solución previamente vistas, las cuales son fundamentales para resolver estos sistemas.
      
## 4. Definiciones

 4.1🔑Circuito: Un circuito es un conjunto de elementos eléctricos conectados entre sí de manera que permiten el paso de corriente eléctrica. Un circuito básico generalmente está compuesto por fuentes de energía 

  <div align="center">
 <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/846e542671e5164aa2ed4265a697dee87c86276c/Build/7bf2a85a2432376373d66e4a86fe015fdb5f5570.svg" width="300">
  </div>
Figura 4.1 Imagen de un Circuito RLC

 4.1🔑Circuito RLC en Serie: En un circuito RLC en serie, los tres componentes (resistor, inductor y condensador) están conectados en una única ruta, formando un único lazo de corriente. Es decir, la misma corriente pasa a través de los tres componentes.

 4.2 🔑Circuito en Paralelo: En un circuito RLC en paralelo, los tres componentes están conectados de forma que cada uno tiene un camino independiente para la corriente. Es decir, la corriente se divide entre el resistor, el inductor y el condensador, pero la tensión es la misma para todos los componentes.

 4.3 🔑 Malla: Es el camino cerrado que forman dos o más ramas de un circuito. En una malla la suma de todas las tensiones, cada una con su signo correspondiente, es igual a 0 (Ley de Kirchoff de las mallas).
 
 4.4 🔑 Nodo:un nodo es cualquier punto donde se conectan dos o más componentes o elementos del circuito, como resistencias, fuentes de voltaje, o conductores. Básicamente, un nodo es un punto de unión o intersección dentro de un circuito eléctrico.

 ## 5. Ejemplos

 ### 1. Análisis de Ohm y Digital

 <div align="center">
  <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/e2c5b3a3036c4696fb92d0a81efcc6115613a167/Build/circuito%201.jpg" width="300">
 </div>

1. $$\( 1kV \Rightarrow \sum v = 0 \)$$
   - Toda la energía se consume del circuito.
2. Identificar las mallas del circuito.
3. Dibujar las corrientes de las mallas.

$$\[V = L \frac{di}{dt}\]$$

**Elementos de Corrientes:**

$$\[-u(t) + V_R + V_L + \gamma = 0 \quad \Rightarrow \quad \gamma = 0\]$$

 ## 2. Actividad: Obtener el Modelo para el Circuito

Obtener el modelo para el circuito de la figura:

 <div align="center">
  <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/93da298ae244186e1f6dafa4f572ace333e666de/Build/circuito%202.jpg" width="300">
 </div>

$$\[u(t) + V_{R1} + V_{R2} + V_C = 0\]$$

**Ecuaciones:**

$$\[-u(t) + (R_1 + R_2) \cdot \frac{dV_C}{dt} = 0\]$$

$$\[y(t) = V_{R2} + V_C\]$$

### 3. Aplicando Ley de Kirchhoff de Corrientes (LKC)

**Aplicando LKC:**

$$[\sum i = 0\]$$

$$[i_u - i_1 = i_c\]$$

$$\[i_u = V_{AB} - 2 \frac{dy(t)}{dt} = 0]$$

**Ecuaciones:**

$$\[-u(t) + (R_1 + R_2) \cdot C \frac{dv}{dt} + V_0 = 0\]$$

## 4. Ecuaciones de Voltajes y Corrientes

**Voltaje y Corriente:**

$$[V_{AB} = 2 \cdot \frac{dy(t)}{dt}\]$$

**Ecuaciones:**

$$\[u(t) - 6 \cdot \frac{dy(t)}{dt} - 2y(t) = 0\]$$

## Ejemplo 3

Halllar el modelo matematico de la siguiente figura 

 <div align="center">
  <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/60d148bbafac71feadf5c41182e61f2c9efa279e/Build/circuito%204.jpg" width="300">
 </div>

**Ley de Kirchhoff de Corrientes Aplicada:**

$$\[- \frac{dex}{dt} = R_2 C_2 \cdot \frac{d^2 C_0}{dC_2^2} + \frac{dC_0}{dt}\]$$

## 6. Ecuaciones Finales

**Ecuaciones Generales:**
$$[-e_x + \frac{R_2 C_2}{R_1} \cdot \frac{d}{dt} \left(\frac{R_2 + 1}{R_1} \right)=0]$$

**Ecuaciones con Corrientes y Voltajes:**

$$ [ei - e_x + C_1 \cdot \frac{d(0 - e_x)}{dt} + \frac{C_0 e_x}{R_2} = 0$$

$$[ \frac{dex}{dt} + e_o + C_2 \cdot \frac{d^2 e_o}{dC_2^2} + \frac{dC_0}{dt} = 0$$

## 7. Tablas

| Unidad del sistema | Ecuación descriptiva                                 | Ecuación en función del tiempo                         |
|--------------------|------------------------------------------------------|--------------------------------------------------------|
| Corriente          | $$i_C(t) = C \frac{dV}{dt}$$                         | $$i_L(t) = - \frac{1}{L} \int_0^t v \, dt + i_L(t_0)$$ |
| Voltaje            | $$V_C(t) = \frac{1}{C} \int_0^t i \, dt + v_C(t_0)$$ | $$v_L(t) = L \frac{di}{dt}$$                           |
| Potencia           | $$P_C = v i = C v \frac{dv}{dt}$$                    | $$P_L = v i = L i \frac{di}{dt}$$                      |

Tabla 5.1 Concepto de las tablas de conceptos que se trabajan en corriente, Voltajes y Resistencias

## 8. Ejercicios

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/a42b4ec2184dc5891d8a04711ac1b1e210046bdf/Build/problema%20circuito%201.jpg" width="300">
</div>

# Solución del problema utilizando el análisis de mallas

Dado el circuito, utilizamos el análisis de mallas para obtener el modelo matemático. Las dos mallas tienen corrientes \( i_1 \) e \( i_2 \), y aplicamos la ley de voltajes de Kirchhoff (LVK) a cada malla.

## Definición de las corrientes
-\( i_1 \): Corriente en la primera malla (a través de \( R_1 \) y \( L \)).
- \( i_2 \): Corriente en la segunda malla (a través de \( R_2 \) y \( C \)).

## Aplicación de la Ley de Voltajes de Kirchhoff (LVK)

### Malla 1
Recorremos la malla en sentido horario:

$$E - R_1 i_1 - L \frac{d}{dt} i_1 = 0$$

$$E = R_1 i_1 + L \frac{d}{dt} i_1$$

### Malla 2
Recorremos la malla en sentido horario:

$$R_2 i_2 + \frac{1}{C} \int i_2 \, dt = L \frac{d}{dt} i_1$$

## Sistema de ecuaciones
El sistema de ecuaciones que describe el comportamiento dinámico de las corrientes \( i_1 \) e \( i_2 \) es el siguiente:

$$E = R_1 i_1 + L \frac{d}{dt} i_1$$

$$R_2 i_2 + \frac{1}{C} \int i_2 \, dt = L \frac{d}{dt} i_1$$

Este sistema de ecuaciones debe tener en cuenta para interpretar como se aplica la ley de Khirchoff en ananalisis de mallas

# Ejercicio 2

En el siguiente ejercicio, Obtenga el modelo matematico que se pueda resolver este circuito por analisis nodal, para hallar la funcion de la salida, con respecto a su entrada

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/8f982ec7b66cc8a905de9981e3d5cca5e8459197/Build/4b7c0223-3dc4-4121-9b5e-21bd7ca7bef9.png" width="300">
</div>

#Solucion
Para el análisis de este circuito con análisis de nodos, definimos los siguientes nodos:

- \( V_{\text{in}} \): Voltaje de entrada.
- \( V_1 \): Voltaje en el nodo entre \( R_1 \) y \( L_1 \).
- \( V_2 \): Voltaje en el nodo entre \( R_2 \) y \( C_2 \).
- \( V_{\text{out}} = V_2 \): Voltaje de salida.

{Ecuaciones de Kirchhoff para los nodos}

{Nodo 1}

Para el nodo 1, se aplica la ley de corrientes de Kirchhoff (LCK):
$$\[\frac{V_{\text{in}} - V_1}{R_1} + C_1 \frac{dV_1}{dt} + \frac{V_1 - V_2}{L_1} = 0\]$$

\subsubsection*{Nodo 2}

Para el nodo 2, se aplica nuevamente la LCK:
$$\[\frac{V_2 - V_1}{L_1} + \frac{V_2}{R_2} + C_2 \frac{dV_2}{dt} = 0\]$$

\subsection*{Sistema de ecuaciones diferenciales}

El sistema de ecuaciones que describe el comportamiento del circuito es:

$$\[\frac{V_{\text{in}} - V_1}{R_1} + C_1 \frac{dV_1}{dt} + \frac{V_1 - V_2}{L_1} = 0\]$$

$$\[\frac{V_2 - V_1}{L_1} + \frac{V_2}{R_2} + C_2 \frac{dV_2}{dt} = 0\]$$

Estas ecuaciones se pueden resolver numéricamente para obtener el voltaje de salida

$$\( V_{\text{out}} = V_2 \).$$

# 9. Código

💡Ejemplo 4
:
% Parámetros del circuito

R1 = 10;   % Resistencia R1 en ohmios
R2 = 10;   % Resistencia R2 en ohmios
L1 = 1e-3; % Inductancia L1 en henrios
C1 = 1e-6; % Capacidad C1 en faradios
C2 = 1e-6; % Capacidad C2 en faradios

% Condiciones iniciales
V1_0 = 0; % Condición inicial de V1
V2_0 = 0; % Condición inicial de V2

% Voltaje de entrada (suponemos un escalón unitario)
Vin = @(t) 1 * (t >= 0);  % Paso de voltaje unitario (escala 1)

% Ecuaciones diferenciales (sistema de orden 2)
% Sistema: dV1/dt y dV2/dt

# 10. Conclusiones
Los Sistemas electricos son modelos matemticos que nos permiten analizar un circuito RLC, por metodo de mallas y Nodos que son tecnicas de solucion que permiten hallar los voltajes a las salidas, analizar las direcciones de las corrientes y entender como se comprtan los elementos pasivos(resisitencias), condensadores y bobinas.

El analisis de Mallas, basandose en la Ley de Voltajes de Kirchoff nos permite hallar las corrientes en lazos cerrados, especialmente cuando hay muchos elementos conectados entre si, su analisis ayuda a solucionar mas rapido los circuitos de manera efectiva. 

El analisis de Nodos permite se basa en la ley de corrientes de Kirchhoff (LCK) y es especialmente ventajoso en circuitos con múltiples puntos de conexión (nodos). Este método es útil cuando el circuito tiene muchos elementos conectados entre sí de manera que las corrientes en varios nodos deben ser determinadas simultáneamente. 

# 11. Referencias

Jorge Eduardo Cote Ballesteros- Clase 4:(file:///C:/Users/hp/Downloads/5.%20Sistemas%20el%C3%A9ctricos.pdf)

Sistemas de Control Automatico- Benjamin Cubo-1996: https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/sistemas-de-control-automatico-benjamin-c-kuo.pdf

Dinamica de Sistemas- Ogata K: https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/dinamica_de_sistemas.pdf








    
 


  
   
   
   
   
