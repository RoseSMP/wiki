# Meta
<!---

NOTE TO CONTRIBUTORS: 
Do NOT edit the meta pages. Contributors should only be modifying the lore pages. If your edits include changes to these pages they will most likely not be accepted, or the changes to files in /meta will be reverted.

--->
All the `meta` pages include things about the wiki itself, and are not in the actual lore. They help people to contribute to the wiki, or other important information that isn't part of the lore.

Here's a list of all the useful pages here you might need:

<ul>
  {% for pg in site.pages %}
      {% if pg.url contains 'meta' %}
    <li>
      <a href="{{ pg.url }}">{{ pg.title }}</a>
    </li>
      {% endif %}
  {% endfor %}
</ul>
