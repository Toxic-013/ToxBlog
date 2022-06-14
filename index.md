# ToxBlog

**Welcome to my site fuckers!!!!!**

<hr>

### Blog Posts

View the top 5 most recent posts below, or view the full archive <a href="https://toxic-013.github.io/ToxBlog/blog/">here</a>.

{% assign doclist = site.pages | sort: 'date' | reverse %}
 <ul>
    {% for doc in doclist limit:5 %}
         {% if doc.url contains '/posts/' %}
             <li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.title }} - {{ doc.date }}</a></li>
         {% endif %}
     {% endfor %}
 </ul>
 <center><a href="https://toxic-013.github.io/ToxBlog/blog/"><i><b>(view all posts)</b></i></a></center>

<br>
<hr>

### Books

A catalogue of my books can be found <a href="https://toxic-013.github.io/ToxBlog/book-list/">here</a>.
