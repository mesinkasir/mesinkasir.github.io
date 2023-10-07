---
layout: default
title: Toko POS App
permalink: /tokoapp/
cover: /assets/img/aplikasi%20kasir%20toko%20penjualan%20retail%20gorsir%20plus%20website%20(1).jpg
description: Aplikasi toko kasir penjualan lengkap hanya disini untuk toko shop minimarket barcode .
---

<div class="container">  
  <div class="row py-3 justify-content-center">
 {% for shop in site.categories.tokos %}
  <div class="col-md-3 p-1 col-6">
      <a class="card p-1 text-center bg-light text-dark" href="{{ shop.url }}">
      <img class="img-fluid card" alt="{{ shop.title }}" src="{{ shop.cover }}"/>
      <main class="card-body p-1">
      <h3 class="card-title info">{{ shop.title }}</h3>
      <p class="card-content info"><small>{{ shop.description }}<br/>{{ shop.author }}</small></p>
      </main>
      </a>
      </div>
    {% endfor %}
 </div>
  </div>
