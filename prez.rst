======
 Prez
======

*Support télégraphique de la présentation*

Pas le temps de replacer ça dans la problèmatique générale du test.

Déboguer: comprendre ce qui se passe dans le code produit.

Quels outils?

- neurones.
- print
- log
- pytest
- ipython
- pdb
 
ipython
=======

https://ipython.org

bash: 50% langage de script, 50% interactif.
1 seul outil, 2 fonctions.

Pour python, c'est séparé: python le langage, ipython l'interactif.

Historique:
-----------

ipython --> Jupyter, notebooks --> JupyterLabs

Features ipython:
- couleur
- complétion
- history (rappel de commandes)
- Et j'en passe, à creuser.
- mais surtout, pdb!



pytest
======

unittest --> nosetest --> pytest

pdb
===

https://docs.python.org/3/library/pdb.html

débogueur, avec les fonctions classiques:

- pas à pas.
- s(tep) ou n(ext)
- (c)ontinue
- (r)eturn


intérêt: **voyager dans la stack!**

- up
- down
- visu des variables (locals(), globals())

Sessions classiques
===================

ipython  --> pdb --> import module --> fail

ipython --> pdb --> %run script args --> fail

pytest <dir_or_file>

pytest -s ....

pytest --pdb



