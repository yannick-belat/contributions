# M'entraîner à l'écriture Markdown

# Exercice 1 : écris quelques titres

En langage Markdown 

# Titre 1 : exercice 1 : écris quelques titres

# Titre 1

s'écrit \# Titre 1

## Titre 2 

s'écrit  \#\# Titre 2 

De même pour \#\#\# Titre 3, \#\#\#\# Titre 4, etc. 

# Exercice 2 : écris un texte, mets des parties en gras, d'autres en italique

**je suis un peu gras** s'écrit \*\* je suis un peu gras\*\*
*je suis italique* s'écrit \*je suis italique\* (ça se dit, ça?)

# Exercice 3 : insère tes « puces »

* à la claire fontaine
* j'ai bu d'leau cristaline®

s'écrit 

\* à la claire fontaine

\* j'ai bu d'leau cristaline®

# Exercice 4 : mets un lien vers un site web 

[lien vers multiBàO](http://multibao.org) s'écrit \[lien vers multiBàO\]\(http://multibao.org\) 
 
## Exercice 5 : insère une image à ta fiche

### Si on l'a sous la forme d'un lien hypertexte

\!\[indiquer un titre pour l'image\]\(indiquer l'url de l'image\)

Exemple :

\!\[Outils-reseaux.org CoursInkscape\]\(http://outils-reseaux.org/files/CoursInkscape_inkscapelogo_vignette_209_209_20130614154853_20130614155446.png)

Donne cela :

![Outils-reseaux.org CoursInkscape](http://outils-reseaux.org/files/CoursInkscape_inkscapelogo_vignette_209_209_20130614154853_20130614155446.png)

Il n'est pour l'instant pas possible d'ajouter directement de photo dans l'édition d'une fiche multiBàO.

### Où trouver des images Creative Commons (autorisant réutilisation)?

http://search.creativecommons.org/ 

### Si on l'a sous la forme d'un fichier jpeg, png,...

Stocker l'image sur ton site ou sur https://framapic.org/

Framapic est un des nombreux services libres, sécurisés et gratuits de Framasoft. En un clic, tu ajoutes ta photo et récupères le lien hypertexte. A partir de ce lien hypertexte, tu peux ajouter la photo sous multiBàO.

### Recommandations pour l'image

* inférieure ou égale à 640 px de largeur
* privilégier des images "légères" pour que l'affichage des fiches soit facilité


# Exercice 6:  insérer des notes 

### A l'endroit où on souhaite insérer la note

on insère juste le code suivant qui indique que cela est une note avec le numéro correspondant 

Exemple : 

\*\*\[1\]\(\#note\)\*\*  donne **[1](#note)**

\*\*\[2\]\(\#note\)\*\*  donne **[2](#note)**

### A l'endroit où l'on veut que la note pointe

Par exemple à la fin de mon document je crée un chapitre "Sources", section dans laquelle je vais citer les différents auteurs, ouvrages...

J'insère le code html suivant : 

`<a id="note"> <a id="note">`

> On passe en html car le language Markdown n'est pas suffisant pour pouvoir mettre des notes qui renvoient vers les sources. C'est une petite manoeuvre qui sera agréable pour les lecteurs. Louise! 

Puis les notes en question :

\* \*\*\[1\]\(\#note\)\*\* Vincent Kober [infolabs.io](http://infolabs.io/sites/default/files/files/dataviz_pieds_V1.pdf), selon les termes de la licence Creative Commons BY-NC-SA 

\* \*\*\[2\]\(\#note\)\*\* Merci a netalloy et openclipart pour les pieds, [openclipart](https://openclipart.org/detail/154855/green-steps-by-netalloy), selon les termes de la licence Creative Commons  CC0 1.0 universel [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.fr)

Ce qui donne :

* **[1](#note)** Vincent Kober [infolabs.io](http://infolabs.io/sites/default/files/files/dataviz_pieds_V1.pdf), selon les termes de la licence Creative Commons BY-NC-SA 

* **[2](#note)** Merci a netalloy et openclipart pour les pieds, [openclipart](https://openclipart.org/detail/154855/green-steps-by-netalloy), selon les termes de la licence Creative Commons  CC0 1.0 universel [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.fr)
