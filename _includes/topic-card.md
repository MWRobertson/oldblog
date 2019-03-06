{% if topic.web_url %}
- {% if topic.image_url %} <img src={{ topic.image_url }} width="64" height="64" alt={{ topic.name }}>{% endif %} [{{ topic.name }}]({{ topic.web_url }}) 
{% else %}
- {{ topic.name }} 
{% endif %}
