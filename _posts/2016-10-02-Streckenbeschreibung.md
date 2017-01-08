---
title: Streckenbeschreibung
background: bg6.jpg
carousel: true
---

<div id="features-carousel" class="carousel slide with-title-indicators max-height" data-height-percent="70" data-ride="carousel">

<!-- Indicators - slide navigation -->
<ol class="carousel-indicators title-indicators">

{% for teil in site.data.strecke %}
  <li data-target="#features-carousel" data-slide-to="{{ forloop.index | minus: 1 }}" {% if forloop.index == 1 %} class="active" {% else %} class="" {% endif %}>
  {{ teil.tag }}
  </li>
{% endfor %}
</ol>

<!-- Wrapper for slides -->
<div class="carousel-inner">

{% for teil in site.data.strecke %}

<!--  TAG  {{ forloop.index | minus: 1 }} -->
<div class="item {% if forloop.index == 1 %} active {% endif %}" style="">
<div class="carousel-text-content" style="">
<h2 class="title">Tag {{ teil.tag }}</h2>
{% if teil.strecke != "1000" %}
{% if teil.strecke != "0" %}<h3>{{ teil.abfahrt }}</h3>
{% else %}
<p>von {{ teil.abfahrt }} nach {{ teil.ziel }}</p>
<p>{{ teil.strecke }}km</p>
{% endif %}
{% for post in site.posts %}
{% assign test = "Beschreibung Tag " | append: teil.tag %}
  {% if post.title == test %}
  <p data-debug="{{ test }}"><a href="" onclick="populate_and_open_modal(event, 'modal-content-{{ post.wandertag }}');" class="btn btn-outline-inverse btn-sm">Details</a></p>
  <div class="content-to-populate-in-modal" id="modal-content-{{ post.wandertag }}">
        {{ post.content | markdownify }}
      </div>
<!-- script>$.vegas({ src:"/assets/images/strecke/tag{{ teil.tag }}.jpg" });</script -->

   {% endif %}
{% endfor %}
{% else %}
<h3>{{ teil.abfahrt }}</h3>
<p>{{ teil.bemerkung }}</p>
{% endif %}
</div>
</div><!-- .item -->

{% endfor %}




</div><!-- .carousel-inner -->

<!-- Controls -->
<a class="left carousel-control" href="#features-carousel" data-slide="prev"></a>
<a class="right carousel-control" href="#features-carousel" data-slide="next"></a>

</div>
