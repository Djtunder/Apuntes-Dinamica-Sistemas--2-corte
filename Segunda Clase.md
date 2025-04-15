## Apuntes segundo corte
# Clase 2 : Sistemas Mecanicos
# Nombre: Kevin Nicolas Perez Tobar
# Curso: M6A

# SISTEMAS MECANICOS
## 1. Introducción
Para analizar los sistemas de control se necesitan emplear modelos matematicos que se basan en las leyes fisicas para gobernar el comportamiento de cualquier sistema.
>>
 ¿Como empleamos los sistemas aplicando los Modelos Matematicos?
>>
A travez de los diagramas de Bloques, donde hay una entrada que se emplea una funcion matematica y una salida de esa funcion. Las Relaciones de entrada y salida se pueden definir dichos sistemas, tiene relaciones causa- efecto y entre estos elementos se conforman diferentes parametros de bloques de funciones basicos para producir ecuaciones y principios matemáticos.

# BLOQUES FUNCIONALES DE SISTEMAS MECANICOS
 Las formas basicas de los bloques funcionales de sistemas mecanicos son tres elementos que conforman son los resortes, masa, y amortiguadores.
 >>
 🔑 Resorte: Es un componente mecánico elástico diseñado para almacenar y liberar energía. Generalmente está fabricado con materiales metálicos, como acero al carbono o acero inoxidable, aunque también existen versiones no metálicas o en multitud de materiales para aplicaciones específicas. Este elemento representa la rigudez del cuerpo.
>>
 <div align="center">
 <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/299363ee395bd9bfdcbfe020186725f9588064a1/resorte.jpg" width="300">
  </div>


