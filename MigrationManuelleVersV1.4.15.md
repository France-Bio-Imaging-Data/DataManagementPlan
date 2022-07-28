# Migration manuelle de certains projets FBI basés sur la trame FBI [V1.3.9](https://dsw.france-bioinformatique.fr/knowledge-models/IFB:bioimage-fbi-embrc-pgd-structure-km:1.3.9)

## Introduction
Ceci concerne les utilisateurs qui ont créé et rempli des PGDs structure taggés 'Plateforme France Bio Imaging', en particulier lors des ateliers de remplissage FBI organisés par Perrine Paul-Gilloteaux durant la première moitié de 2022.

À l'époque, la plupart d'entre vous avez travaillé avec la trame en version [V1.3.9](https://dsw.france-bioinformatique.fr/knowledge-models/IFB:bioimage-fbi-embrc-pgd-structure-km:1.3.9). Depuis ce temps,  cette trame a énormément évolué et a subit une restructuration drastique, si drastique que je (Paulette Lieby) me suis engagée à migrer ces projets manuellement : cette migration est achevée et tous vos projets sont à présent basés sur la version [V1.4.15](https://dsw.france-bioinformatique.fr/knowledge-models/IFB:bioimage-fbi-embrc-pgd-structure-km:1.4.15).

## Q&A

### Oú vais-je trouver mes projets, ceux d'avant la migration, et ceux une fois la migration effectuée ?
Les projets d'avant la migration se retrouvent avec un ajout dans le titre de la mention '_avant migration vers IFB:bioimage-fbi-embrc-pgd-structure-km:1.4.15_'. Par exemple 

<kbd><img width="1000" alt="avant_migration" src="https://user-images.githubusercontent.com/47455219/181507047-93068898-d664-4d70-b465-ea040ee3fc2d.png"></kbd>

<br/>
Les projets migrés se retrouvent sous leur nom original :  
<kbd><img width="1000" alt="après_migration" src="https://user-images.githubusercontent.com/47455219/181509070-d49d3e97-1467-46e1-a48d-09974bd5f3ae.png"></kbd>

<br/>
Dans les deux cas, notez la version de la trame.

### Qu'est une migration 'automatisée' ?

Dans la liste des projets, on peut voir des projets suivis de l'onglet <img width="100" alt="migrate" src="https://user-images.githubusercontent.com/47455219/181510045-067b31cd-85f5-4634-9e26-4c5841abdc7b.png"> comme ici 

<kbd><img width="1000" alt="après_migration" src="https://user-images.githubusercontent.com/47455219/181509216-ae568cbb-fe87-423d-b85c-fcb6bf2a5de6.png"></kbd>

<br/>
En clickant sur cet onglet, DSW nous guide alors à travers la migration du projet. L'onglet <img width="100" alt="migrate" src="https://user-images.githubusercontent.com/47455219/181510045-067b31cd-85f5-4634-9e26-4c5841abdc7b.png"> s'affiche le long du nom du projet tant qu'une version plus récente de la trame sur laquelle il est basé est présente. 

Bien sûr, en ce qui nous concerne ici, l'objet est précisément de ne pas suivre ce processus, du moins pour les versions de la trame FBI antérieures à V1.4.8 (voir plus bas).

### Pourquoi une migration manuelle ?

Parce que la migration automatisée dans DSW entraine la perte de données dans notre cas de figure précis :  ceci est dû au fait que, de V1.3.9 à V1.4.15, (presque) tous les choix simples ont été transformés en choix multiples, ce qui dans le cadre de DSW, entraine une perte des questions originales (et donc de la possiblité d'effectuer une migration automatisée).
Ensuite, un (grand) effort a été fait pour rationaliser les questions et surtout réduire les redondances : ce processus a aussi entrainé la nécéssaire perte de certaines questions (et donc de leur réponses).

### À partir de quelle version de la trame FBI est-il possible d'opérer une migration automatisée ?

À partir de la version V1.4.8+ la migration automatisée est possible : mais notons, à l'exception des projets qui ont été migrés manuellement, il ne reste aucun projet 'Plateforme France Bio Imaging' basé sur une version antécédente à V1.4.15.

### Y-a-t'il eu perte de données lors dette migration mauelle ?

Sans doute, mais j'espère que les dégats sont minimaux ; j'ai fait du mieux que j'ai pu. Vous êtes donc encouragés à reviser la version migrée ; bien sûr toutes mes excuses pour les inconvénients rencontrés.

### Y aura-t-il une autre restructuration de la trame qui soit aussi destructive ?

Bon, bien sûr, il n'y a pas de promesse qui tienne dans ce contexte. Mais la trame s'est consolidée et est 

permet dès à présent  est à présent à même de s'étoffer à partir de la structure actuelle. Elle est en bonne position pour intégrer les demandes issues de la communauté de la bioimagerie et au delà (travaux en cours).
À priori donc, si perte de données il y a lors d'une migration automatisée dans le futur, elles seront minimes.https://gitlab.com/ifb-elixirfr/fair/gt2-is1-mudis4ls/gt2/-/issues

### Précautions à prendrer pour opérer une migration automatisée 

Comme noté dans la bannière d'accueil du site, il est vital que vous cloniez le projet à migrer : car une fois migré, la version précédente est écrasée et irrécupérable (du moins dans la version actuelle de DSW 3.13.0).

### Finalement

* Vous pouvez effacer vos projets d'avant la migration manuelle si vous êtes satisfaits du résultat de celle-ci ;
* À l'avenir, tout nouveau projet basé sur la trame FBI sera (forcément) basé sur une verion V1.4.15+...
* Pour tous commentaires et questions, vous pouvez vous adresser à paulette.lieby@france-bioinformatique.fr

