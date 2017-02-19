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

En Js existe un objeto que no necesita ser creado porque por el simple hecho de correr el programa ya existe, este
objeto se le conoce como 'Global Object', al igual que los demas objetos tiene propiedades y es por esa razon que cuando
creas una varialble en Js sin la palabra reservada 'var' o 'function' esta pasa a formar una propiedad del Objeto Global

{% highlight javascript %}
//	Global object property
y = 'Soy una propiedad del objeto global.'
//	Normal property
var x = 'Yo no soy propiedad del objeto global';
{% endhighlight %}
