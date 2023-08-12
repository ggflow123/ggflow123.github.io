{% for link in site.data.navigation.main %}
    [{{ link.title }}]({{ link.url }})
{% endfor %}
