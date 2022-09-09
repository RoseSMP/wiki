# List of All Pages

A list of all wiki pages in the RoseSMP wiki.



{% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
{% endfor %}