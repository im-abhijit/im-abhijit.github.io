## Debug

Posts: {{ site.posts.size }}

{% for post in site.posts %}
- {{ post.title }}
- {{ post.url }}
{% endfor %}
