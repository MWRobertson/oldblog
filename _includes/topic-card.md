{% if topic.web_url %}
- {% if topic.image_url %} ![{{ topic.name }}]({{ topic.image_url }}){% endif %} [{{ topic.name }}]({{ topic.web_url }})
{% else %}
- {{ topic.name }}
{% endif %}
