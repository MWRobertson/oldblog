{{ user.bio }}

    {% if user.name %}
        {% octicon mark-github height:20%}
        [@{{ user.login }}](https://github.com/{{ user.login }})
    {% endif %}

    {% if user.email %}
        {% octicon mail height:20%}
        [{{ user.email }}](mailto:{{ user.email }})
    {% endif %}

    {% if user.location %}
        {% octicon location height:20%}
        {{ user.location }}
    {% endif %}

