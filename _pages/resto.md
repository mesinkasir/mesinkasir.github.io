---
layout: default
title: Resto App
permalink: /restoapp/
cover: /assets/img/aplikasi%20kasir%20toko%20penjualan%20retail%20gorsir%20plus%20website%20(1).jpg
description: Aplikasi restoran lengkap hanya disini untuk kuliner rumah makan cafe.
---

<div class="container">  
  <div class="row py-3 justify-content-center">
 {% for resto in site.categories.restos %}
  <div class="col-md-3 p-1 col-6">
      <a class="card p-1 text-center bg-light text-dark" href="{{ resto.url }}">
      <img class="img-fluid card" alt="{{ resto.title }}" src="{{ resto.cover }}"/>
      <main class="card-body p-1">
      <h3 class="card-title info">{{ resto.title }}</h3>
      <p class="card-content info"><small>{{ resto.description }}<br/>{{ resto.author }}</small></p>
      </main>
      </a>
      </div>
    {% endfor %}
 </div>
  </div>
