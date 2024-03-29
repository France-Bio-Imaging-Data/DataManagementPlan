# Migration manuelle de certains projets FBI basés sur la trame FBI [V1.3.9](https://dsw.france-bioinformatique.fr/knowledge-models/IFB:bioimage-fbi-embrc-pgd-structure-km:1.3.9)

## Introduction

Ceci concerne les utilisateurs qui ont créé et rempli des PGDs structure taggés 'Plateforme France Bio Imaging', en particulier lors des ateliers de remplissage FBI organisés par Perrine Paul-Gilloteaux durant la première moitié de 2022.

À l'époque, la plupart d'entre vous avez travaillé avec la trame (ou knowledge model) _bioimage-fbi-embrc-pgd-structure-km_ en version [V1.3.9](https://dsw.france-bioinformatique.fr/knowledge-models/IFB:bioimage-fbi-embrc-pgd-structure-km:1.3.9). Depuis ce temps,  cette trame a énormément évolué et a subit une restructuration drastique, si drastique que je (Paulette Lieby) me suis engagée à migrer ces projets manuellement : cette migration est achevée et tous vos projets sont à présent basés sur la version [V1.0.0](https://dsw.france-bioinformatique.fr/knowledge-models/IFB:pgd-structure:1.0.0) de la trame renommée  _pgd-structure_.

## Q&A

### Oú vais-je trouver mes projets, ceux d'avant la migration, et ceux une fois la migration effectuée ?

Les projets / questionnaires d'avant la migration se retrouvent avec un ajout dans le titre de la mention '_avant migration vers IFB:pgd-structure:1.0.0_'. Par exemple 

<kbd><img width="1000" alt="avant_migration" src="https://user-images.githubusercontent.com/47455219/186443575-a0be61aa-639b-4464-821c-ecd6640426d2.png"></kbd>

<br/>
Les projets migrés se retrouvent sous leur titre original :  
<kbd><img width="1000" alt="après_migration" src="https://user-images.githubusercontent.com/47455219/186445512-0ed0629e-c5f1-44b5-a4d8-ae70357e57fa.png"></kbd>

<br/><br/>
Notez
1. le changement du nom de la trame, de _bioimage-fbi-embrc-pgd-structure-km_ en _pgd-structure_
2. le numéro de version

### Pourquoi une migration manuelle ?

Parce que la migration automatisée dans DSW entraine la perte de données dans notre cas de figure précis :  ceci est dû au fait que, de _bioimage-fbi-embrc-pgd-structure-km:V1.3.9_ à _pgd-structure:V1.0.0_, (presque) tous les choix simples ont été transformés en choix multiples, ce qui dans le cadre de DSW, entraine une perte des questions originales (et donc de la possiblité d'effectuer une migration automatisée).
Ensuite, un (grand) effort a été fait pour rationaliser les questions et réduire les redondances : de même, ce processus a impliqué la perte de certaines questions (et donc de leur réponses).

### Qu'est une migration 'automatisée' ?

Dans la liste des projets, on peut voir des projets suivis de l'onglet <img width="100" alt="migrate" src="https://user-images.githubusercontent.com/47455219/181510045-067b31cd-85f5-4634-9e26-4c5841abdc7b.png"> comme ici 

<kbd><img width="1000" alt="après_migration" src="https://user-images.githubusercontent.com/47455219/186447816-48a1a7ce-06c9-4401-a190-5efbf09b6c6e.png"></kbd>

En clickant sur cet onglet, DSW nous guide à travers la migration du projet. L'onglet <img width="100" alt="migrate" src="https://user-images.githubusercontent.com/47455219/181510045-067b31cd-85f5-4634-9e26-4c5841abdc7b.png"> s'affiche le long du nom du projet tant qu'une version plus récente de la trame sur laquelle il est basé est présente. 

Bien sûr, en ce qui nous concerne ici, l'objet est précisément de ne pas suivre ce processus, du moins pour les versions de la trame FBI antérieures à _bioimage-fbi-embrc-pgd-structure-km:V1.4.8_ (voir ci-après).

### À partir de quelle version de la trame FBI est-il conseillé d'opérer une migration automatisée ?

À partir de la version _bioimage-fbi-embrc-pgd-structure-km:V1.4.8_ la migration automatisée est possible avec une perte de données réduite : mais notons, que à l'exception des projets originaux créés lors des ateliers, il ne reste aucun projet 'Plateforme France Bio Imaging' basé sur une version antécédente à _pgd-structure:V1.0.0_ ; voir le point suivant.

### Quel est la différence entre les trames _bioimage-fbi-embrc-pgd-structure-km_ et _pgd-structure_ ?

_pgd-structure:V1.0.0_ est un clone de la dernière version de _bioimage-fbi-embrc-pgd-structure-km_, V1.14.17. En ce sens _pgd-structure:V1.0.0_ et toutes les versions à venir jalonnent l'évolution de la trame FBI au fil du temps ; dans ce cas présent cette évolution implique aussi un changement de nom de la trame.

### Y-a-t'il eu perte de données lors de cette migration manuelle ?

Sans doute, mais j'espère que les dégats sont minimaux ; j'ai fait du mieux que j'ai pu pour saisir les données existantes. Vous êtes donc encouragé.e.s à reviser la version migrée.

### Y aura-t-il une autre restructuration de la trame qui soit aussi destructive ?

Bien sûr, il n'y a pas de promesse qui tienne dans ce contexte. Mais la trame s'est consolidée et est à même de mieux accommoder les demandes issues de la communauté de la bioimagerie et au delà (travaux en cours).
À priori donc, si perte de données il y a lors d'une migration automatisée dans le futur, elles seront minimes, mais elles ne peuvent être éliminées totalement : elles sont une conséquence directe de l'effort continu de remplacer la saisie de texte libre par celle de choix parmi des options pré-déterminés.

### Précautions à prendre pour opérer une migration automatisée 

Comme noté dans la bannière d'accueil du site, il est *vital* que vous cloniez le projet à migrer : car une fois migré, la version précédente est écrasée et irrécupérable (du moins dans la version actuelle de DSW 3.13.0).

### Suis je obligé.e de migrer vers des versions de trame plus récentes ?

Non, pas du tout : cela dépend si la structuration vous sied. D'oú l'importance de cloner un projet avant de le migrer plus avant pour se donner le choix.

### La trame FBI [_pgd-structure:V1.0.0_](https://dsw.france-bioinformatique.fr/knowledge-models/IFB:pgd-structure:1.0.0)

Quelques caractérisques :
* Certaines redondances ont été éliminées : en particulier pour les contributeurs et les produits de la recherche. Pour ce faire a été mise en œuvre une imitation de liste déroulantes ; pour plus de détail voir le [tutoriel](https://github.com/France-Bio-Imaging-Data/DataManagementPlan/blob/main/TutorielCreerVotrePGDdeStructureBioImage.md).
* Beaucoup de choix simples ont été transformés en choix multiples, suite à une forte demande d'utilisateurs.

### Le futur de la trame FBI

Les montées en version de la trame seront rapprochées et nombreuses cette deuxième moité de l'année 2022. Les objectifs sont 
* d'améliorer l'ergonomie et la fluidité des questions,
* d'intégrer des questions concernant des domaines en dehors de la bioimagerie,
* de limiter autant que faire se peut la nécéssité de saisir du texte (pour le remplacer par des choix pré-établis).

### Finalement

* Vous pouvez effacer vos projets d'avant la migration manuelle si vous êtes satisfaits du résultat de celle-ci ;
* À l'avenir, tout nouveau projet basé sur la trame FBI sera (forcément) basé sur une version de _pgd-structure:1.0.0_+ ;
* N'oubliez pas le [tutoriel](https://github.com/France-Bio-Imaging-Data/DataManagementPlan/blob/main/TutorielCreerVotrePGDdeStructureBioImage.md) pour vous guider dans le remplissage du PGD ; 
* Pour tous commentaires et questions, vous pouvez vous adresser à paulette.lieby@france-bioinformatique.fr