🔑 Amortiguadores: Es un elemento que se emplea para representar pictoricamente las fuerzas de amortiguamiento que hacen mas lento el movimiento del objeto y consta de un piston que se mueve dentro de un clindro cerrado. El movimiento dentro del cilindro cerrado. El movimiento del piston requiere que el fluido pase de un lado a otro. Este produce una fuerza resistiva en el caso ideal, la Fuerza resistiva o de amaortiguamiento F es proporcional a la velocidad v del piston.
 >>
 <div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/99ed05eb858429fc36236baf1b4e36178d610819/Build/amortiguador.jpg.png" width="300">
 </div>
 🔑 Masas: En un sistema masa-resorte, la masa es el objeto que está sujeto a la acción de la fuerza ejercida por el resorte. La masa representa la cantidad de materia de dicho objeto y es la responsable de su resistencia al movimiento, es decir, de su inercia. La masa exhibe la propiedad cuando analizamos el sistema entre mayor sea la masa, mayor es la fuerza reqerida para producir una aceleracion especifica. La relacion entre la Fuerza y la masa a es la segunda ley de newton.

 <div align="center">
 <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/c13787753e34825e7a5794230e020255ca72a419/Build/masa.jpg" width="300">
 </div>

 # FRICCIÓN
 
 🔑 Definicion:es un concepto que involucra la interacción entre un sistema de masa y resorte, considerando la resistencia al movimiento debido a la fricción. Este tipo de sistema es comúnmente analizado en la física para estudiar el comportamiento de oscilaciones amortiguadas.
 
 <div align= "center">
 <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/2b8d06868bb9120c7def887ebf84d8ae16051504/friccion.jpg" width="300">
 </div>
 
 # TIPOS DE FRICCIÓN
  🔑 Fuerzas de Friccion: Es una reaccion de una fuerza externa, que depende de la velcidad.
  
  <div align= "center">
  <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/3a9311ee4484ed7e784b6f786f40d5daba7a1e2e/Build/fr.png" width="300">
  </div>
  
  🔑 Fricción estatica: Es una fuerza entre dos superficies que impide que estas se deslicen o resbalen una sobre la otra.
  
   <div align= "center">
   <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/e8c8e17128bcdf8461d2b147eda7099e554aa3fd/Build/friccion%20estatica.png" width="300">
   </div>
  
  🔑 Fricción por Deslizamiento: Es la fuerza que se opone ante el movimiento deslizante de dos objetos de un objeto o una superficie. 
  
   <div align= "center">
   <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/de9c67b919655f1ab36918d1f77efa89a3718c5a/Build/friccion%20por%20deslizamiento.png" width="300">
   </div>
  
   🔑 Fricción por Rodamiento: La friccion por Rodamiento implica en superficies no concordantes, es una fuerza resistiva que actua entre dos superficies en contacto cuando se desliza 
      o intenta deslizrse una sobre la otra.
   
 <div align= "center">
 <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/f75b8d05b61cc4ce4f07850f1450b57c83bc97df/Build/Figura%206.jpg" width="300">
 </div>
  
  ## Sistemas de masa-resorte-Amortiguador.
 🔑  Definición: Muchas fuerzas que actuan sobre el sistema pueden considerarse una masa, un resorte y un amortiguador dispuestos en la manera que la fuerza y el desplazamiento del sistema se adopta un proceso que se considera la relacion de las fuerzas que actuan sobre ella. Para ello utilizamos un Diagrama de Cuerpo Libre, donde las fuerzas actuan de manera swimulatanea sobre un cuerpo. En el esquema podemos ver las fuerzas horizontales que van en opocision a la Fuerza de la salida del Dezplazamiento (x), que son la Fuerza del resorte (k) yla Fuerza del Amortiguador (bx).
  
 <div align= "center">
 <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/6d1e8ea872022d29af1ecc33b73791ce8eff1b72/Build/sistema%20masa-resorte-amortiguador.jpg" width="300">
 </div>
 
 # 3. Ecuaciones
 
 $y = \textit{la salida que yo quiero conocer}$*

 $k_2 = \textit{posición}$



 Primer Paso
 1) Diagrama de Cuerpo Libre
    
 <div align= "center">
 <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/686cc0411a2e49feca6c8c5efe521f75da5c97cf/Build/Imagen1.png" width="300" >
 </div>

 ## Ley de Newton
 🔑En un sistema masa-resorte, el resorte genera una fuerza de restitución (de acuerdo con la ley de Hooke), que es proporcional al desplazamiento de la masa desde su posición de equilibrio.

 La ecuación es
 
 $$F= m*a$$
 
 donde,
 
 $F= \textit{Fuerza aplicada al resorte}$
 
 $m= \textit{masa}$
 
 $a= \textit{aceleracion del objeto}$
 
 Si usamos la ecuacion diferencial de la aceleracion que describe al sistema como:
 
 $$m*a=−kx$$
 
 donde
$m= \textit{es la masa}$

$a= \textit es la aceleración {derivada del movimiento}$

$k = \textit{es la constante del resorte},$

$x = \textit{es el desplazamiento de la masa desde la posición de equilibrio.}$

 ## Fricción Viscosa
🔑La fuerza de fricción Fv que actúa en el Movimiento Armónico Amortiguado es proporcional a la velocidad V en la mayoría de los casos de interés científico. Dicha fuerza tiene la forma Fv = bV, donde b es una constante positiva que depende de las características del fluido que ocasiona la fricción, entre otras cosas. Esta fricción, también conocida como Fricción Viscosa, se representa mediante un diagrama que consiste en un pistón y un cilindro lleno de aceite:

 <div align= "center">
 <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/73ac419985aa61c9d8fd90870253d18a1c559a97/Build/null80.png" width="300">
 </div>
 
 Ecuación 
 
 $$Ft = K1*Vm$$

 ## Ley de Hooke 
