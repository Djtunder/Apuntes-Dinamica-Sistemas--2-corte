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
## 2 EJERCIO
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
