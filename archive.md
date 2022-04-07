---
layout: default
title: Archive List
permalink: /archive/
cover: /assets/img/aplikasi%20kasir%20toko%20penjualan%20retail%20gorsir%20plus%20website%20(1).jpg
description: blog informasi Mesin kasir toko minimarket supermarket. Mesin kasir restoran cafe kuliner. Mesin kasir online
---

<div class="container">  
  {% for tag in site.tags %}
  <div class="row py-3 justify-content-center">
  <h3 class="text-center">{{ tag[0] }}</h3>
    {% for post in tag[1] %}
    <div class="col-md-3 p-1 col-6">
      <a class="card p-1 text-center bg-light text-dark" href="{{ post.url }}">
      <img class="img-fluid card" alt="{{ post.title }}" src="{{ post.cover }}"/>
      <main class="card-body p-1">
      <h3 class="card-title info">{{ post.title }}</h3>
      <p class="card-content info"><small>{{ post.description }}<br/>{{ post.author }}</small></p>
      </main>
      </a>
      </div>
    {% endfor %}
  </div>
{% endfor %}

</div>