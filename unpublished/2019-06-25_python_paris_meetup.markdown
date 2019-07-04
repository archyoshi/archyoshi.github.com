#---
layout: post
title:  "Meetup python paris"
date:   2019-06-22 10:00:00 +0200
categories: main
#---

Mutextree le besoin ==> Faire des opération complex exemple

maison -> user 1 -> telephone 1
      -> user 2 -> telephone 2

on peut pas suprimer le user 1 sans supprimer le téléphone 1

l'idée c'est de faire un arbre de noeuds qui représente notre système


L'algorithme : Mutextree

si abdf alors on sait que abd ne peut pas être prit

module python ==> basé sur redis et redis-lock
Utilise KEYS ==> le temps (complexité) et % au nombre de noeuds protégés simultanément (O(n)) ...
what is KEYS ? ... Optimisation


utilisable comme décorateur ou context-manager


___

moteur NLP  / Machine learning

Intention pas/peu décrite ==> donc il faut érer beaucoup les approximations

- construction du vocab de réf
- spellcheck
-normalisation
- detection d entité

==> Mettre en place une platforme de QA

Construicution d'un corpus de référence ==> mettre en place des faux bots  et le figer pour toujours. (pour que ça fasse une référence pour pouvoir comparer.

- "l"intention" doit matcher un "compotement"
- mettre en place un FALLBACK ==> réponse standard du bot lorsqu'il ne sait pas répondre à une certaine question.

Query (est cnadidate) = [intent 1 1 , intent2 .... Fallback]

calculer des métriques de qualité fiables.
Utiliser des métriques secondaire.

génère des notebook python qui permettent d explorer les donnée qui ont été généré avec les sessions de QA

Accepter ou pas les modifications.
Le but est de sortir du ressentis et se baser sur des données métriques et statistiques pour rassurer sur les choix qui sont effectués.
société ==> clustaar

___
 Common pattern ==> Multiple code version pointing to the same DB !

 speakerdeck ==> the path to smoother database migrations

 django-migration-linter
 easy to integrate into your CI pipeline
 gère les changements de db qui pourraient poser des soucis de migration.
 3YOURMIND (github)
still got some downsides

casser la prod / générer du downtime lots des migrations...

société botify contact hello@botfy

___
QuantMetry ==> société datascience (ML ENgineer) Rémi Addon

Fuzzy Matching with FlashText

1. Fuzzy Matching def ?
- nettoyer des données clients.
en général c'est du dataframe qu'ils cherchent à matcher avec un corpus de données
non structurés

Algorthme naiif (no optimal) Linear scan
n keywords, m entries
Regex - text entier...

"Brit" --> voir sur wikipedia dataset

2. FlashText intro ?
Aho-Corasik + Trie Dict -> O(n)

New York City -> NYC
New York -> NY

on a un text qui contient new york city
on obtient NYC et pas NY car il cherche a matcher le plus de mots possible
Radim Rehurek

met en cache ce qu'il a trouvé puis tente d'avancer le plus loin possible.

3. Levenshtein algo ?
Comment implémenter ça dans l algo existant
avec le moins de code possible
et en gardant les meme perf (car c'est très important)


3 opération ==>  insertion Suppression / Substitution
Levenshtein

Max cost = 1

Marina ==> on cherche à arriver à Marine. (qui est le plus procheà
sur 32 noeuds de l'arbre, on a éviter de parcourir 20 pour trouver ce qu'on souhaite

avantages => Intelligible / Debuggable / Facilement adaptable.

4. Limitation / R&D
Levenishtein (string, strong) = Levenshtein (ing, ong)
si on arrie a supprimer la partie commune, on reste toujours sur la même distance.


python ==> cython !
multi threading vs multi processing


==


2 mars 2020 => dotPy
voir ce que c'est que les conférence dot !