🔑La ley de Hooke :Establece que es la Fuerza aplicada en el resorte, cuando esten es sistemas lineales, simplemente se mantienen al mantenimiento del material de referencia donde, hay una contante K y la elongación (x), aqui podemos visualizar la grafica del comportamiento donde se pueden ver los tres tipos de resortes en funcion de la Fuerza con respecto a su pocisión (x).
  
 <div align= "center">
 <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/52649eb86dc511eea11b6fb12642b7bc4d0621f1/Build/grafica%20de%20resortes.jpg" width="300">
 </div>

4. ## EJERCICIOS
4.1 Hallar la ecuacion Diferencial del sistema masa resorte- amortiguador
  
 <div align= "center">
  <img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/47242b2460dfb97629aa9edc934af9b2eb469182/Build/Captura%20de%20pantalla%202025-04-09%20210219.jpg" width="300">
 </div>

1) Paso
   
   Dibujar el Diagrama de Cuerpo Libre
   
 <div align= "center">  
 <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/97d5de16eb03fefe3a42a9d1db1b4152bb00a596/Build/DCL2.png" width="300">
 </div>

$$fk(t)= k(X1(t)-x(t))$$
$$Fb(t)= b(x1)-x'(t))$$
$$k(x_1(t) - x(t)) + b(\dot{x}_1(t) - \dot{x}(t)) = m\ddot{x}(t)$$


4.2 El siguiente ejercio muestra un sistema donde no se tiene en cuenta el efecto de la fuerza de gravedad, si se considera el desplazamiento desde la pocision de equilibrio
puesto que en este caso:

$$k\delta = mg$$

Y si se considera la sustitución:

𝑦 = 𝑥 + 𝛿

El término correspondiente a la fuerza de gravedad desaparece haz lo mismo.

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/745cce1d35c71fc3363432c7ad914ad9b0498581/Build/ejercicio3.png" width="300">
</div>

Ahora, vamos aplicarlo a un ejercicio donde se aplicamos un sistema de masa resorte de suspension 

 $$𝑈+𝐹𝑟−𝐹𝑔=∑〖𝐹=𝑚𝑎〗$$
$$𝑚𝑔+𝑢(𝑡)−𝑘2𝑦(𝑡)−𝑘1𝑦^′ (𝑡)=𝑚𝑦¨(𝑡)$$
$$𝑢+𝐹𝑤−𝐹𝑟−𝐹𝐹=𝑚∗𝑎$$
$$−𝑢−𝐹𝑤+𝐹𝑟+𝐹𝐹=−𝑚∗𝑎$$

# Vibracion Libre
🔑Definición: 	Aún aplicando entrada durante un intervalo de tiempo definido es posible provocar un comportamiento oscilatorio en la variable de salida del sistema
•	Por ejemplo, en el caso de la suspensión si se aplica una fuerza constante durante un intervalo corto de tiempo y se retira dicho estímulo el sistema tiende a vibrar
•	Este movimiento periódico se conoce como vibración libre

<p align="center">
  <img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/13825c612a482899d14c48c81b08caea37f0ed05/Build/ejericio%20resorte%20masa-amortiguador.jpg?raw=true" width="400"/>
</p>

Ejemplo
>>
•	Simular la solución de este sistema sabiendo:
𝑁
•	$$𝑘=22500$$
𝑚
𝑁𝑠
•	$$𝑏 = 2000$$
𝑚
•	$$𝑀 = 300 𝐾𝑔$$
•	Si se suben al carro 2 personas que en promedio pesan 80Kg
>>
# Solución
1. Obtenemos los datos del sistema
   
$$
k_1 = k_2 = 22500 \, \frac{N}{m}
$$

$$
b = 2000 \, \frac{Ns}{m}
$$

$$
m_1 = 300 + 2 \times 80 = 460 \, kg
$$

$$
m_2 = 300 \, kg
$$
⚙️ Ecuaciones del sistema
$$\{Primera}\ \{ecuación (masa m1m_ 1m1)}:$$

