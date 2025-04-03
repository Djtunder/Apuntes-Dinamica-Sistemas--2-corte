# Apuntes-Dinamica-Sistemas-2-corte
# Nombre: Kevin Nicolas Perez Tobar
# Curso: M6A 
## APUNTES PRIMERA CLASE 
>>
# Correccion Parcial Primer Corte
# Ejercicio 1 
>>
$$
F(s) = \ddot{x} + 4x = 5, \quad X(0) = 5, \quad X'(0) = 0
$$
>>
$$
s^2 X(s) - 5s + 4x(s) = \frac{5}{s}
$$
$$
X(s)(s^2 + 4) = \frac{5}{s} + 5s
$$
>>
$$ X(s) = \frac{5 + 5s^2}{s^2 + 4} = \frac{A}{s} + \frac{Bs + D}{s^2 + 4} $$

Multiplicamos ambos lados por \( s^2 + 4 \):

$$ A(s^2 + 4) + Bs^2 + Ds = 5 + 5s^2 $$
>>
# Coeficientes de S^2
A+B= 5
# Coeficientes de S
D=0
# Coeficientes  de  A
4A=5
>>
$$ A = \frac{5}{4} $$
>>
# Expandimos los términos:
>>
$$ As^2 + 4A + Bs^2 + Ds = 5 + 5s^2 $$
>>

$$\frac{5}{4} + B = 5 $$

$$ B = 5 - \frac{5}{4} $$
$$ B = \frac{-5 + 20}{4} $$
$$ B = -\frac{15}{4} $$
>>
Aplicamos la transformada inversa de Laplace:
>>
$$ \mathcal{L}^{-1}\{ X(s) \} = \frac{5}{4} - \frac{15}{4} \cos(2t) $$
>>
## Segundo Ejercicio
>>
$$
F(s) = 2\ddot{x} + 2x + x = 1, \quad X(0) = 0, \quad X'(0) = 2
$$

$$
2(s^2X(s) - 2s) + 2(sX(s)) + X_s = \frac{1}{s}
$$

$$
2s^2X(s) - 4s + 2(sX(s)) + X_s = \frac{1}{s}
$$

$$
X(s)(2s^2 + 2s + 1) = \frac{1}{s} + 4
$$

$$
X(s) = \frac{1 + 4s}{s(2s^2 + 2s + 1)} = \frac{A}{s} + \frac{Bs + D}{2s^2 + 2s + 1}
$$

$$
A = \left| \frac{1 + 4s}{s(2s^2 + 2s + 1)} \right|_{s=0}
$$
>>
$$
A = \left| \frac{1 + 4(0)}{s(2(0)^2 + 2(0) + 1)} \right| = \frac{1}{1} = 1
$$

$$
\left. \frac{1 + 4s}{s} \right|_{s = -1 + 2i}
$$

$$
\left. Bs + D \right|_{s = -1 + 2i}
$$

$$
\frac{1 + 4(-1 + 2i)}{-1 + 2i} = -B + 2Bi + D
$$

$$
\frac{1 + (-4 + 8i)}{-1 + 2i} = -B + 2Bi + D
$$

$$
\frac{1 - 4 + 8i}{-1 + 2i} = -B + 2Bi + D
$$

$$
-1 + 4 + 8i \ast (-1 + 2i) = (-1 + 2i) \ast (-B + 2Bi + D)
$$

$$
3 + 6i - 8i + 16i^2 = B - 4Bi - D + 2Di
$$

$$
3 - 2i + 16 = -3B - 4Bi - D + 2Di
$$

$$
-4Bi + 2Bi = \frac{2}{5}i
$$

$$
-4Bi + 2Bi = \frac{2}{5}i
$$

$$
-2Bi = \frac{2}{5}i
$$

$$
B = \frac{2}{-10i}i
$$

$$
B = \frac{-1}{5}
$$

$$
B - D = -19
$$

$$
-D = -19 + B
$$

$$
-D = -19 - \frac{1}{5}
$$

$$
D = \frac{20}{5}
$$

$$
D = 4
$$
>>
## Tercer Ejercicio
$$
F(s) = \frac{5(s+2)}{s^2(s^2 - 4s + 8)}
$$

Expandiendo en fracciones parciales:

$$
F(s) = \frac{5(s+2)}{s^2(s^2 - 4s + 8)} = \frac{A}{s} + \frac{B}{s^2} + \frac{Cs+D}{s^2 - 4s + 8}
$$

Para encontrar \( A \), evaluamos en \( s = 2 \):

$$
A = \left. \frac{5(2+2)}{(2^2 - 4(2) + 8)} \right|_{s=2}
$$

$$
A = \frac{10}{8} = \frac{5}{4}
$$
Sabemos que \( B = 0 \) porque al usar anuladores con \( s = -2 \), se cancela el numerador.

La ecuación para A es:

$$
A = \frac{5(S + 2)}{S^2}
$$

$$
A = \frac{5(S^2 - 4S + 8) - 5(S + 2)(2S - 4)}{(S^2 - 4S + 8)}
$$

Evaluando en \( S = 2 + 2i \):

$$
\left.\frac{5(S + 2)}{S^2}\right|_{S = 2 + 2i}
$$

$$
\left.CS + D\right|_{S = 2 + 2i}
$$

Sustituyendo \( S = 2 + 2i \):

