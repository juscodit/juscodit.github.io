---
layout: default
title: Categories
---

<div id="home">
  <ul class="cats">
    <li><span class="catname">Numerical Optimization (NPTEL)</span>
      <ul class="posts">
        {% for post in site.categories.nnumop %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      </ul>
    </li>

    <li><span class="catname">Machine Learning</span>
      <ul class="posts">
        {% for post in site.categories.ml %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      </ul>
    </li>

    <li><span class="catname">Algorithm</span>
      <ul class="posts">
        {% for post in site.categories.algo %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      </ul>
    </li>

    <li><span class="catname">Data Structure</span>
      <ul class="posts">
        {% for post in site.categories.ds %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      </ul>
    </li>

    <li><span class="catname">Programming</span>
      <ul class="posts">
        {% for post in site.categories.prog %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      </ul>
    </li>

    <li><span class="catname">Arch Linux (Arch is the BEST !)</span>
      <ul class="posts">
        {% for post in site.categories.arch %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      </ul>
    </li>

  </ul>
</div>