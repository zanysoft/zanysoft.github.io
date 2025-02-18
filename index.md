## Zany Soft
### My GitHub Projects

<ul>
  {% for repo in site.github.public_repositories %}
    {% if repo.name != "zanysoft.github.io" and repo.fork == false %}
      <li>
        <a href="{{ repo.html_url }}" style="margin-right: 20px" >{{ repo.name }}</a>
        <a href="https://packagist.org/packages/zanysoft/{{ repo.name }}" target="_blank">
          <img src="https://img.shields.io/packagist/dt/zanysoft/{{ repo.name }}?style=flat" >
        </a>
        <a href="https://github.com/zanysoft/{{ repo.name }}/releases" target="_blank">
          <img src="https://img.shields.io/github/v/release/zanysoft/{{ repo.name }}?sort=semver&display_name=release&style=flat" >
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

