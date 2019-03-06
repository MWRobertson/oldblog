{% assign content = page.content | strip_newlines %}
{% assign posts_total = site.posts | size %}
{% assign user = site.github.owner %}

{% include topsection.html %}
{% include bottomsection.html %}
