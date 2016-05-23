---
layout: default
---
<div class="section article">
<div class="inner">
<div class="section-content no-header">

<div class="post-content">
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.url }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>
</div>

</div><!--  / .section-content /  -->
</div><!--  / .inner /  -->
</div><!--  / .article /  -->