---
layout: default
---
<h1>The Team</h1>
{% for profile in site.profiles %}
<li>
    <h2>{{ profile.name }}</h2>
    <h3>{{ profile.position}}</h3>
    <p>{{ profile.content }}</p>
    </li>
{% endfor %}
