---
layout: default
---

Welcome to my blog 🌱  
Here I will document my learning journey in the world of Artificial Intelligence and Machine Learning.

---

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <em>{{ post.date | date: "%B %d, %Y" }}</em>
    </li>
  {% endfor %}
</ul>

