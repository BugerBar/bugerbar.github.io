---
layout: page
title: All post
---

<p class="message">
  Hey there! This page is included as an example. Feel free to customize it for your own use upon downloading. Carry on!
</p>

<div class="related">
  <ul class="related-posts">
    {% for post in site.posts %}
      <li>
        <h3>
          <a href="{{ post.url }}">
            {{ post.title }}
            <small>{{ post.date | date_to_string }}</small>
          </a>
        </h3>
      </li>
    {% endfor %}
  </ul>
</div>

Thanks for reading!