---
layout: default
title: Hardware POS set
permalink: /hardwarepos/
cover: /assets/img/aplikasi%20kasir%20toko%20penjualan%20retail%20gorsir%20plus%20website%20(1).jpg
description: Hardware perangkat kasir mesin kasir alarm security barcode touchscreen lengkap. 
---

<div class="container">  
  <div class="row py-3 justify-content-center">
 {% for pos in site.categories.hardwares %}
  <div class="col-md-3 p-1 col-12">
      <a class="card p-1 text-center bg-light text-dark" href="{{ pos.url }}">
      <img class="img-fluid card" alt="{{ pos.title }}" src="{{ pos.cover }}"/>
      <main class="card-body p-1">
      <h3 class="card-title info">{{ pos.title }}</h3>
      <p class="card-content info"><small>{{ pos.description }}<br/>{{ pos.author }}</small></p>
      </main>
      </a>
      </div>
    {% endfor %}
 </div>
  </div>
