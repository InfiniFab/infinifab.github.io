---
title: "Les projets IF"
permalink : /projets/
pageurl : https://github.com/InfiniFab/infinifab.github.io/blob/master/projets.md
---

L'essence d'un fablab est de produire une multitude projet, et bien sur de les partager pour permettre aux personnes qui le souhaitent de reproduire ces projets

2 critères ont été choisi pour qualifier les ateliers :

![](/asset/icon ateliers/acc1.png){: width="20px"} ![](/asset/icon ateliers/acc2.png){: width="20px"} ![](/asset/icon ateliers/acc3.png){: width="20px"} : L'avancement du projet

![](/asset/icon ateliers/diff1.png){: width="20px"} ![](/asset/icon ateliers/diff2.png){: width="20px"} ![](/asset/icon ateliers/diff3.png){: width="20px"} : La complexité estimée à réaliser le projet

<div align="center">
  {% for post in site.posts %}
    {% if post.tag == "projet" %}
    
    <div class="div-class">
    <a href="{{post.permalink}}">
    <table class="tableau-atelier"><thead>
      <tr>
        <th colspan="2"><p class="min-atelier-titre">{{post.title }}</p></th>
        <th width="150px"><img  class="icon-atelier"  src="{{post.avc}}" /><img  class="icon-atelier"  src="{{post.diff}}" /></th>
      </tr></thead>
    <tbody>
      <tr>
        <td colspan="3"><img  class="mini-atelier"  src="{{post.image}}" /></td>
      </tr>
      <tr>
        <td class="mini-atelier-desc" colspan="3">{{post.description }}</td>
      </tr>
    </tbody>
    </table>
    </a>
    </div>
    
  {% endif %}
  {% endfor %}
</div>

<!-- 
{% for post in site.posts %}
{% if post.tag == "projet" %}{: .listateliers}
|  |
| [![]({{post.image}}){: height="150px"}]({{ post.url }}) |
|  |
| {{post.description}}|
|  | 
{% endif %}
{% endfor %}
 -->