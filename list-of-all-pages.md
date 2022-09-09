# List of All Pages

A list of all wiki pages in the RoseSMP wiki.

<ul>
    {% for doc in site.la %}
    	<li><a href="{{ doc.url }}">{{ doc.title }}</a></li>
    {% endfor %}
</ul>
