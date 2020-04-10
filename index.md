---
---

<ul>
{% for gamepad in site.gamepads %}
  <li><a href="{{ gamepad.url | relative_url }}">{{ gamepad.brand }} {{ gamepad.model }}</a></li>
{% endfor %}
</ul>

[Update this page on GitHub](https://github.com/denilsonsa/gamepad-cheatsheet)
