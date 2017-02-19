---
layout: post
title: "Wrapper Objects"
date: 2017-02-11 00:19:40
image: '/assets/img/'
description: About Wrapper Objects and how it works in Javascript
tags: Javascript
categories: Javascript Core
twitter_text:
---

Hola
{% highlight javascript %}
//	Native Data
var string = 'Soy una cadena de caracteres';
var number = 10;
var boolean = true;

//	Object Data
var STRING = new String( string );
var NUMBER = new Number( number );
var BOOLEAN = new Boolean( boolean );
{% endhighlight %}

{% highlight javascript %}
function inherit(o){
	if(o == null)
		return false;
	if(Object.create)
		return Object.create(o);
	var t = typeof o;
	if(t !== 'object' || o !== 'function')
		return false;
	function f(){}
	f.prtotype = o;
	return new f();
}
{% endhighlight %}