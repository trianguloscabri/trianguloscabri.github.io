---
usemathjax: true
layout: post
title: Markdown para matemáticos en Github Pages
---


## **Markdown** básico

Los aspectos más básicos del [Markdown](https://www.markdownguide.org/cheat-sheet/) pueden ser encontrados por internet fácilmente, esta página se centra sobre todo en intentar añadir elementos un poco más complejos a un Markdown y la página html que posteriormente genera Jekyll.

## Presentar información en una **Tabla**

|          | Lunes | Miércoles | Viernes |
| :------: | :---: | :-------: | :-----: |
| opcion 1 |       |           |    x    |
| opción 2 |       |     x     |         |
| opcion 3 |   x   |           |    x    |


## **Imagen** en nuestra propia estructura web.

![zorrito](./demoFiles/3827f3b6832fba42dfe18bb3b470b5c6.jpg)


## **Imagen** en una localización externa.

Una imagen en otro dominio no es una práctica recomendada y deberíamos evitarla en lo posible.

![Definicion de triangulos](https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Euler_diagram_of_triangle_types_es.svg/1920px-Euler_diagram_of_triangle_types_es.svg.png)


## **Videos** de Youtube

<iframe width="560" height="315" src="https://www.youtube.com/embed/BUA0tX_ZxMY?si=L_aT3IwHE92OEOPF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## **Expresiones matemáticas** en Latex

$$  K(a,b) = \int \mathcal{D}x(t) \exp(2\pi i S[x]/\hbar)  $$


$$
      \huge  i\hbar \frac{\partial \Psi(x,t)}{\partial t} = -\frac{\hbar^2}{2m} \frac{\partial^2 \Psi(x,t)}{\partial x^2} + V(x,t)\Psi(x,t)
$$


## **Código fuente** 

Imprimir un "Hola Mundo" con Java
```java
System.out.println("Hola Mundo");
```

Abrir un fichero con Python
{% highlight python linenos %}
with open('archivo.txt', 'r') as f:
    for linea in f:
        print(linea.strip())
{% endhighlight %}


## Contar historias con **emojis**

<div style="font-size:2.5em;">❓🙏😇✌️🤝🟰🙋‍♀️👀💀🔨🤷‍♂️🧾😶👭🤫</div>


## Un fichero de **Geogebra** local


<script src="https://cdn.geogebra.org/apps/deployggb.js"></script>
<div id="geogebra" style="width: 800px; height: 600px;"></div>
<script>
var applet = new GGBApplet({
"filename": "demoFiles/material-fpgkybfj.ggb", // Cambia esto según la ubicación de tu archivo
"showToolbar": true,
"showAlgebraInput": true,
"showMenuBar": true
}, true);
applet.inject('geogebra');
</script>




