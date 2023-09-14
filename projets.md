---
title: "Les projets IF"
permalink : /projets/
pageurl : https://github.com/InfiniFab/infinifab.github.io/blob/master/projets.md
---

L'essence d'un fablab est de produire une multitude projet, et bien sur de les partager pour permettre aux personnes qui le souhaitent de reproduire ces projets


{% for post in site.posts %}
{% if post.tag == "projet" %}{: .listateliers}
 

|  |
| [![]({{post.image}}){: height="150px"}]({{ post.url }}) |
|  |
| {{post.description}}|
|  |


 
{% endif %}
{% endfor %}
