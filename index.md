## Zany Soft
### My GitHub Projects


<ul>
  {% for repo in site.github.public_repositories %}
    {% if repo.name != "zanysoft.github.io" and repo.fork == false %}
      <li><a href="{{ repo.html_url }}">{{ repo.name }}</a>
        <img src="https://img.shields.io/packagist/dt/zanysoft/{{ repo.name }}?style=social" >
      </li>
    {% endif %}
  {% endfor %}
</ul>

