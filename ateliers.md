---
title: "Les ateliers IF"
permalink : /ateliers/
pageurl : https://github.com/InfiniFab/infinifab.github.io/blob/master/ateliers.md

---

Fort d'une bonne experience acquise dans les fablabs, Infini Fab propose différents ateliers pour les fablabs voulant proposer une experience nouvelle à ses utilisateurs ou bien aux acteurs et lieux locaux voulant apporter de nouvelles perspectives, proposer une découverte des fablabs et de ce qu'on y fait.


Pour vous aider choisir, 3 critères sontproposès pour qualifier les ateliers :

![](/asset/icon ateliers/1-coll.png){: width="20px"} ![](/asset/icon ateliers/2-coll.png){: width="20px"} ![](/asset/icon ateliers/3-coll.png){: width="20px"} : L'intelligence collective

![](/asset/icon ateliers/1-crea.png){: width="20px"} ![](/asset/icon ateliers/2-crea.png){: width="20px"} ![](/asset/icon ateliers/3-crea.png){: width="20px"} : La créativité

![](/asset/icon ateliers/1-prod.png){: width="20px"} ![](/asset/icon ateliers/2-prod.png){: width="20px"} ![](/asset/icon ateliers/3-prod.png){: width="20px"} : La production


Chaque ateliers proposé ci dessous vous fera découvrir le monde des fablabs ou bien explorer de nouveau domaine de ceux-ci en vous proposant la fabrication d'un objets fun et utile.


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Montserrat, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Montserrat, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>

<div align="center">
  {% for post in site.posts %}
    {% if post.tag == "atelier" %}
    <table class="tg"><thead>
      <tr>
        <th class="tg-0pky" colspan="2"><p class="titre-min-atelier">{{post.title }}</p></th>
        <th class="tg-0pky"><img  class="icon-atelier"  src="{{post.ic}}" /><img  class="icon-atelier"  src="{{post.crea}}" /><img  class="icon-atelier"  src="{{post.prod}}" /></th>
      </tr></thead>
    <tbody>
      <tr>
        <td class="tg-0pky" colspan="3"><a href="{{post.permalink}}"><img  class="mini-atelier"  src="{{post.image}}" /></a></td>
      </tr>
      <tr>
        <td class="tg-0lax" colspan="3">{{post.description }}</td>
      </tr>
    </tbody>
    </table>

    
    {% endif %}
  {% endfor %}
</div>

<!-- {% for post in site.posts %}
{% if post.tag == "atelier" %}{: .listateliers}
 
|------------------------------------+---------------------|
|{{post.description | color: blue}} |  ![]({{post.ic}}){: width="20px"} ![]({{post.crea}}){: width="20px"} ![]({{post.prod}}){: width="20px"}  |   
|------------------------------------|:-------------------:|
| [![]({{post.image}}){: width="250px"}]({{ post.url }}) |   | 
|------------------------------------+---------------------|
| ![](/asset/clock.png){: width="50px"} | {{post.temps}} |
|------------------------------------+---------------------|
 
{% endif %}
{% endfor %} -->

