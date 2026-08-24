---
title: "Clase 2 — Regresión lineal simple"
permalink: /clases/clase-2/
---

<div class="hero" style="min-height:140px;">
  <div class="hero-inner">
    <h1 style="font-size:1.9rem;">Clase 2</h1>
    <div class="hero-rule"></div>
    <div class="hero-role">Regresión lineal simple: MCO y supuestos clásicos</div>
  </div>
</div>

<main style="padding-top:20px;">

## Explicación

El modelo de regresión lineal simple estima la relación entre una variable
dependiente Y y una variable explicativa X mediante Mínimos Cuadrados
Ordinarios (MCO). Repasamos los supuestos de Gauss-Markov y qué implica
cada uno para que el estimador sea BLUE (mejor estimador lineal insesgado).

- [📑 Diapositivas de la clase](../../materiales/clase-2-slides.pdf)
- [📊 Dataset de ejemplo](../../materiales/clase-2-datos.csv)

## Práctica guiada
{: #practica-guiada}

```r
modelo <- lm(y ~ x, data = datos)
summary(modelo)
plot(datos$x, datos$y, col = "#0A1930", pch = 19)
abline(modelo, col = "#E4007C", lwd = 2)
```

## Práctica independiente
{: #practica-independiente}

1. Estimá el modelo con tu propio dataset y reportá los coeficientes.
2. Interpretá el R² y la significancia de los parámetros.
3. Verificá gráficamente el supuesto de linealidad.

</main>
