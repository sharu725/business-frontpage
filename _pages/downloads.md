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
          <a type="button" id="download-url" class="btn btn-primary btn-block" href="https://cdn-142.anonfiles.com/f5v9w2E9xf/43f42d35-1643445953/20220130-final.mp4">                    <img src="/img/file/filetypes/mime/video_unknown.png?1597404212"> Download
                    (708.72 MB)</a>
        </div>
      </div>
    </div> 
  </div>
{% endfor %}
