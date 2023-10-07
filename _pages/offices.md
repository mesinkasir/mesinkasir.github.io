---
layout: default
title: Office App
permalink: /officeapp/
cover: /assets/img/aplikasi%20kasir%20toko%20penjualan%20retail%20gorsir%20plus%20website%20(1).jpg
description: Aplikasi invoice,aplikasi inventori,aplikasi akuntansi accounting lengkap disini .
---

<div class="container">  
  <div class="row py-3 justify-content-center">
 {% for acc in site.categories.offices %}
  <div class="col-md-3 p-1 col-12">
      <a class="card p-1 text-center bg-light text-dark" href="{{ acc.url }}">
      <img class="img-fluid card" alt="{{ acc.title }}" src="{{ acc.cover }}"/>
      <main class="card-body p-1">
      <h3 class="card-title info">{{ acc.title }}</h3>
      <p class="card-content info"><small>{{ acc.description }}<br/>{{ acc.author }}</small></p>
      </main>
      </a>
      </div>
    {% endfor %}
 </div>
  </div>
