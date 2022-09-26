Olá, sou Pedro Schmalz, mestrando no DCP-USP, e aqui apresentarei visualizações e resultados
de alguns projetos em que estou envolvido. Espero que gostem!


<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>

<h1 class="entry-title">
    <a href="{{ root_url }}{{ page.url }}">{{ page.title }}</a>
</h1>
{% if post.title %}
  <h1 class="entry-title">
    <a href="{{ root_url }}{{ post.url }}">{{ post.title }}</a>
  </h1>      
{% endif %}
<div class="entry-content">{{ content }}</div>
