# UNDERTOW

<hr>

### Blog

View the top three most recent posts below, or view the full archive <a href="https://toxic-013.github.io/ToxBlog/blog/">here</a>.

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

### Book Catalogue

A catalogue of my books can be found <a href="https://toxic-013.github.io/ToxBlog/book-list/">here</a>.

I wrote them all myself, and I hope you'll read them!

<hr>

### Misc Posts

Are you having fun yet?
if not, here's a link to all my <a href=https://toxic-013.github.io/ToxBlog/miscellaneous/>misc posts</a>.
