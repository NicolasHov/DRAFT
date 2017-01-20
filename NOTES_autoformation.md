# Notes autoformation :

Support/dépôt github défis (par Manu) : <https://github.com/simplonco/java-initiation/blob/master/tuto/javaPart8_defis.md>
* apprendre le workflow: apprendre à se faire un github perso. Plutôt de temps en temps et pas une journée -> faire du java directement et plutôt couper.

_Ressources :_

- [Java initiation sur le Github](https://github.com/simplonco/java-initiation/tree/master/tuto)
- jmdoudoux -> exos
- penser java
- OC (succint)

# 1ere semaine:

_Programme :_

- Transversal : Eclipse / Git et GitHub
- héritage
- encapsulation
- UML
- polymorphisme
- final
- abstract (qui débouche sur interface)
- static (méthode d'instance)

_Intro: objets et classes_

_Algo simple_

- exos/défis: créer une classe avec public static main et faire le fizzbuzz idéalement utiliser le debugger <https://github.com/simplonco/FizzBuzz/tree/4335f74b3e01f0734a7ec4504b3fcc19679af8f8>
- exos : reprendre les exos Js

_Algo sur tableaux_

- exos (tableau, années). => question des tableau qui réapparait (avant de voir les collections)/ de la mémoire
- Faire methode shuffle et l'implémenter sur différente collection => notion interface.

_getters/setters :_ voir getters et setters en qualifiant les attributs de la classe comme private voir héritage en les qualifiant protected toujours pr protéger son code, par défaut on les met sur tous mais on a le choix. on peut metre des conditions sur les getters on peut aussi sur les setters (ex MAJ) : notion de droit

- Défis/exos:

_héritage_

- Défis/exos:

_Encapsulation :_

- pr simpliofier échange entre créateur et utilisateur : uncontrat entre toi et l'utilisateur , qui va être un autre dev
- pour faire évoluer: la rétrocompatibilité (garder maitrise de son code) en gardant son code protégé (question des signature, pour protéger son code) -> que ce soit rétro compatible pour que les utilisateurs continuent à utiliser. => ds le libre pas trop rétrocompatible (ex PHP) or Oracle le fait ce qui fait qu'il est rétrocompatible (depuis 15ans)

- Défis/exos: trouver exos sur encapsulation

_conception classes:UML_ on part du détail et on généralise on créé ensuite les relations on liste les attrib puis on regroupe dans classe au dessus ou on va supprimer(ex: le nom qu'on remonte et qu'on supprime). Quand j'hérite d'une classe je m'attribue les attributs mais je ne peux les modifier (on en a l'usufruit, mais on en est pas maître)

- Défis/exos:

  - conception commune classe User et de son diagramme UML
  - Défi UML Pokemon
  - user/articles/commandes/fournisseur + exo airbnb (attention défis quon ne pourra pas coder tt de suite)
  - cooking data <https://github.com/simplonco/java-cooking-data> reprendre exo et reformuler car question des librairies/utilisation objet attention à faire un repo que pour eux

_encapsulation_

- Défis/exos:

  - cooking data <https://github.com/simplonco/java-cooking-data>

_polymorphisme_

- Défis/exos:

_final_

- Défis/exos:

_abstract_ (qui débouche sur interface)

- Défis/exos:

_static (méthode d'instance)_

- Défis/exos:

_Eclipse_

- capacité à renommer par groupe, faire des packages
- Debbuger : pas à pas avec breakpoints pour vérifier
- Tomcat
- impletion

les raccourcis (ctrl+clic) -> checker le projet exemple de Manu cf doc sur développez.com Syso/new

# 2eme semaine :

Liste défis Manu : <https://github.com/simplonco/java-initiation/edit/master/tuto/javaPart8_defis.md>

(XML/publipostage simple/cryptage de données/log)

- stream
- xml (je lis un fichier et je le sors, convertir csv en xml, créer par ex une classe ligne intermédiaire, commencer à utiliser les librairies de la JVM : celle qui fait conversion .csv en .xml) + il faudra aussi gérer les exceptions -> en faire un défi de même exo avec coder un mdp (crypto)
- log (plus les syso, mais écrire ds un fichier avec log4j)
- voir serialisation et java beans (sans voir l'annotation, qu'on verra dans spring avec hibernate)

inkection de dépendances :

- s'il y a dépendance forte = ie une classe fait appel à une autre, comme la classe voiture qui est présente ds la classe proprio.
- avec injection on passe plutôt par un fichier externe xml => était particulièrement abrupt => on utilise des annotations (l'annotation voiture par ex)

# 3eme semaine :

spring utilise bcp les interfaces, utiliser mais créer difficile

java beans -> réutilisable
