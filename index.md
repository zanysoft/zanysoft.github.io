## Welcome to Zanysoft

### My GitHub Projects
<ul>
  {% for repo in site.github.public_repositories %}
    {% if repo.name != "zanysoft.github.io" %}
      <li><a href="{{ repo.html_url }}">{{ repo.name }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

```json
{{ site.github }}
```

