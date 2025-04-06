---
layout: home
title: jridev - Welcome to My Blog
---

# Welcome to jridev's Blog! 🚀

Hello, and welcome to **jridev's** personal blog! This is where I share my journey in coding, learning, and everything tech. I write about projects I’m working on, interesting coding challenges, and tips I pick up along the way. 

## Latest Posts 📝

Here are my most recent posts:

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
      <p><small>Published on {{ post.date | date: "%B %d, %Y" }}</small></p>
    </li>
  {% endfor %}
</ul>

---

Thanks for visiting **jridev's** blog! Stay tuned for more posts and updates. 🎉

&copy; 2025 **jridev**
