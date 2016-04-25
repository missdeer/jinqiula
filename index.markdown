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
    <li class="listing-seperator"><a href="/introduce">进球啦——国内首创的滚球推荐app</a></li>
    <li class="listing-seperator"><a href="/pay">充值续费</a></li>
    <li class="listing-seperator"><a href="/faq">常见问题</a></li>
    <li class="listing-seperator"><a href="/agent">成为代理</a></li>
    <li class="listing-seperator"><a href="/download">软件下载</a></li>
    <li class="listing-seperator"><a href="/about.html">联系我们</a></li>
  </ul>
</div>
