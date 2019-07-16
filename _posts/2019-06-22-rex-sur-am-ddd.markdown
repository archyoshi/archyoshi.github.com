---
layout: post
title:  "Retour sur l’après-midi du Domain-Driven Design - episode 2"
date:   2019-06-22 10:00:00 +0200
categories: main
---

![AM DDD Affiche](/assets/images/amddd_affiche.jpeg)


La seconde édition de l'après-midi du DDD ou [#AMDDD](https://twitter.com/hashtag/AMDDD?src=hash) s'est déroulée le 20 juin 2019 dans les locaux de Microsfost à Issy-Les-Moulineaux. L'événement a été organisé par [42Skillz](http://www.42skillz.com) avec, comme animateurs, [Bruno Boucard](https://twitter.com/brunoboucard) et [Thomas Pierrain](https://twitter.com/tpierrain), à leurs côté plusieurs invités, je cite : Xavier DETANT, Chloé GRANDIN, Radwane HASSEN, Audrey NEVEU, Pablo PERNOT et Alexandre VICTOOR.

J'ai assisté a cet évènement très enrichissant, et je vais partager avec vous l'expérience que j'ai eu lors de cet event.

La présentation était très originale, car au lieu d'être un enchaînement de talks et de sessions de coding, c'était sous forme d'une pièce de théâtre. Chaque scène a mis en lumière un aspect de la vie quotidienne de développeurs d'une société fictive nommée TicketOffice.

Voici quelques problématiques mises en lumière par cette belle pièce de théâtre :
- Le turn-over des employés les plus expérimentés sur une appli fais conduit fatalement a un échec si le code ne respecte pas les bonnes pratiques qui lui permettent d'être relus / compris et maintenu par d'autres développeurs.
- Quand la communication entre l'équipe de dev et leur client n'est pas assez poussée, les dév parfois se retrouvent à redévelopper des briques de code qui ne sont pas dans leurs cercle de responsabilité. Parfois même, ils se peut qu'ils codent des éléments qui ont toute une équipe dans la société dédiée mais qu'ils n'ont en tout simplement pas connaissance.
- Quand les discussions avec le métiers ne sont pas assez clarifiées et précisées on peut se retrouver avec des éléments (comme des règles métiers) très ambigüe ou parfois contradictoire.
- Quand on dépend d'autres équipes, et que notre base de code n'est pas assez "protégée", on peut être victime de nos dépendances, il faut donc s'outiller correctement pour s'en prémunir.

Quelques idées qui pour apporter des solutions à ces problématiques :
- Quand on est face à un sujet de grande importance et qu'on souhaite réellement tout faire pour que ça marche, il faut également s'en donner les moyens, par exemple en s'assurant que les gens qui connaissent la base de code partage assez de connaissances avec ceux les nouveaux et qu'ils les fassent monté en compétence avec un accompagnement pour qu'ils deviennent fiable et capable de de contribuer efficacement au projet.
- Un des bons moyens d'être sur la même longueur d'onde que celle du client est de faire un atelier (ou plusieurs) atelier d'[Event Storming](https://en.wikipedia.org/wiki/Event_storming)
en utilisant un maximum de moyens visuels afin d'illustrer correctement les idées et de les faire aboutir à un même concept clair pour tout le monde.
- La pratique du [Domain Driven Design](https://en.wikipedia.org/wiki/Domain-driven_design) devient alors un bon moyen pour que le code représente un maximum le métier, donc s'accorder sur les termes métier employer pour désigner les mêmes éléments et d'une importance cruciale.
- Si on remarque que notre application est souvent hors service, et que la raison provient souvent de nos dépendances, il faut chercher différent moyens de s'en prémunir, il y a par exemple l'utilisation de l'[Architecture Hexagonale](https://java-design-patterns.com/patterns/hexagonal/) d'un côté, mais encore une autre manière d'y remédier est le [Anti Corruption Layer](https://docs.microsoft.com/en-us/azure/architecture/patterns/anti-corruption-layer)

Je vous laisse donc redécouvrir cette belle après midi en vidéo ici:
{% include youtubePlayer.html id="PIo6jUl4VO8" %}
