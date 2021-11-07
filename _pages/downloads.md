---
layout: default
permalink: /downloads/
---

## Vorige Preke

Hier kan jy ons vorige opnames aflaai en saam jou neem:
<br>
<br>
<div class="row">
{% for item in site.data.preke %}
  <div class="col-md-4 mb-5">
    <div class="card"> 
      <div class="card_container">
        <h4><b>{{ item.title }}</b></h4> 
        <p>{{ item.description }}</p> 
        <a class="btn btn-primary btn-sm" href="#">Download</a>
      </div>
    </div>
  </div> 
{% endfor %}
</div>
