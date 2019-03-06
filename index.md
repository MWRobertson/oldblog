{% assign content = page.content | strip_newlines %}
{% assign posts_total = site.posts | size %}
{% assign user = site.github.owner %}

{% include blogposts.html %}

{% include masthead.html metadata=true %}
