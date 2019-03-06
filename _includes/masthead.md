
![{% if user.name %}{{ user.name }}{% else %}{{ user.login }}{% endif %}]({{ user.avatar_url }})

## {% if user.name %}{{ user.name }}{% else %}{{ user.login }}{% endif %}

{{ user.bio }}

    {% if user.name %}
        [@{{ user.login }}](https://github.com/{{ user.login }})
    {% endif %}

    {% if user.email %}
        [{{ user.email }}](mailto:{{ user.email }})
    {% endif %}

    {% if user.location %}
        {{ user.location }}
    {% endif %}


