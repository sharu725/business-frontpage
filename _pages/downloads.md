---
layout: default
permalink: /downloads/
---

## Vorige Preke

Hier kan jy ons vorige opnames aflaai en saam jou neem:
<br>
<br> 
{% for item in site.data.preke %}
  <div class="row">
    <div class="col-md-12 mb-5">
      <div class="card"> 
        <div class="card_container">
          <h4><b>{{ item.title }}</b></h4> 
          <p>{{ item.description }}</p> 
          <a class="btn btn-primary btn-sm download_link" href="https://anonfiles.com/d8q1d8E0x5/20220123-final_mp4" id="{{ item.date }}" download>Download</a>
        </div>
      </div>
    </div> 
  </div>
{% endfor %}
