---
layout: default
title: Books
description: A catalogue of Toxic's books.
---

{% assign doclist = site.pages | sort: 'date' | reverse %}
 <ul>
    {% for doc in doclist %}
         {% if doc.url contains '/books/' %}
             <li><a href="{{ doc.docslink }}" target="_blank">{{ doc.title }}</a><br>
               Description: {{ doc.description }} 
             </li>
         {% endif %}
     {% endfor %}
 </ul>
