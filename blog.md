---
layout: page
title: Blog
permalink: /blog/
---

<section>
  <div class="home">
    <h1 class="page-heading">Posts</h1>

    <ul class="post-list">
      {% for post in site.posts %}
        <li>
          <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

          <h2>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          </h2>
        </li>
      {% endfor %}
    </ul>

    <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
  </div>

<nav>
<ul>
  <li><a href="/"><span class="fa fa-info-circle fa-3x about"></span></a></li>
  <li><a href="/blog/"><span class="fa fa-pencil fa-3x blog"></span></a></li>
  <li><a href="/portfolio/"><span class="fa fa-folder-open fa-3x portfolio"></span></a></li>
  <li><a href="/resume/"><span class="fa fa-spinner fa-3x resume"></span></a></li>
</ul>
</nav>
</section>