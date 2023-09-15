<ul>
    {% for skill in site.data.skills %}
    <li class="skill">{{ skill.name }} - {{ skill.rating }}</li>
    {% endfor %}
</ul>

