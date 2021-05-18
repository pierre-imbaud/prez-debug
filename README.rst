====================================================
 Présentation "Debug en python; évolution récentes"
====================================================

Présentation faite par Pierre Imbaud, pour l'évènement « En attendant
la PyConFr » du 20 mai 2021, de l'afpy.

Ce repository git va contenir:

- Des morceaux de code pour illustrer la prez.
- Des morceaux de texte, en support de la prez.


Contexte:
=========

Je suis un vieil utilisateur des méthodes de debug, en particulier
pdb, et ipython. Récemment, dans le cadre d'un développement d'api
Rest sous Flask, j'ai eu des difficultés à faire coucher ce petit
monde ensemble:

- flask
- pytest
- ipython
- pdb

J'ai lancé un appel au secours sur `l'app de discussion de l'afpy
<https://discuss.afpy.org>`_. De bonnes suggestions sont venues, mais
j'ai essentiellement trouvé tout seul mes solutions, signalé au
groupe, disant que j'allais rédiger ça un peu plus tard. Et la
proposition est venue "pourquoi tu ne présenterais pas ça pour "En
attendant ..."? Et me voici embarqué.

Spoiler:
========
Il me semble vital de permettre à ceux qui n'apprendraient rien de
cette présentation de le savoir avant, et de se libérer pour des
tâches plus valorisantes, arboricoles ou puericoles. Pour les Pycon
live [1]_, [2]_, c'était assez frustrant pour moi, de faire le choix
entre 4 exposés, et plus encore de faire le mauvais choix!

Je pense que c'est une prez "pour débutants", ou du moins pour ceux
qui ne sont pas totalement familiers de l'écosystème python.

Les "nouveautés" que j'introduis sont ipdb, breakpoint(), et pdb++

Références
==========

- https://testandcode.com

- ` "Goodbye Print Statements, Hello Debugger!" - Nina Zakharenko
  (PyCon AU 2019)` <https://www.youtube.com/watch?v=HHrVBKZLolg>`_ :

- https://testdriven.io/test-driven-development/

.. [1] Oui, c'était le bon temps! vivement qu'il revienne.

.. [2] Notes sans grand intérêt, hormis de montrer les supériorités de
       restructuredText sur Markdown, qui gagne du terrain dans le
       monde python, tandis que McDo en gagne sur la Bonne Bouffe
       Française. 