$$m1x¨1=-k1x1-bx˙1+k2(x2-x1)m_1 \ddot{x}_1 = -k_1 x_1 - b \dot{x}_1 + k_2(x_2 - x_1)m1x¨1=-k1x1-bx˙1+k2(x2-x1)$$

Sustituyendo\ valores:

$$460x¨1=-22500x1-2000x˙1+22500(x2-x1)460 \ddot{x}_1 = -22500 x_1 - 2000 \dot{x}_1 + 22500(x_2 - x_1)460x¨1=-22500x1-2000x˙1+22500(x2-x1)$$

Simplificada:

$$460x¨1+2000x˙1+45000x1-22500x2=0460 \ddot{x}_1 + 2000 \dot{x}_1 + 45000 x_1 - 22500 x_2 = 0460x¨1+2000x˙1+45000x1-22500x2=0$$

⚙️ Ecuaciones del sistema

$$\{Segunda}\ \{ecuación (masa m2m_2m2)}:$$

$$m2x¨2=-k2(x2-x1)m_2 \ddot{x}_2 = -k_2(x_2 - x_1)m2x¨2=-k2(x2-x1)$$

Sustituyendo\ valores:

$$300x¨2=-22500(x2-x1)300 \ddot{x}_2 = -22500(x_2 - x_1)300x¨2=-22500(x2-x1)$$

Simplificada:

$$300x¨2+22500x2-22500x1=0300 \ddot{x}_2 + 22500 x_2 - 22500 x_1 = 0300x¨2+22500x2-22500x1=0$$

# EJERCICIO 2
# SISTEMA MASA-RESORTE COMPLEJO

🔑Definición: En resumen, el análisis de un sistema masa-resorte complejo de carros horizontales involucra resolver ecuaciones diferenciales que modelan el movimiento de la masa(s), teniendo en cuenta las fuerzas elásticas, de fricción y las posibles fuerzas externas. Para sistemas más complejos, se requieren métodos de simulación computacional.

¿Cual es la Aplicación del sistemas masa.resorte de carros vericales en Ingenieria?
Este tipo de modelo es útil para analizar vibraciones en estructuras, sistemas de suspensión de vehículos, o en el diseño de amortiguadores para reducir las vibraciones no deseadas.

## Ejercicio de Aplicación visto en clase

Halle la ecuación modelo del sistema Masa Mecanico complejo.

<div algin="center">
<img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/b657f57fd992c8107319db169d33b07430edf28c/Build/sistema%201.jpg" width="300">
</div>

#Solución

1) Dibjamos los diagramas de cuerpo libre del carro 1, que seria la masa 1 y el carro 2 que seria la masa 2.

# Diagrama de Cuerpo Libre 1
<div algin="center">
<img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/d952a403c464d67aab0070badc1b8c1b8b610dbe/Build/diagrama%20cuerpo%20libre%201.jpg" width="300">
</div>

# Diagrama de Cuerpo Libre 2

<div algin="center">
<img src= "https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/8c076506d836f72133fdf5539fbbc87a33393c0c/Build/diagrma%20de%20cuerpo%20libre%202.jpg" width="300">
</div>

## Ecuaciones 
FR1 y FR2, tienen la misma fuerza

$$𝑢 − 𝐹𝑅1 − 𝐹𝑅2 − 𝐹𝐹 = 𝑚1 ∗ 𝑎𝑚1$$

