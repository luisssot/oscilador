# Resolución de la Ecuación de Schrödinger con Múltiples Barreras en Python

Este proyecto resuelve la ecuación de Schrödinger unidimensional estacionaria para una partícula cuántica enfrentando múltiples barreras de potencial rectangulares. Utiliza el método de diferencias finitas para obtener los niveles de energía y funciones de onda.

## 📘 Descripción

La ecuación de Schrödinger estacionaria que se resuelve es:

\[
-\frac{\hbar^2}{2m} \frac{d^2\psi}{dx^2} + V(x)\psi = E\psi
\]

El potencial \( V(x) \) puede contener un número arbitrario de barreras rectangulares, definidas por su posición, ancho y altura.

## 🧰 Requisitos

Este programa requiere Python 3 y las siguientes bibliotecas:

- `numpy`
- `scipy`
- `matplotlib`

Instálalas con:

```bash
pip install numpy scipy matplotlib
