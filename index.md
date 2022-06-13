under construction!!!

## Blog Posts
<hr>
<br>
{% assign doclist = site.pages | sort: 'date' | reverse %}
 <ul>
    {% for doc in doclist %}
         {% if doc.url contains '/posts/' %}
             <li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.title }} - {{ doc.date }}</a></li>
         {% endif %}
     {% endfor %}
 </ul>
