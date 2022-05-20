Chers collègues,

Vous avez mis en place une base de données d’images dans votre structure en ayant conscience que cela permet d’augmenter la traçabilité des données de la recherche en répondant de façon implicite au [concept FAIR](https://www.go-fair.org/fair-principles/), soit « Facile à découvrir, Accessible, Interopérable, Réutilisable ». Ce concept est l’un des piliers de la Science Ouverte. La mise en place d'un Plan de Gestion de Données associé à votre structure (PGD de structure) est la formalisation du processus de gestion de vos  données décrivant les moyens permettant de les rendre visibles, accessibles, et réutilisables quel que soit le demandeur.
Dans le but de vous faciliter la moisson de ces informations, un projet de « PGD structure bioimagerie », porté par et réalisé conjointement avec les Infrastructures Nationales en Biologie Santé (INBS) « France-BioImaging » (FBI), « Institut Français de Bioinformatique » (IFB), et « le Centre National De Ressources Biologiques Marines » (EMBRC-France), ainsi que l'Université Côte d'Azur, est en cours d’élaboration.

Cette initiative à destination des usagers de votre structure facilitera d'une part la communication autour de votre gestion de données, et d'autre part la conception des PGDs projets. En effet, cela permettra à terme que les champs idoines du PGD projet soient automatiquement renseignés par les informations déjà glanées en amont. Par exemple, s'il s'agit du PGD d'un projet émargeant à votre structure, l'utilisateur remplissant son PGD pourra trouver des recommandations et certains champs préremplis pour les données d'imagerie générées au sein de votre structure, et pourra le compléter à terme avec le PGD d'autres structures pour d'autres types de données.

Nous vous proposons de tester et nous donner votre avis sur le questionnaire générique, dédié à l'imagerie, destiné à moissonner ces informations en entrée puis de générer des documents à façon en utilisant des « Templates » d’extraction. <br><br>

[Comment contribuer?](#contribuer)<br> 
[Terminologie](#terminologie)<br> 
[Profils Utilisateurs](#profil)<br> 
[Workflow](#workflow)<br> 
[Partager](#partager)<br> 
[Questions-Réponses](#faq)<br> 

<h2><strong> COMMENT CONTRIBUER?</h2></strong><a id="contribuer"></a><br> 
Pour participer à la création de ce PGD Structure productrice d'imagerie, deux propositions :<br>  
<br>  


* Vous pouvez consulter sans être identifié [un questionnaire non éditable générique](https://dsw.france-bioinformatique.fr/projects/30bc910d-60c1-4a49-a77f-17db454bae91), et un [exemple pour une plateforme](https://dsw.france-bioinformatique.fr/projects/98f4dc29-d729-46e1-ac0e-b9100578db19). Notez que vous ne pourrez pas remplir ce questionnaire ni voir les différentes listes d'options disponibles. Vous pourrez faire remonter vos remarques/questions en utilisant la fonctionnalité "Comments" pour soumettre vos questions/problèmes/suggestions d'améliorations. Cette fonction "Comments" est visible à la lecture du questionnaire ainsi : 


<img width="600" alt="Comments.a" src="https://user-images.githubusercontent.com/47455219/136796837-cde03c3f-5b73-4e03-8a91-4aaa5af3c571.png">

En cliquant sur cet onglet on accède aux fils de discussion et on peut y contribuer. Il est aussi possible de créer un fil de discussion pour chaque question en cliquant sur les bulles qui s'affichent à coté de leur intitulé :

<img width="600" alt="Comments.b" src="https://user-images.githubusercontent.com/47455219/136796880-358e5e3d-949b-46dd-b3ea-6fb0f075353d.png">

Les fils de discussion montreront l'historique de le conversation ; il est aussi possible de consulter les discussions résolues. Votre nom ne sera pas affiché donc n'hésitez pas à signer pour que les développeurs puisse revenir vers vous si nécessaire. 


* Vous pouvez aussi tester l'outil en y apportant les réponses pour votre structure (qui seront privées par défaut sauf si vous décidez de les partager, voir le paragraphe ["Partager"](#partager)). Pour cela nous vous invitons, avec un statut de ["Researcher"](#profil) à suivre le workflow proposé ci-dessous qui vous permettra de créer, de compléter et d'exporter votre propre PGD de structure. Pour pouvoir éditer votre propre questionnaire vierge, il vous faut [créer un compte sous l'application Data Stewardship Wizard (DSW)](https://dsw.france-bioinformatique.fr/signup). Vous pourrez également utiliser la fonctionnalité de commentaires sur les questions décrites ci-dessus, ou [émettre des suggestions générales](https://gitlab.com/ifb-elixirfr/fair/madmp-bioimage/-/issues) sur gitlab.



<h2><strong>TERMINOLOGIE</h2></strong><a id="terminologie"></a><br> 

<img width="600" alt="Presentationrelationdocuments" src="https://user-images.githubusercontent.com/19286219/125417057-026b8898-b603-4e70-beae-bb91004a1bae.png">

* <strong>Les « Knowledge Models » (KM)</strong> : formats pré-établis de questionnaires vides. Base de connaissances à partir de laquelle un questionnaire est généré. Identifié par un KM ID. Il peut être personnalisé/publié/exporté/importé.

* <strong>Les projets ou questionnaires </strong> : représentation d'un KM sous la forme d'un formulaire à remplir.

* <strong>Les (output) templates </strong> : gabarits d’extraction ; c'est à dire une mise en forme et une sélection des champs du questionnaire pour en produire un <strong>document</strong> dans des formats divers (Word, JSON, HTML, ...) qui seront accessibles dans l'onglet "Documents" d'un questionnaire. Ces gabarits sont encore limités mais sont un outil très puissant pour ne pas rentrer plusieurs fois les mêmes informations, en permettant le reformattage sur une mise en forme attendue par différents acteurs (financeurs, gestionnaire de base de données,...). Par exemple, pour les gestionnaires de base de données un des gabarits permettra d’extraire l’ensemble du document complété.


<h2><strong>WORKFLOW</h2></strong><a id="workflow"></a><br>

<img width="700" alt="DSW Workflow-03" src="https://user-images.githubusercontent.com/84018042/117858359-1c032380-b28e-11eb-94ec-167659eaa82c.png">

<h2><strong>PROFILS UTILISATEURS</h2></strong><a id="profil"></a><br>

Il existe 4 rôles différents pour un profil utilisateur :<br>   

<strong>Anonymous</strong> : utilisateur de DSW qui n'est pas encore connecté. Elle/il peut s'inscrire, se connecter ou récupérer son mot de passe si vous l'avez oublié.<br><br>
<strong>Researcher</strong> : ce rôle est attribué par défaut aux utilisateurs après leur inscription. Nous partirons du principe que seuls les administrateurs pourront modifier ces rôles. Cet utilisateur travaille sur un projet scientifique et a les connaissances sur le projet en question. Son objectif est de créer r un plan de gestion des données FAIR.<br>    
<strong>Data Steward</strong> : utilisateur qui a la responsabilité de concevoir les modèles de PGD ; il peut créer des « knowledge models ». Ceux-ci sont ensuite utilisés par les scientifiques (ayant le rôle de Researcher) pour créer le PGD avec le questionnaire.<br><br>
<strong>Administrator</strong> : elle/il gère les paramètres généraux et dispose des privilèges les plus élevés.<br><br>  
   
<h2><strong>CREER UN PROJET</h2></strong><br>

Après avoir obtenu un accès :  <img width="200" alt="acces" src="https://user-images.githubusercontent.com/19286219/115886454-3b5a1e00-a451-11eb-97f9-542e76f85d6d.png">, vous pouvez utiliser l’ensemble des fonctionnalités de l’outil DSW :

<img width="200" alt="dsw" src="https://user-images.githubusercontent.com/47455219/136909954-7ea3617f-5f8f-4196-b9ce-9c7d9057f42e.png">

Pour remplir votre propre questionnaire, procédez comme suit : <img width="200" alt="remplir_a" src="https://user-images.githubusercontent.com/19286219/115886648-6d6b8000-a451-11eb-850c-357b62142269.png">, puis <img width="100" alt="remplir_b" src="https://user-images.githubusercontent.com/19286219/115886669-74928e00-a451-11eb-88f9-777cbc12be9c.png">


<strong>ALLER SUR l'ONGLET CUSTOM</strong> puis nommez votre projet comme suit "PGD Nom de votre labo ou plateforme" en utilisant le « Knowledge Model » : "Modèle de PGD structure pour la bioimagerie" (pour l'heure, utilisez la version V1.3.10 comme indiqué : les versions ultérieures ne sont encore que des ébauches) :

<img width="1000" alt="create_project" src= "https://user-images.githubusercontent.com/47455219/161218048-c7100c2a-e970-4443-af3d-ee86105b534b.png">


Sauvegardez ; votre projet est maintenant disponible dans <img width="200" alt="dispo" src="https://user-images.githubusercontent.com/19286219/115886735-8411d700-a451-11eb-9337-ea85e8962af3.png">

<h2><strong>REMPLISSAGE DU QUESTIONNAIRE</h2></strong><br>
A la création du questionnaire, aucune question n'apparait :

<img width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/136815048-33e403ce-3fca-4347-b848-dd92373e041d.png">

Il va falloir ajouter les questions ("Add"). Typiquement, une seule itération est nécéssaire comme dans le cas d'informations sur la structure (à moins que plusieurs structures soient concernées) :


<img width="600" alt="project_start" src="https://user-images.githubusercontent.com/47455219/136815619-b9d393e7-9900-4108-8732-603f0d899e7d.png">

Par contre, il est probable que le PGD décrive plusieurs produits de la recherche :

<img width="600" alt="project_start" src="https://user-images.githubusercontent.com/47455219/136815599-6338d468-2c64-46da-ab3b-02f5764f3424.png">

Dans ce cas, il faudra ajouter un block "Produit de la recherche" autant de fois que nécéssaire. Ceci se repétera pour toute question. Vous êtes prêts à compléter le questionnaire. Les encadrés vous permettent de suivre l'imbrication des questions, ainsi que la numérotation des questions. 

<h2><strong>CHOISIR LE FORMAT D'EXTRACTION</h2></strong><br>

Lors du remplissage du questionnaire vous pouvez à tout moment choisir le format d’extraction, c'est à dire le « Output Template » ; ceci est nécéssaire si vous voulez soit pre-visualiser le questionnaire, soit en créer un document. Pour cela, il faut renseigner l'onglet "Settings" du questionnaire :


<img width="600" alt="project_start" src="https://user-images.githubusercontent.com/47455219/136821413-befa9fab-bd1b-4903-be6c-4455ab515bf4.png">

Le mieux est de choisir "Questionnaire Report", qui est d'ailleurs celui recommandé, et HTML comme format par défaut pour la prévisualisation :

<img width="600" alt="questionnaire_report" src="https://user-images.githubusercontent.com/47455219/167566069-ed675397-a310-4179-99c0-6fa6d358a94b.png">


Un autre gabarit d'extraction qui peut se relever interessant, est 'Insight' qui vous permet de voir un déroulé complet de la hiérarchie des questions, avec les réponses si elles sont présentes :  

<img width="600" alt="questionnaire_report" src="https://user-images.githubusercontent.com/47455219/167565958-021f1342-d0d7-4d99-8e2d-81d6d7644a64.png">


<h2><strong>CREER UN DOCUMENT</h2></strong><br>

Choisir le menu <img width="100" alt="document_menu" src="https://user-images.githubusercontent.com/19286219/115886914-b0c5ee80-a451-11eb-9f47-1f11efb9d600.png"> puis « Create ».

<img width="600" alt="document_create" src="https://user-images.githubusercontent.com/47455219/167566612-81edda1f-84fd-4b02-9b44-11fbb0d31fe0.png" >

Votre document est maintenant disponible dans votre environnement « Projet » : 

<img width="600" alt="document_create" src="https://user-images.githubusercontent.com/47455219/167566995-84703ae0-779d-4940-af45-e5f020a91706.png" >

<h2><strong> PARTAGER UN PROJET</h2></strong><a id="partager"></a><br>

Choisir l'onglet PROJET, puis selectionner le projet ou le document que vous voulez partager. Pour accéder aux options du menu "SHARE", appuyez sur le bouton en haut à droite. <img width="100" alt="document_create" src="https://user-images.githubusercontent.com/84018042/134765728-b02acf41-dd3a-4d58-9b2c-84b63edc91a7.jpg" >


Vous avez ensuite la possibilité de partager vos projets avec vos collègues, qu'ils disposent ou non d'un compte utilisateur DSW. Pour vos collègues ayant créé un compte, vous avez la possibilité d'inviter des personnes spécifiques et leur attribuer des droits cumulatifs, de lecteur à propriétaire.


<img width="600" alt="share_button" src="https://user-images.githubusercontent.com/47455219/136914418-bfac4240-e979-4acf-947c-6b5990c75c5a.png" >

<img width="600" alt="share_a" src="https://user-images.githubusercontent.com/47455219/136914666-fd9f3abb-4877-4ae1-973c-37dcab41618f.png" >

Ensuite, vous pouvez choisir de refuser tout accès aux utilisateurs connectés à DSW 

<img width="600" alt="share_b_n" src="https://user-images.githubusercontent.com/47455219/136915640-7276a7ea-fb9d-49aa-8084-090a97619de0.png" >

ou au contraire leur attribuer certains droits

<img width="600" alt="share_b_y" src="https://user-images.githubusercontent.com/47455219/136916584-a5dcab8a-fb47-4e87-8812-8411016a21e8.png" >

Enfin, vous pouvez rendre le lien unique de votre PGD (questionnaire) complété lisible par tout utilisateur non connecté : il faudra envoyer le lien du questionnaire à ces utilisateurs.

<img width="600" alt="share_c" src="https://user-images.githubusercontent.com/47455219/136917529-aa042c5e-d9d9-4fdc-a1a8-c701f6bc995b.png" >

Notons plusieurs choses :

* le choix des droits à attribuer est aussi une fonction des paramètres globaux que les administrateurs choisissent au départ ; il se pourrait donc que ce choix soit plus restreint que celui démontré ici
* vous êtes tenus de respecter les droits à la protection des données personnelles et donc il vous incombe de veiller à la manière dont vous partagez les projets
* finalement, notez que le partage des documents issus du projet est soumis aux droits afférents au "Projet"


<h2><strong>QUESTIONS/REPONSES</h2></strong><a id="faq"></a><br>

* <strong>Quelle différence entre les PGDs Structure et les PGDs Projets ? </strong> Un PGD structure décrit la gestion des données pour une structure, suivant les types de données. Un PGD projet est associé à un projet scientifique, à un planning de réalisation, avec des dates. Le PGD structure va servir à remplir un PGD projet qui utilise des données produites par cette structure. Plus généralement, un PGD structure aide la structure à tracer ces données du moment de leur création à leur livraison aux donneurs d'ordre, les porteurs de projets donc.

* <strong>Pourquoi ne pas utiliser [DMP OPIDoR] (https://dmp.opidor.fr) ? </strong> Nous utilisons dans le cadre de ce projet DSW pour ses fonctionnalités de travail collaboratif de conception de modèles de PGD, et sa visibilité et utilisation européenne. DMP OPIDoR présente lui l'avantage d'une interface beaucoup plus simple pour l'utilisateur qui renseigne le PGD. De plus la dernière version de DMP OPIDoR est structurée, partiellement _machine-actionable_ (qui s'appuie sur des flux d'échange de données automatisés), et permet des spécialisations de certaines rubriques. Un recrutement est en cours pour developper des passerelles entre les deux outils ; notre but est à terme de déposer les modèles de PGD finalisés sur DMP OPIDoR. <br>
