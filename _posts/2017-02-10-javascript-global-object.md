---
layout: post
title: "Javascript Global Object"
date: 2017-02-10 23:57:09
image: '/assets/img/'
description: About global object in Javascript, how it works
tags: Javascript
categories: JS
twitter_text:
---

El objeto global en JS es un Objeto regular de Javascript que sirve para un importante proposito:  las propiedades de este objeto son definidas globales que estan disponibles para todo el programa JS. Cuando el interprete de JS inicia (o cuando el navegador web carga una nueva pagina), esta crea un objeto global y le da un conjunto de propiedades iniciales:

Propiedades globales como <b>undefined</b>, <b>Infinity</b> y <b>NaN</b>
Funciones globales como <b>isNaN()</b>, <b>parseInt()</b> y <b>eval()</b>
Funciones constructoras como <b>Date()</b>, <b>RegExp()</b>, <b>String()</b>, <b>Object</b> y <b>Array()</b>

{% highlight javascript %}
//	Define a global variable para referirse al objeto global
var global = this;
//	Global object property
y = 'Soy una propiedad del objeto global.'
//	Normal property
var x = 'Yo no soy propiedad del objeto global';
{% endhighlight %}
