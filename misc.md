---
layout: default
title: "Misc. Posts"
description: An archive of Toxic's miscellaneous posts.
---

# Miscellaneous Posts

{% assign doclist = site.pages | sort: 'date' | reverse %}
 <ul>
    {% for doc in doclist %}
         {% if doc.url contains '/misc/' %}
             <li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.title }} - {{ doc.date }}</a></li>
         {% endif %}
     {% endfor %}
 </ul>
