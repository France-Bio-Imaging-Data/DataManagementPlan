Chers collègues,

Vous avez mis en place une base de données d’images dans votre structure en ayant conscience que cela permet d’augmenter la traçabilité des données de la recherche en répondant de façon implicite au concept FAIR (https://www.go-fair.org/fair-principles/), soit « Facile à découvrir, Accessible, Interopérable, Réutilisable », qui est l’un des piliers de la science ouverte. La mise en place de Plans de Gestion de Données associés (PGD de structure) est la formalisation du processus de gestion de votre base de données décrivant les moyens permettant ainsi de les rendre ainsi visibles, accessibles, et réutilisables quel que soit le demandeur.
Dans le but de vous faciliter la moisson de ces informations, un projet de « PGD structure bioimagerie », porté par et réalisé conjointement avec les Infrastructure Nationale en Biologie Santé (INBS) « France-BioImaging » (FBI), « Institut Français de Bioinformatique » (IFB), et « Centre National De Ressources Biologiques Marines » (EMBRC-France) est en cours d’élaboration.


Cette architecture formera le tronc du PGD projet à destination des usagers de cette structure, permettant accessoirement que les champs idoines du PGD projet soient automatiquement renseignés par les informations déjà glanées en amont.
Nous vous proposons de tester et nous donner votre avis sur le questionnaire générique élaboré, destiné à moissonner ces informations en entrée puis de générer des documents à façon en utilisant de « Templates » d’extraction.

Vous pouvez avoir un aperçu complet du questionnaire non éditable à cette adresse : https://dsw.france-bioinformatique.fr/projects/c59841dd-ca42-49fe-90da-6412cf9dd3bf

<h1><strong>AUTHENTIFICATION</h1></strong><br>
Il existe 4 rôles différents pour un profil utilisateur :<br><br>     
<strong>Anonymous</strong> : utilisateur de DSW qui n'est pas encore connecté. Il peut s'inscrire, se connecter ou récupérer son mot de passe si vous l'avez oublié.<br><br>
<strong>Researcher</strong> : ce rôle est attribué par défaut aux utilisateurs après leur inscription. Nous partirons du principe que seuls les administrateurs pourront modifier ces rôles.
               Cet utilisateur travaille sur un projet scientifique et a les connaissances sur le projet en question. Son objectif est d'obtenir un plan de gestion des données
               FAIR.<br><br>        
<strong>Steward</strong> : utilisateur qui a une bonne connaissance de l'outil DSW. I peut créer  des « knowledge models ». Ceux-ci sont ensuite utilisé par les scientifiques (ayant le rôle de Researcher) pour créer le DMP avec le questionnaire.<br><br>
<strong>Administrator</strong> : Il gère les paramètres généraux et dispose des privilèges les plus élevés.<br><br>  
   

Après avir obtenu un accès :  <br>
![image](https://user-images.githubusercontent.com/19286219/115886454-3b5a1e00-a451-11eb-97f9-542e76f85d6d.png)<br>
Vous pouvez utiliser l’ensemble des fonctionnalités de l’outil DSW (Data Stewardship Wizard) :

![image](https://user-images.githubusercontent.com/19286219/115886496-457c1c80-a451-11eb-9d30-aaa4eacc82c1.png)

Les « knowledge models » sont des formats pré-établis de questionnaires vides

Les projets sont des questionnaires remplis ou en cours de remplissage à partir des « knowledge models » par chaque utilisateur possédant un accès.

Les documents sont les fichiers extraits une fois les questionnaires complétés dans des formats standard : pdf, json…

Les Templates sont des gabarits d’extraction : cad extraction de l’ensemble des champs ou d’une partie en fonction du type de besoin.

Par ex : pour les gestionnaires de base de données le gabarit par défaut permettra d’extraire l’ensemble du document complété.

Pour un chef d’équipe qui a besoin de décrire la gestion de ses images dans le cadre d’un PGD de projet, un gabarit spécifique sera disponible.

Pour remplir votre propre questionnaire, procédez comme suit :
Créez un nouveau projet : ![image](https://user-images.githubusercontent.com/19286219/115886648-6d6b8000-a451-11eb-850c-357b62142269.png) puis ![image](https://user-images.githubusercontent.com/19286219/115886669-74928e00-a451-11eb-88f9-777cbc12be9c.png)
Puis nommez votre projet comme suit PGD_« Nom de votre labo ou plateforme » en utilisant le « knowledge model » : Bioimagexxxx, sauvez
![image](https://user-images.githubusercontent.com/19286219/115886699-7bb99c00-a451-11eb-8fcb-57d8f44b7a7f.png)
Votre projet est disponible dans ![image](https://user-images.githubusercontent.com/19286219/115886735-8411d700-a451-11eb-9337-ea85e8962af3.png)
![image](https://user-images.githubusercontent.com/19286219/115886757-87a55e00-a451-11eb-92a5-686bd533f4cd.png)
Vous avez maintenant accès aux différents champs à compléter dans ![image](https://user-images.githubusercontent.com/19286219/115886786-8ecc6c00-a451-11eb-9f2e-a8db285a66a3.png)
![image](https://user-images.githubusercontent.com/19286219/115886792-925ff300-a451-11eb-971c-07df155dbce6.png)
Une fois complété ou lors du remplissage vous pouvez à tout moment choisir le format d’extraction et le « Template » IFBxxxxx dans ![image](https://user-images.githubusercontent.com/19286219/115886841-9f7ce200-a451-11eb-881a-5adc397d6546.png)

![image](https://user-images.githubusercontent.com/19286219/115886864-a6a3f000-a451-11eb-98eb-8de6d8829769.png)
Pour créer le document, choisir le menu 
![image](https://user-images.githubusercontent.com/19286219/115886914-b0c5ee80-a451-11eb-9f47-1f11efb9d600.png)![image](https://user-images.githubusercontent.com/19286219/115886934-b4597580-a451-11eb-8171-0dcf8e057c92.png)

![image](https://user-images.githubusercontent.com/19286219/115886957-b91e2980-a451-11eb-9761-1f3babd10d3c.png)
puis « Create ». Votre document est disponible dans votre environnement « Projet » :
![image](https://user-images.githubusercontent.com/19286219/115886995-c3402800-a451-11eb-828a-c3ddcb3d0087.png)

