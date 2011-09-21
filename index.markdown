---
layout: default
title: What is autotest?
---

<p>Autotest is a framework for fully automated testing. It is designed
primarily to test the Linux kernel, though it is useful for many other
functions such as qualifying new hardware. It's an open-source project under
the GPL and is used and developed by a number of organizations, including
Google, IBM, Red Hat, and many others.</p>

<div class="bootcamp-help">
  <h1>Resources
  </h1>
  <div class="bootcamp-body">
  <ul>
    <li class="setup">
      <a href="https://github.com/autotest/autotest">
        <div class="image">&nbsp;</div>
        <div class="desc">
          <h2>Source</h2>
        </div>
      </a>
    </li>
    <li class="create-a-repo">
      <a href="https://github.com/autotest/autotest/issues">
        <div class="image">&nbsp;</div>
        <div class="desc">
          <h2>Issues</h2>
        </div>
      </a>
    </li>
    <li class="fork-a-repo">
      <a href="https://github.com/autotest/autotest/wiki">
        <div class="image">&nbsp;</div>
        <div class="desc">
          <h2>Wiki</h2>
        </div>
      </a>
    </li>
    <li class="be-social">
      <a href="https://github.com/autotest/autotest/downloads">
        <div class="image">&nbsp;</div>
        <div class="desc">
          <h2>Downloads</h2>
        </div>
      </a>
    </li>
  </ul>
  </div> <!-- /bootcamp-body -->
</div>

<div class="list-module">
  <h2>News</h2>
  <div class="list-body">
    <ul>
      {% for post in site.categories.news reversed %}
        <li>
          <a href="{{ post.url }}" id="{{ cat }}">
            <h3>{{ post.title }}</h3>
            <p>{{ post.description }}</p>
          </a>
        </li>
      {% endfor %}
    </ul>
  </div>
</div>