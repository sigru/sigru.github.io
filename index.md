## Personal Blog

coming soon

## My posts

<ul>
  {% for post in site.posts %}
      {{ post.excerpt }}
      <a href="{{ post.url }}">More</a>

  {% endfor %}
</ul>
