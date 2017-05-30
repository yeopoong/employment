<ul>
  {% for post in site.posts %}
    <li>
      <a href="/employment/{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
