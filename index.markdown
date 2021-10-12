---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
permalink: /
---

{% assign thedate = '' %}

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} - {{ post.date | date: "%Y-%m-%d" }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
