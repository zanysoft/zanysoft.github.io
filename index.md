## Zany Soft
### My GitHub Projects
<ul>
  {% for repo in site.github.public_repositories %}
    {% if repo.name != "zanysoft.github.io" and repo.fork == false %}
      <li><a href="{{ repo.html_url }}">{{ repo.name }}</a>
      [![Downloads](https://img.shields.io/packagist/dt/zanysoft/{{ repo.name }}.svg?style=flat-square)](https://packagist.org/packages/zanysoft/{{ repo.name }})
      </li>
    {% endif %}
  {% endfor %}
</ul>

