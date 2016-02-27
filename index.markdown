---
layout: default
---

<div>
  <ul class="listing">
  {% for post in site.posts limit: 1 %}
  <article class="content">
    <section class="title">
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    </section>
    <section class="meta">
 </section>
    <section class="post">
    {{ post.content }}
    </section>
    </article>
  {% endfor %}
  </ul>
  <div class="divider"></div>
  <ul class="listing main-listing">
    <li class="listing-seperator"><a href="/2016/02/27/download.html">软件下载</a></li>
    <li class="listing-seperator"><a href="/2016/02/27/pay.html">充值续费</a></li>
    <li class="listing-seperator"><a href="/2016/02/27/faq.html">常见问题</a></li>
    <li class="listing-seperator"><a href="/about.html">联系我们</a></li>
  </ul>
</div>
