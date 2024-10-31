
```markdown
---
layout: home
title: "Avatansh's Blog"
---

# Welcome to My Blog

Here you'll find various posts and guides.

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
    </li>
  {% endfor %}
</ul>
```