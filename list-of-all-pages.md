# List of All Pages

A list of all wiki pages in the RoseSMP wiki.

<ul>
  {% for pg in site.pages %}
    <li>
      <a href="{{ pg.url }}">{{ pg.title }}</a>
    </li>
  {% endfor %}
</ul>