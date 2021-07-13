Chers collègues,

Vous avez mis en place une base de données d’images dans votre structure en ayant conscience que cela permet d’augmenter la traçabilité des données de la recherche en répondant de façon implicite au [concept FAIR](https://www.go-fair.org/fair-principles/), soit « Facile à découvrir, Accessible, Interopérable, Réutilisable ». Ce concept est l’un des piliers de la science ouverte. La mise en place d'un Plan de Gestion de Données associé à votre structure (PGD de structure) est la formalisation du processus de gestion de vos  données décrivant les moyens permettant de les rendre visibles, accessibles, et réutilisables quel que soit le demandeur.
Dans le but de vous faciliter la moisson de ces informations, un projet de « PGD structure bioimagerie », porté par et réalisé conjointement avec les Infrastructures Nationales en Biologie Santé (INBS) « France-BioImaging » (FBI), « Institut Français de Bioinformatique » (IFB), et « le Centre National De Ressources Biologiques Marines » (EMBRC-France), ainsi que l'Université Côte d'Azur, est en cours d’élaboration.

Cette initiative à destination des usagers de votre structure facilitera d'une part la communication autour de votre gestion de données, et d'autre part la conception des PGDs projets. En effet, cela permettera à terme que les champs idoines du PGD projet soient automatiquement renseignés par les informations déjà glanées en amont. Par exemple, s'il s'agit du PGD d'un projet émargeant à votre structure, l'utilisateur remplissant son PGD pourra trouver des recommandations et certains champs préremplis pour les données d'imagerie générées au sein de votre structure, et pourra le compléter à terme avec le PGD d'autres structures pour d'autres types de données.

Nous vous proposons de tester et nous donner votre avis sur le questionnaire générique, dédié à l'imagerie, destiné à moissonner ces informations en entrée puis de générer des documents à façon en utilisant des « Templates » d’extraction. <br><br>

[Comment contribuer?](#contribuer)<br> 
[Terminologie](#terminologie)<br> 
[Profils Utilisateurs](#profil)<br> 
[Workflow](#workflow)<br> 
[Questions-Réponses](#faq)<br> 

<h2><strong> COMMENT CONTRIBUER?</h2></strong><a id="contribuer"></a><br> 
Pour participer à la création de ce PGD Structure productrice d'imagerie, deux propositions:<br>  
<br>  

* Vous pouvez consulter sans être identifié [un questionnaire non éditable générique](https://dsw.france-bioinformatique.fr/projects/3e62b45f-14ab-4045-8f73-6fffb02927ab), et un [exemple pour une plateforme](https://dsw.france-bioinformatique.fr/projects/f5378aa4-93d5-41d4-9223-db99754d6e29) . Notez que vous ne pourrez pas remplir ce questionnaire ni voir les différentes listes d'option disponibles. Vous pourrez faire remonter vos remarques/questions en utilisant la fonctionnalité "Feedback" pour soumettre vos questions/problèmes/suggestions d'améliorations, en cliquant sur le point d'exclamation à côté des questions:

<img width="633" alt="CaptureFeedback" src="https://user-images.githubusercontent.com/19286219/125419753-5e0a936c-74b3-4cff-a16f-0ec8c963ffa4.PNG">

Vous pourrez également suivre l'évolution de traitement en notant le lien donné après que vous ayez envoyer votre remarque:
<img width="282" alt="CaptureFeedback2" src="https://user-images.githubusercontent.com/19286219/125419936-3a02fa81-abfe-480a-85c3-edec70fb6a89.PNG">


* Vous pouvez ausi tester l'outil en y apportant les réponses pour votre structure (qui seront privées par défaut sauf si vous décidez de les partager, voir le paragraphe "Partager". Pour cela nous vous invitons, avec un statut de "Researcher" à suivre le workflow proposé ci-dessous qui vous permettra de créer, de compléter et d'exporter votre propre PGD de structure. Pour pouvoir éditer votre propre questionnaire vierge, il vous faut [créer un compte sous l'application Data Stewardship Wizard (DSW)](https://dsw.france-bioinformatique.fr/signup). Vous pourrez également utiliser la fonctionnalité de feedback sur les questions décrites ci-dessus, ou [émettre des suggestions générales](https://gitlab.com/ifb-elixirfr/fair/madmp-bioimage/-/issues) avec un compte gitlab.

<h2><strong>TERMINOLOGIE</h2></strong><a id="terminologie"></a><br> 

![Presentationrelationdocuments](https://user-images.githubusercontent.com/19286219/125417057-026b8898-b603-4e70-beae-bb91004a1bae.png)

* <strong>Les « knowledge models » (KM)</strong> : formats pré-établis de questionnaires vides. Base de connaissances à partir de laquelle un questionnaire est généré. Identifié par un KM ID. Il peut être personnalisé/publié/exporté/importé.

* <strong>Les Questionnaires </strong> : représentation d'un KM sous la forme d'un formulaire à remplir.

* <strong> Les projets </strong> : questionnaires remplis ou en cours de remplissage à partir des « knowledge models » par chaque utilisateur possédant un accès.

* <strong>Les documents </strong> : fichiers extraits une fois les questionnaires complétés dans des formats standard : pdf, json…

*  <strong>Les Templates </strong> : gabarits d’extraction : cad extraction de l’ensemble des champs ou d’une partie en fonction du type de besoin.

Par ex : pour les gestionnaires de base de données le gabarit par défaut permettra d’extraire l’ensemble du document complété.

Pour un chef d’équipe qui a besoin de décrire la gestion de ses images dans le cadre d’un PGD de projet, un gabarit spécifique sera disponible.

<h2><strong>WORKFLOW</h2></strong><a id="workflow"></a><br>


![DSW Workflow-03](https://user-images.githubusercontent.com/84018042/117858359-1c032380-b28e-11eb-94ec-167659eaa82c.png)

<h2><strong>PROFILS UTILISATEURS</h2></strong><a id="profil"></a><br>

Il existe 4 rôles différents pour un profil utilisateur :<br>   
<strong>Anonymous</strong> : utilisateur de DSW qui n'est pas encore connecté. Il peut s'inscrire, se connecter ou récupérer son mot de passe si vous l'avez oublié.<br><br>
<strong>Researcher</strong> : ce rôle est attribué par défaut aux utilisateurs après leur inscription. Nous partirons du principe que seuls les administrateurs pourront modifier ces rôles. Cet utilisateur travaille sur un projet scientifique et a les connaissances sur le projet en question. Son objectif est d'obtenir un plan de gestion des données
               FAIR.<br>    
<strong>Steward</strong> : utilisateur qui a une bonne connaissance de l'outil DSW. I peut créer  des « knowledge models ». Ceux-ci sont ensuite utilisé par les scientifiques (ayant le rôle de Researcher) pour créer le DMP avec le questionnaire.<br><br>
<strong>Administrator</strong> : Il gère les paramètres généraux et dispose des privilèges les plus élevés.<br><br>  
   
<h2><strong>CREER UN PROJET</h2></strong><br>

Après avoir obtenu un accès :  <br>
![image](https://user-images.githubusercontent.com/19286219/115886454-3b5a1e00-a451-11eb-97f9-542e76f85d6d.png)<br>
Vous pouvez utiliser l’ensemble des fonctionnalités de l’outil DSW :

![image](https://user-images.githubusercontent.com/19286219/115886496-457c1c80-a451-11eb-9d30-aaa4eacc82c1.png)

Pour remplir votre propre questionnaire, procédez comme suit :<br>

![image](https://user-images.githubusercontent.com/19286219/115886648-6d6b8000-a451-11eb-850c-357b62142269.png) puis ![image](https://user-images.githubusercontent.com/19286219/115886669-74928e00-a451-11eb-88f9-777cbc12be9c.png)

Puis nommez votre projet comme suit "PGD_Nom de votre labo ou plateforme" en utilisant le « knowledge model » : "Modèle de PGD structure pour la bioimagerie" :

![image](https://user-images.githubusercontent.com/60437839/120227113-de6c3780-c248-11eb-912d-e902b4b85edb.png)

Sauvez

Votre projet est maintenant disponible dans ![image](https://user-images.githubusercontent.com/19286219/115886735-8411d700-a451-11eb-9337-ea85e8962af3.png)<br><br>

<h2><strong>REMPLISSAGE DU QUESTIONNAIRE</h2></strong><br>
Vous avez maintenant accès aux différents champs à compléter dans

![image](https://user-images.githubusercontent.com/19286219/115886786-8ecc6c00-a451-11eb-9f2e-a8db285a66a3.png)<br><br>
![QUESTIONNAIRE](https://user-images.githubusercontent.com/84018042/117865418-3d680d80-b296-11eb-8657-aca5c4352c6a.png)

<h2><strong>CHOISIR LE FORMAT D'EXTRACTION</h2></strong><br>

Une fois complété ou lors du remplissage du questionnaire vous pouvez à tout moment choisir le format d’extraction et le « Template » IFBxxxxx dans 

![image](https://user-images.githubusercontent.com/19286219/115886841-9f7ce200-a451-11eb-881a-5adc397d6546.png)

![image](https://user-images.githubusercontent.com/60437839/120227753-12942800-c24a-11eb-9c24-dbaf69d7d8ba.png)

<h2><strong>CREER UN DOCUMENT</h2></strong><br>
Choisir le menu 

![image](https://user-images.githubusercontent.com/19286219/115886914-b0c5ee80-a451-11eb-9f47-1f11efb9d600.png)![image](https://user-images.githubusercontent.com/19286219/115886934-b4597580-a451-11eb-8171-0dcf8e057c92.png)

![image](https://user-images.githubusercontent.com/60437839/120228066-b1b91f80-c24a-11eb-926c-dfeba883eb6a.png)

puis « Create ». Votre document est maintenant disponible dans votre environnement « Projet » : <br><br>
![image](https://user-images.githubusercontent.com/60437839/120228238-052b6d80-c24b-11eb-8521-746a8c415e9c.png)

<h2><strong>QUESTIONS/REPONSES</h2></strong><a id="faq"></a><br>

* <strong>Quelle différence entre les PGDs Structure et les PGDs Projets ? </strong> Un PGD structure décrit la gestion des données pour une structure, suivant les types de données. Il n'est pas associé à des dates. Un PGD projet est associé à un projet scientifique, il est associé à un planning de réalisation, avec des dates. Le PGD Structure peut permettre de remplir un PGD projet, lorsque le projet utilise une structure productrice de données. Voir aussi le document SchemaRelationPGDs.pdf.<br>
* <strong>Pourquoi ne pas utiliser DMP OPIDOR? </strong>  Nous utilisons dans le cadre de ce projet DSW pour ses fonctionnalités de travail collaboratif et sa visibilité et utilisation européenne. DMP Opidor présente lui l'avantage d'une interface beaucoup plus simple pour l'utilisateur. Un recrutement est en cours pour permettre les transferts de DMP d'une solution à une autre, notre but est de déposer les versions finalisées après ce travail collaboratif sur DMP OPIDOR. <br>