𝐿𝑎 𝑑𝑖𝑠𝑡𝑎𝑛𝑐𝑖𝑎 𝑑𝑒 𝑒𝑙𝑜𝑛𝑔𝑎𝑐𝑖ó𝑛 𝑑𝑒𝑙 𝑟𝑒𝑠𝑜𝑟𝑡𝑒 2 𝑑𝑒𝑝𝑒𝑛𝑑𝑒 𝑑𝑒𝑙 𝑚𝑜𝑣𝑖𝑚𝑖𝑒𝑡𝑜 𝑑𝑒 𝑎𝑚𝑏𝑎𝑠 𝑚𝑎𝑠𝑎𝑠 𝐿𝑎 𝑣𝑒𝑙𝑜𝑐𝑖𝑑𝑎𝑑 𝑑𝑒𝑙 𝑒𝑚𝑏𝑜𝑙𝑜 𝑑𝑒𝑙 𝑎𝑚𝑜𝑟𝑡𝑖𝑔𝑢𝑎𝑑𝑜𝑟 𝑑𝑒𝑙 𝑟𝑒𝑠𝑜𝑟𝑡𝑒 2 𝑑𝑒𝑝𝑒𝑛𝑑𝑒 𝑑𝑒𝑙 𝑚𝑜𝑣𝑖𝑚𝑖𝑒𝑡𝑜 𝑑𝑒 𝑎𝑚𝑏𝑎𝑠 𝑚𝑎𝑠𝑎s.

$$𝐹𝑅2 + 𝐹𝐹 − 𝐹𝑅3 = 𝑚2 ∗ 𝑎𝑚2$$

Para la masa 1

$$u(t) - k1 {(x1(t) - k2*( x1(t) - x2(t)) - b \frac{d(x_1(t) - x2(t))}{dt} = m_1 \frac{d^2 x_1(t)}{dt^2}}$$


Para la masa 2

$$k2*{( x1(t) - x2(t)) + b \frac{d(x1(t) - x2(t))}{dt} - k3 x2(t) = m2 \frac{d^2 x_2(t)}{dt^2}}$$

Finalmente tenemos un sistema de ecuaciones de segundo orden, donde se obtuvo dos respuetas al analizar dos cuerpos de dicho sistema

$$u(t) - k_1 x_1(t) - k_2 \left( x_1(t) - x_2(t) \right) - b \frac{d(x_1(t) - x_2(t))}{dt} = m_1 \frac{d^2 x_1(t)}{dt^2}$$

$$k_2 \left( x_1(t) - x_2(t) \right) + b \frac{d(x_1(t) - x_2(t))}{dt} - k_3 x_2(t) = m_2 \frac{d^2 x_2(t)}{dt^2}$$


## EJERCICIOS DE REPASO

La Figura 1 muestra un sistema masa-resorte-amortiguador. La salida es el desplazamiento x(t) del sistema, mientras que la entrada es la fuerza u(t) que se ejerce sobre la masa m. Hallar el modelo matematico de dicho sistema.

<div align="center">
<img src="https://github.com/Djtunder/Apuntes-Dinamica-Sistemas--2-corte/blob/eb1c146508ff3e19a745c1977c6e2b9a078d6fc1/null-12.png" width="300">
</div>

# SOlUCIÓN

Sabemos que la sumatoria de fuerzas:
    
  $$\[ \sum F = m \cdot a \]$$
    
  $$ \[a = \frac{F}{m}, \quad F = m \cdot a\]$$
    
 $$ \[ a = \frac{F_R}{m}, \quad F_R = m \cdot a \]$$

  $$ \[ F_R = k z \cdot y(t) \]$$

  $$\[ F_F = b \cdot \frac{dy(t)}{dt} \]$$
    
   $$\[ u(t) - k z \cdot y(t) - b \cdot \frac{dy(t)}{dt} = m \cdot \frac{d^2 y(t)}{dt^2} \]$$
    
   {Ecuación Diferencial:}
    
  Derivamos respecto al tiempo:
    
   $$\[ k \left( \frac{du(t)}{dt} - \frac{dy(t)}{dt} \right) - k z \cdot \frac{dy(t)}{dt} - b \cdot \frac{d^2 y(t)}{dt^2} \]$$
    
  $$\[ku - ky \cdot \frac{dy(t)}{dt} = m \cdot \frac{d^2 y(t)}{dt^2}\]$$

 $$k \left( y - u \right) - k_i \frac{d y}{dt} = m \frac{d^2 u}{dt^2} + ky$$












