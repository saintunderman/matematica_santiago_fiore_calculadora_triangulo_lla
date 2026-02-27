# Calculadora de Triángulos LLA

[![Licencia: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
![Version: 1.0](https://img.shields.io/badge/Version-1.0-blue)
![Language: HTML/JS](https://img.shields.io/badge/Language-HTML%2FJS-orange)

Una herramienta educativa diseñada para resolver el **caso ambiguo (LLA)** del Teorema del Seno. Desarrollada por **Santiago Fiore**, esta calculadora no solo entrega resultados numéricos, sino que ofrece un desarrollo matemático paso a paso y una representación visual dinámica.


## Características Principales

* **Resolución del Caso Ambiguo**: Identifica automáticamente si existe una solución única, dos soluciones (caso ambiguo) o si el triángulo es imposible.
* **Precisión Geométrica**: Implementación de lógica basada en épsilon ($\epsilon$) para manejar imprecisiones infinitesimales en cálculos de punto flotante de 64 bits.
* **Desarrollo Matemático**: Renderizado de fórmulas en tiempo real utilizando **MathJax** para una visualización académica clara.
* **Visualización Dinámica**: Generación de gráficos mediante un motor de renderizado en `<canvas>` que escala el triángulo proporcionalmente según los resultados.
* **Responsive Design**: Interfaz moderna construida con CSS nativo, optimizada para dispositivos móviles y escritorio.

## Tecnologías Utilizadas

* **HTML5 & CSS3**: Estructura y diseño basado en variables modernas y Grid Layout.
* **JavaScript (Vanilla)**: Motor lógico de cálculo trigonométrico y manipulación del DOM.
* **MathJax**: Motor de visualización para notación matemática LaTeX.
* **Canvas API**: Para la representación gráfica vectorial del triángulo.

## Lógica de Cálculo

El sistema evalúa la relación entre el ángulo dado $A$, el lado opuesto $a$ y el lado adyacente $b$, considerando la altura $h = b \cdot \sin(A)$:

## Instalación y Uso

No requiere dependencias externas ni compilación. 

https://saintunderman.github.io/matematica_santiago_fiore_calculadora_triangulo_lla/

## Licencia y Créditos

Desarrollado por **Santiago Fiore**.

* **Sitio Web:** https://sites.google.com/view/santiago-fiore/portada
* **Licencia:** Creative Commons CC BY-NC-SA 4.0 (Atribución-NoComercial-CompartirIgual).
