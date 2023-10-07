---
layout: default
title: Web Development
permalink: /webdevelopment/
cover: /assets/img/aplikasi%20kasir%20toko%20penjualan%20retail%20gorsir%20plus%20website%20(1).jpg
description: Pembuatan website murah dan lengkap dengan technologyy modern terbaru.
---

<div class="container">  
  <div class="row py-3 justify-content-center">
 {% for web in site.categories.websites %}
  <div class="col-md-3 p-1 col-6">
      <a class="card p-1 text-center bg-light text-dark" href="{{ web.url }}">
      <img class="img-fluid card" alt="{{ web.title }}" src="{{ web.cover }}"/>
      <main class="card-body p-1">
      <h3 class="card-title info">{{ web.title }}</h3>
      <p class="card-content info"><small>{{ web.description }}<br/>{{ web.author }}</small></p>
      </main>
      </a>
      </div>
    {% endfor %}
 </div>
  </div>
