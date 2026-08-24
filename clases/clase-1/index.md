---
title: "Clase 1 — Introducción a la econometría"
permalink: /clases/clase-1/
---

<div class="hero" style="min-height:140px;">
  <div class="hero-inner">
    <h1 style="font-size:1.9rem;">Clase 1</h1>
    <div class="hero-rule"></div>
    <div class="hero-role">Introducción a la econometría y repaso de probabilidad</div>
  </div>
</div>

<main style="padding-top:20px;">

## Explicación

<!-- Reemplazá este bloque con tu contenido: teoría, diapositivas o video embebido -->
La econometría combina teoría económica, matemática y estadística para
estimar relaciones y contrastar hipótesis a partir de datos. En esta clase
repasamos los conceptos de variable aleatoria, esperanza, varianza y
distribución muestral que sirven de base para el modelo de regresión lineal.

- [📑 Diapositivas de la clase](../../materiales/clase-1-slides.pdf)
- [📊 Dataset de ejemplo](../../materiales/clase-1-datos.csv)

## Práctica guiada
{: #practica-guiada}

<!-- Acá va tu script comentado paso a paso (R, Python o Stata) -->
```r
# Ejemplo: simulación de una muestra aleatoria
set.seed(123)
x <- rnorm(100, mean = 50, sd = 10)
hist(x, main = "Distribución muestral", col = "#E4007C")
```

## Práctica independiente
{: #practica-independiente}

1. Descargá el dataset de la clase y calculá media, varianza y desvío estándar.
2. Graficá el histograma y comentá la forma de la distribución.
3. Subí tu script a la carpeta de entregas (o al aula virtual).

</main>
