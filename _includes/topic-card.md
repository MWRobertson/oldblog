{% if topic.web_url %}
- [{{ topic.name }}]({{ topic.web_url }}) 
{% else %}
- {{ topic.name }} 
{% endif %}