$$
\frac{5(2 + 2i + 2)}{(2 + 2i)^2} = 2C + 2Ci + D
$$

$$
\frac{10 + 10i + 10}{4 + 8i - 4} = 2C + 2Ci + D
$$

Simplificando:

$$
\frac{20 + 10i}{8i} \cdot \frac{-8i}{-8i}
$$

$$
\frac{-160 + 80}{64} = 2C + 2Ci + D
$$

$$
\frac{-160i + 80}{64} = 2C + 2Ci + D
$$

Igualando los coeficientes de la parte real y la parte imaginaria:

Parte imaginaria:

$$
2Ci = \frac{-160i}{64}
$$

$$
C = \frac{-160i}{\frac{64}{2i}}
$$

$$
C = \frac{-160i}{128i}
$$

$$
C = \frac{-1}{4}
$$

Parte real:

$$
\frac{80}{64} = 2C + D
$$

$$
D = \frac{80 \times 128}{64 \times 2 \times 160}
$$

$$
D = \frac{-10240}{20480}
$$

$$
D = \frac{-1}{2}
$$

Calculamos la Transformada Inversa de Laplace

$$\mathcal{L}^{-1}\{ X(s) \} = \frac{A}{S^2} + \frac{B}{S} - \frac{Cs + D}{S^2 - 4S + 8}$$

$$ \mathcal{L}^{-1}\{ X(s) \} = \frac{\frac{5}{4}}{S^2} - \frac{\frac{-1}{4} - \frac{1}{2}}{S^2 - 4S + 8} $$

$$ \frac{5}{4} \mathcal{L}^{-1}\left( \frac{1}{S^2} \right) + \frac{1}{4} \mathcal{L}^{-1}\left( \frac{1}{S^2 - 4S + 8} \right) + \frac{1}{2} \mathcal{L}^{-1}\left( \frac{1}{S^2 - 4S + 8} \right) $$
>>
Calculamos cada una de las Transformadas por aparte

$$ \mathcal{L}^{-1}\left( \frac{1}{S^2} \right) = t $$

$$ \mathcal{L}^{-1}\left( \frac{1}{S^2 - 4S + 8} \right) = e^t \cos(2t) $$

Por lo tanto, la transformada inversa de Laplace de la ecuación 

$$ F(s) = \frac{5}{4} t + \frac{1}{4} e^t \cos(2t) + \frac{1}{2} e^t \cos(2t) $$
>>
## Cuarto Ejercicio

$$
F(S) = \frac{6s}{(s - \frac{5}{2})(S^2 - 4S + 8)} = \frac{A}{s - \frac{5}{2}} + \frac{Bs + C}{S^2 - 4S + 8}
$$

Desarrollamos la ecuación:

$$
6s = A(S^2 - 4S + 8) + (Bs + C)(s - \frac{5}{2})
$$

Expandiendo los términos:

$$
6s = As^2 - 4As + 8A + Bs^2 - \frac{5}{2}Bs + Cs - \frac{5}{2}C = 0
$$

Agrupamos en términos de \( S^2 \), \( S \) y términos independientes:

$$
6s = s^2(A + B) + S(-4A + C - \frac{5}{2}B) + (8A - \frac{5}{2}C) = 0
$$

### **Sistema de ecuaciones**
Organizamos el sistema de ecuaciones de 3*3

$$ A + B = 0 $$

$$ -4A + C - \frac{5}{2}B = 0 $$

$$ 8A - \frac{5}{2}C = 0 $$

#### **Solución del sistema**

De la ecuación \( A + B = 0 \):

$$
B = -A
$$

Reemplazamos en la segunda ecuación:

$$
-4A + C - \frac{5}{2}(-A) = 6
$$

$$
-4A + C + \frac{5}{2}A = 6
$$

$$
\frac{-3}{2}A + C = 6
$$

$$
C = 6 + \frac{3}{2}A
$$

Sustituyendo en la tercera ecuación:

$$
8A - \frac{5}{2}C = 0
$$

$$
8A - \frac{5}{2} (6 + \frac{3}{2}A) = 0
$$

$$
8A - 15 - \frac{15}{4}A = 0
$$

Multiplicamos por 4 para eliminar fracciones:

$$
32A - 60 - 15A = 0
$$

$$
(32 - 15)A = 60
$$

$$
17A = 60
$$

$$
A = \frac{60}{17}
$$

Hallamos \( C \):

$$
C = 6 + \frac{3}{2} \times \frac{60}{17}
$$

$$
C = 6 + \frac{180}{34}
$$

$$
C = \frac{204}{34} + \frac{180}{34}
$$

$$
C = \frac{192}{17}
$$

Ahora hallamos \( B \):

$$
B = -A = -\frac{60}{17}
$$

Finalmente, sustituimos los valores en la ecuación general:

$$
\frac{A}{S - \frac{5}{2}} + \frac{B}{S^2 - 4S + 8}
$$

$$
\frac{60}{17} \mathcal{L}^{-1} \bigg( \frac{1}{S - \frac{5}{2}} \bigg) - \frac{60}{17} \mathcal{L}^{-1} \bigg( \frac{1}{S^2 - 4S + 8} \bigg) + \frac{192}{17} \mathcal{L}^{-1} \bigg( \frac{1}{S^2 - 4S + 8} \bigg)
$$







