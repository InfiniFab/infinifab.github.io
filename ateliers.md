---
title: "Les ateliers IF"
permalink : /ateliers/
pageurl : https://github.com/InfiniFab/infinifab.github.io/blob/master/ateliers.md

---
Fort d’une solide expérience acquise au sein des fablabs, **InfiniFab** propose divers ateliers à destination :  
- des fablabs souhaitant offrir une **nouvelle expérience** à leurs utilisateurs,  
- des acteurs et lieux locaux désireux d’ouvrir **de nouvelles perspectives**,  
- toute personne curieuse de **découvrir l’univers des fablabs** et leurs possibilités.  

### 🔍 **Comment choisir votre atelier ?**  

Pour mieux vous guider, chaque atelier est classé selon trois critères :  

- **L’intelligence collective**  
  ![](/asset/icon%20ateliers/col1.png){: .icon-atelier}  
  ![](/asset/icon%20ateliers/col2.png){: .icon-atelier}  
  ![](/asset/icon%20ateliers/col3.png){: .icon-atelier}  

- **La créativité**  
  ![](/asset/icon%20ateliers/crea1.png){: .icon-atelier}  
  ![](/asset/icon%20ateliers/crea2.png){: .icon-atelier}  
  ![](/asset/icon%20ateliers/crea3.png){: .icon-atelier}  

- **La production**  
  ![](/asset/icon%20ateliers/prod%201.png){: .icon-atelier}  
  ![](/asset/icon%20ateliers/prod%202.png){: .icon-atelier}  
  ![](/asset/icon%20ateliers/prod%203.png){: .icon-atelier}  

### ⚙️ **Des ateliers pratiques et immersifs**  

Chaque atelier proposé ci-dessous vous plongera dans l’univers des fablabs. Vous aurez l’occasion d’explorer de nouveaux domaines tout en fabriquant un **objet ludique et utile**.  

📅 **Tous les ateliers se déroulent sur une demi-journée, soit 3h30.**  





<div align="center">
  {% for post in site.posts %}
    {% if post.tag == "atelier" %}
    <a href="{{post.permalink}}">
    <div class="div-class">
    <a href="{{post.permalink}}">
    <table class="tableau-atelier"><thead>
      <tr>
        <th colspan="2"><p class="min-atelier-titre">{{post.title }}</p></th>
        <th width="150px"><img  class="icon-atelier"  src="{{post.ic}}" /><img  class="icon-atelier"  src="{{post.crea}}" /><img  class="icon-atelier"  src="{{post.prod}}" /></th>
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
  {% endif %}
  {% endfor %}
</div> 



Autres ateliers à venir prochainement...



