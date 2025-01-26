---
usemathjax: true
title: Galeria de posibilidades de Github Pages
---

Esta página es una demostracion de posibles capacidades para una web hecha en Markdown-Jekyll.

## Imagen en nuestra propia estructura web

![Proporcion cordobesa](curso20162017/extra800dam.gif)

## Imagen en una localización externa (en otro dominio)
No es una práctica recomendada y deberíamos evitarla en lo posible.

![Definicion de triangulos](https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Euler_diagram_of_triangle_types_es.svg/1920px-Euler_diagram_of_triangle_types_es.svg.png){: width="550" }

## Videos de Youtube

<iframe width="560" height="315" src="https://www.youtube.com/embed/BUA0tX_ZxMY?si=L_aT3IwHE92OEOPF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Expresiones matemáticas en Latex

$$  K(a,b) = \int \mathcal{D}x(t) \exp(2\pi i S[x]/\hbar)  $$


$$
      \huge  i\hbar \frac{\partial \Psi(x,t)}{\partial t} = -\frac{\hbar^2}{2m} \frac{\partial^2 \Psi(x,t)}{\partial x^2} + V(x,t)\Psi(x,t)
$$

# Un fichero de geogebra Online

Este es un ejemplo de cómo incrustar un archivo GeoGebra:

<div id="geogebra"></div>
<script>
  var applet = new GGBApplet({
    "filename": "https://www.geogebra.org/material/iframe/e2vzakjh",
    "showToolbar": true,
    "showAlgebraInput": true,
    "showMenuBar": true
  }, true);
  applet.inject('geogebra');
</script>
<script src="https://cdn.geogebra.org/apps/deployggb.js"></script>


## Código fuente 

```java
System.out.println("Hola Mundo");
```

{% highlight python linenos %}
# Abrir un fichero en modo lectura
with open('archivo.txt', 'r') as f:
    for linea in f:
        print(linea.strip())
{% endhighlight %}




