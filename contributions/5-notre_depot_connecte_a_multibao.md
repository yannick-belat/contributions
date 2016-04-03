# Connecter  notre dépôt de fiches à http://multibao.org

Les dépôts individus présentant des fiches statiques écrites par une seule personne ne sont pas présentées. 
MultiBàO est une expérience collective. 
Les présents critères ont été choisis lors de 4 jours immersifs de développement web multiBàO avec *Xavier Coadic*, *Stéphane Langlois* et *Thomas Wolff* fin mars 2016. Ils sont ouverts à la discussion via la liste de discussion du projet ou l'outil Slack à venir.

**Les dépôts de fiches qui apparaissent sur http://multibao.org**

* sont liés à des organisations. Ce n'est pas un individu seul qui porte un ensemble de ressources. 
 * les organisations liées à un nom personnel ne sont pas affichées
* les dépôts de fiches ont au moins 3 contributeurs affichés. 
 * 3 regards sur une ressource, c'est le minimum pour que les ressources puissent être revues, amendées, corrigées 
* au moins 30% des fiches sont écrites ou citent au moins 2 auteurs différents.
 * la ressource est déjà issue d'un travail de compilation et/ou de mise en abime avec 2 parties prenantes différentes
 
## Réaliser l'opération 

Pour ce faire, il vous faut un accès contributeur à http://github.com/multibao. Vous pouvez demander à n'importe quel contributeur existant de multiBaO. Ou écrire à thomas.wolff@cpcoop.fr pour lui demander de vous inviter.

Connectez votre dépôt github à multiBàO
* éditez le document suivant : https://github.com/multibao/contributions/blob/master/_config.yml en indiquant
 * **label** correspondant au titre du dépôt qui apparaîtra sur multibao.org
 * **account** votre nom d'utilisateur
 * **repo** le dépôt dans lequel sont stockées les fiches
 * **folder** le menu dans lequel sont stockées les fiches

Exemple pour le dossier de fiches "Réseau transition", visibles sur github en suivant le lien http://github.com/reseautransitionwb/reseau_transition/contributions

label: Réseau transition - c'est le nom qui apparaît sur multibao.org 
account: reseautransitionwb - c'est leur nom d'utilisateur
repo: reseau_transition - c'est le nom du dépôt
folder: contributions - c'est le nom du dossier où se trouvent les fiches

