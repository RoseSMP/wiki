# List of All Pages

A list of all wiki pages in the RoseSMP wiki.

<!-- NOTE TO CONTRIBUTORS: This page auto-generates itself thanks to the magic of Jekyll and Liquid. DO NOT EDIT IT!!! -->

<ul>
  {% for pg in site.pages %}
    <li>
      {% if pg != '' %}
      {% unless pg.url contains 'meta' or pg.url contains 'test' or pg.url contains '404' or pg.title == '' or pg.title == 'Welcome to the RoseSMP wiki!' %}
      <a href="{{ pg.url }}">{{ pg.title }}</a>
      {% endunless %}
      {% endif %}
    </li>
  {% endfor %}
</ul>
