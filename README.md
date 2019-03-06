{% include masthead.md %}

### Blog Posts

{% for post in site.posts %}
-  [{{ post.title }}]({{ post.url }})
{% endfor %}

### Interests

{% include topics.md %}


