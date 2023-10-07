---
layout: default
title: Source Code Free
permalink: /sourcecodefree/
cover: /assets/img/aplikasi%20kasir%20toko%20penjualan%20retail%20gorsir%20plus%20website%20(1).jpg
description: Free download source code dan aplikasi gratis full version.
---

<div class="container">  
  <div class="row py-3 justify-content-center">
 {% for sc in site.categories.sourcecode %}
  <div class="col-md-3 p-1 col-6">
      <a class="card p-1 text-center bg-light text-dark" href="{{ sc.url }}">
      <img class="img-fluid card" alt="{{ sc.title }}" src="{{ sc.cover }}"/>
      <main class="card-body p-1">
      <h3 class="card-title info">{{ sc.title }}</h3>
      <p class="card-content info"><small>{{ sc.description }}<br/>{{ sc.author }}</small></p>
      </main>
      </a>
      </div>
    {% endfor %}
 </div>
  </div>
