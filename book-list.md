---
layout: default
title: Books
description: A catalogue of Toxic's books.
---

{% assign doclist = site.pages | sort: 'date' | reverse %}
 <ul>
    {% for doc in doclist %}
         {% if doc.url contains '/books/' %}
             <li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.title }}</a><br>
               Description: {{ doc.description }}<br>
               Publish date: {{ doc.date }}
             </li>
         {% endif %}
     {% endfor %}
 </ul>
