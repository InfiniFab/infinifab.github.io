---
title: "Les ateliers IF"
permalink : /ateliers/
pageurl : https://github.com/InfiniFab/infinifab.github.io/blob/master/ateliers.md

---

Fort d'une bonne experience acquise dans les fablabs, Infini Fab propose différents ateliers pour les fablabs voulant proposer une experience nouvelle à ses utilisateurs ou bien aux acteurs et lieux locaux voulant apporter de nouvelles perspectives, proposer une découverte des fablabs et de ce qu'on y fait.

En constante évolution, vous pouvez voir l'avancement de chaque ateliers selon les critères suivant :
- V 0.1 : à l'état de projet 
- V 0.2 : Les informations pour le fabriquer ont été récupérées
- V 0.3 : un 1er prototype a été fabriqué et validé
- V 0.9 : L'ateliers est pret à être proposé pour une animation

Chaque ateliers proposé ci dessous vous fera découvrir le monde des fablabs ou bien explorer de nouveau domaine de ceux-ci en vous proposant la fabrication d'un objets fun et utile.


{% for post in site.posts %}
{% if post.tag == "atelier" %}{: .listateliers}
 
|------------------------------------+---------------------|
| {{post.description}} |     |   
|------------------------------------|:-------------------:|
| [![]({{post.image}}){: width="150px"}]({{ post.url }}) |   | 
|------------------------------------+---------------------|
| ![](/asset/clock.png){: width="50px"} | {{post.temps}} |
|------------------------------------+---------------------|
 
{% endif %}
{% endfor %}