# Page d'accueil du rapport de stage

Stage effectué par Olivier CHECCHIN chez SAP, pour la fin de la 2eme année à La Prépa des INPs à Bordeaux.

Tous les PDFs et images sont accessibles sur cette page.

Le rapport de stage en lui même est le fichier ["rapport de stage.md"](rapport_de_stage.md).

Le rapport de stage convertit en PDF avec l'outil Pandoc est le fichier ["rapport.pdf"](rapport.pdf).

La conversion se fait à l'aide du code suivant:

~~~~
pandoc --toc --number-sections -V documentclass=scrreprt -V linkcolor=black -s -o rapport.pdf "rapport de stage.md"
~~~~
