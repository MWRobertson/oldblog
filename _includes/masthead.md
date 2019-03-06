![{% if user.name %}{{ user.name }}{% else %}{{ user.login }}{% endif %}]({{ user.avatar_url }})

## {% if user.name %}{{ user.name }}{% else %}{{ user.login }}{% endif %}

{{ user.bio }}

    {% if user.name %}
        {% octicon mark-github height:20 class:"mr-2 v-align-middle" fill:{{ icon_color }} aria-label:GitHub %}
        [@{{ user.login }}](https://github.com/{{ user.login }})
    {% endif %}

    {% if user.email %}
        {% octicon mail height:20 class:"mr-2 v-align-middle" fill:{{ icon_color }} aria-label:email %}
        [{{ user.email }}](mailto:{{ user.email }})
    {% endif %}

    {% if user.location %}
        {% octicon location height:20 class:"mr-2 v-align-middle" fill:{{ icon_color }} aria-label:Location %}
        {{ user.location }}
    {% endif %}


