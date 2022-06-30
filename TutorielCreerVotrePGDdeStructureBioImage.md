Chers collègues,

Vous avez mis en place une base de données d’images dans votre structure en ayant conscience que cela permet d’augmenter la traçabilité des données de la recherche en répondant de façon implicite au [concept FAIR](https://www.go-fair.org/fair-principles/), soit « Facile à découvrir, Accessible, Interopérable, Réutilisable ». Ce concept est l’un des piliers de la Science Ouverte. La mise en place d'un Plan de Gestion de Données associé à votre structure (PGD de structure) est la formalisation du processus de gestion de vos  données décrivant les moyens permettant de les rendre visibles, accessibles, et réutilisables quel que soit le demandeur.
Dans le but de vous faciliter la moisson de ces informations, un projet de « PGD structure bioimagerie », porté par et réalisé conjointement avec les Infrastructures Nationales en Biologie Santé (INBS) « France-BioImaging » (FBI), « Institut Français de Bioinformatique » (IFB), et « le Centre National De Ressources Biologiques Marines » (EMBRC-France), ainsi que l'Université Côte d'Azur, est en cours d’élaboration.

Cette initiative à destination des usagers de votre structure facilitera d'une part la communication autour de votre gestion de données, et d'autre part la conception des PGDs projets. En effet, cela permettra à terme que les champs idoines du PGD projet soient automatiquement renseignés par les informations déjà glanées en amont. Par exemple, s'il s'agit du PGD d'un projet émargeant à votre structure, l'utilisateur remplissant son PGD pourra trouver des recommandations et certains champs préremplis pour les données d'imagerie générées au sein de votre structure, et pourra le compléter à terme avec le PGD d'autres structures pour d'autres types de données.

Nous vous proposons de tester et nous donner votre avis sur le questionnaire générique, dédié à l'imagerie, destiné à moissonner ces informations en entrée puis de générer des documents à façon en utilisant des « Templates » ou gabarits d’extraction. <br><br>

[Comment contribuer?](#contribuer)<br> 
[Terminologie](#terminologie)<br> 
[Profils Utilisateurs](#profil)<br> 
[Workflow](#workflow)<br> 
[Partager](#partager)<br> 
[Questions-Réponses](#faq)<br> 

<h2><strong> COMMENT CONTRIBUER ?</strong></h2><a id="contribuer"></a><br> 
Pour participer à la création de ce PGD Structure productrice d'imagerie, deux propositions :<br>  
<br>  


* Vous pouvez consulter sans être identifié [un questionnaire non éditable générique](https://dsw.france-bioinformatique.fr/projects/d1b4abf4-9b7f-45d0-9450-79b010b51187), et un [exemple pour une plateforme](https://dsw.france-bioinformatique.fr/projects/aee67ccc-6eaa-4cd7-acc4-f6300c0e25b9). Notez que vous ne pourrez pas remplir ce questionnaire ni voir les différentes listes d'options disponibles. Vous pourrez faire remonter vos remarques/questions en utilisant la fonctionnalité "Comments" pour soumettre vos questions/problèmes/suggestions d'améliorations. Cette fonction "Comments" est visible à la lecture du questionnaire ainsi : 


<kbd><img width="1000" alt="Comments.a" src="https://user-images.githubusercontent.com/47455219/175924330-48ba6b97-7177-4df5-9584-792bf9bbed26.png"></kbd>

En cliquant sur cet onglet on accède aux fils de discussion et on peut y contribuer. Il est aussi possible de créer un fil de discussion pour chaque question en cliquant sur les bulles qui s'affichent à coté de leur intitulé :

<kbd><img width="1000" alt="Comments.b" src="https://user-images.githubusercontent.com/47455219/175924491-a5185cfb-7675-4938-a179-e50c8a96e040.png"></kbd>

Les fils de discussion montreront l'historique de le conversation ; il est aussi possible de consulter les discussions résolues. Votre nom ne sera pas affiché donc n'hésitez pas à accéder à votre compte pour que les développeurs puisse revenir vers vous<kbd> si nécessaire. 


* Vous pouvez aussi tester l'outil en y apportant les réponses pour votre structure (qui seront privées par défaut sauf si vous décidez de les partager, voir le paragraphe ["Partager"](#partager)). Pour cela nous vous invitons, avec un statut de ["Researcher"](#profil) à suivre le workflow proposé ci-dessous qui vous permettra de créer, de compléter et d'exporter votre propre PGD de structure. Pour pouvoir éditer votre propre questionnaire vierge, il vous faut [créer un compte sous l'application Data Stewardship Wizard (DSW)](https://dsw.france-bioinformatique.fr/signup). Vous pourrez également utiliser la fonctionnalité de commentaires sur les questions décrites ci-dessus, ou [émettre des suggestions générales](https://gitlab.com/ifb-elixirfr/fair/gt2-is1-mudis4ls/gt2/-/issues) sur gitlab.



<h2><strong>TERMINOLOGIE</strong></h2><a id="terminologie"></a><br> 

<kbd><img width="600" alt="Presentationrelationdocuments" src="https://user-images.githubusercontent.com/19286219/125417057-026b8898-b603-4e70-beae-bb91004a1bae.png"></kbd>

* <strong>Les « Knowledge Models » (KM)</strong> : formats pré-établis de questionnaires vides. Base de connaissances à partir de laquelle un questionnaire est généré. Identifié par un KM ID. Il peut être personnalisé/publié/exporté/importé.

* <strong>Les projets ou questionnaires </strong> : représentation d'un KM sous la forme d'un formulaire à remplir.

* <strong>Les (output) templates </strong> : gabarits d’extraction ; c'est à dire une mise en forme et une sélection des champs du questionnaire pour en produire un <strong>document</strong> dans des formats divers (Word, JSON, HTML, ...) qui seront accessibles dans l'onglet "Documents" d'un questionnaire. Ces gabarits sont encore limités mais sont un outil très puissant pour ne pas rentrer plusieurs fois les mêmes informations, en permettant le reformattage sur une mise en forme attendue par différents acteurs (financeurs, gestionnaire de base de données,...). Par exemple, pour les gestionnaires de base de données un des gabarits permettra d’extraire l’ensemble du document complété.


<h2><strong>WORKFLOW</strong></h2><a id="workflow"></a><br>

<kbd><img width="700" alt="DSW Workflow-03" src="https://user-images.githubusercontent.com/84018042/117858359-1c032380-b28e-11eb-94ec-167659eaa82c.png"></kbd>

<h2><strong>PROFILS UTILISATEURS</strong></h2><a id="profil"></a><br>

Il existe 4 rôles différents pour un profil utilisateur :<br>   

<strong>Anonymous</strong> : utilisateur de DSW qui n'est pas encore connecté. Elle/il peut s'inscrire, se connecter ou récupérer son mot de passe si oublié.<br><br>
<strong>Researcher</strong> : ce rôle est attribué par défaut aux utilisateurs après leur inscription. Nous partirons du principe que seuls les administrateurs pourront modifier ces rôles. Cet utilisateur travaille sur un projet scientifique et a les connaissances sur le projet en question. Son objectif est de créer un plan de gestion des données FAIR.<br>    
<strong>Data Steward</strong> : utilisateur qui a la responsabilité de concevoir les modèles de PGD ; elle/il peut créer des « knowledge models ». Ceux-ci sont ensuite utilisés par les scientifiques (ayant le rôle de Researcher) pour créer le PGD avec le questionnaire.<br><br>
<strong>Administrator</strong> : elle/il gère les paramètres généraux et dispose des privilèges les plus élevés.<br><br>  
   
<h2><strong>CREER UN PROJET</strong></h2><br>

Après avoir obtenu un accès :  <img width="200" alt="acces" src="https://user-images.githubusercontent.com/19286219/115886454-3b5a1e00-a451-11eb-97f9-542e76f85d6d.png">, vous pouvez utiliser l’ensemble des fonctionnalités de l’outil DSW :

<kbd><img width="200" alt="dsw" src="https://user-images.githubusercontent.com/47455219/136909954-7ea3617f-5f8f-4196-b9ce-9c7d9057f42e.png"></kbd>

Pour remplir votre propre questionnaire, procédez comme suit : <img width="200" alt="remplir_a" src="https://user-images.githubusercontent.com/19286219/115886648-6d6b8000-a451-11eb-850c-357b62142269.png">, puis <img width="100" alt="remplir_b" src="https://user-images.githubusercontent.com/19286219/115886669-74928e00-a451-11eb-88f9-777cbc12be9c.png">


<strong>ALLER SUR l'ONGLET CUSTOM</strong> puis nommez votre projet comme suit "PGD Nom de votre labo ou plateforme" en utilisant le « Knowledge Model » : "Modèle de PGD structure pour la bioimagerie". La dernière version du « Knowledge Model » s'affichera automatiquement :

<kbd><img width="1000" alt="create_project" src= "https://user-images.githubusercontent.com/47455219/176402267-36b346d9-1e37-4052-b950-1a5e1cb2f951.png"></kbd>

Au 29/06/22 nous en sommes à la version 1.4.8, néanmoins notez que les montées en version vont être nombreuses, dont certaines assez rapprochées, au cours des mois suivants. 

Sauvegardez ; votre projet est maintenant disponible dans <img width="200" alt="dispo" src="https://user-images.githubusercontent.com/19286219/115886735-8411d700-a451-11eb-9337-ea85e8962af3.png">. Par défaut, uniquement les projets auxquels vous avez accès seront listés :

<kbd><img width="1000" alt="create_project" src= "https://user-images.githubusercontent.com/47455219/176413787-e3eb2faa-ca71-4b81-bda7-08961f82586d.png"></kbd>

<h2><strong>REMPLISSAGE DU QUESTIONNAIRE</strong></h2><br>
A la création du questionnaire, aucune question n'apparait :

<kbd><img width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176402558-68f13846-d9b9-494a-8905-5822136ea916.png"></kbd>

Il va falloir ajouter les questions ("Add"). Typiquement, une seule itération est nécéssaire comme dans le cas d'informations sur la structure (à moins que plusieurs structures soient concernées) :

<kbd><img width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176402637-11cffbed-69eb-4db5-be1f-c4cb279045b7.png"></kbd>

Par contre, il est probable que le PGD décrive plusieurs produits de la recherche : les questions les concernant sont organisés d'une manière spécifique pour minimiser autant que faire se peut les doubles saisies. Au niveau supérieur de la hiérarchie, on retrouve deux questions, 'Les produits de la recherche' et 'Description des produits de la recherche'. Ces deux questions ont des objectifs différents.

<kbd><img width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176418892-82dc50b6-fdcd-44d7-8d57-993569f570b0.png"></kbd>

Une autre vue de cette même hiérarchie est donnée ici 

<kbd><img width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176451033-b7f85c62-540e-4543-b2da-7ca9af25e12f.png"></kbd>

   <h3 id="liste_produits"><strong>Question <i>Les produits de la recherche</i></strong></h3><br>

Le but de cette question est uniquement de recenser <em>tous</em> les produits de la recherche : pour chacun d'entre eux il sera nécessaire d'ajouter un bloc de questions dont le but est de recueillir le <a id="nom_label"> nom/étiquette/label</a>, l'identifiant (si déjà attribué/connu), et une description succinte. En particulier le nom/étiquette/label sera utilisé dans la suite du questionnaire pour associer les réponses aux produits de la recherche concernées par celles-ci (l'identifiant ne peut pas remplir ce rôle puisque tous les produits de la recherche n'ont pas d'identifiant, en particulier au début du projet).

<kbd><img width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176451337-9ff75e58-953e-47cf-824c-b16e77e5074c.png"></kbd>

<h3><strong>Question <i>Description des produits de la recherche</i></strong></h3><br>

Ici il suffit d'ajouter un seul bloc de questions :

<kbd><img width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176451377-3cd6793b-e917-43fc-8606-c30a9b798d1b.png"></kbd>

Ces questions (six en tout) vont guider la description détaillée des produits de la recherche listés <a href="#liste_produits"> plus haut</a>. Chacune de ces questions se décline elle même comme un bloc de questions dont la première vous demandera de préciser quels produits de la recherche sont concernés par les réponses qui vont suivre :  
   
<kbd><img id="liste_produits_sections" width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176465156-78feddef-a165-42f6-8d4b-8cc6ee138af9.png"></kbd>

Cela implique deux choses :  
   
1. Les produits de la recherche doivent être reférencés de manière consistante à travers le PGD, d'oú cette mention de <a href="#nom_label">nom/étiquette/label</a> qui est va servir à identifier de manière unique le produit de la recherche. Cela sera nécessaire lorsque le PGD sera lu/traité par des machines.
   
2. Il faudra créer autant de blocs de réponses que nécessité par la diversité des réponses possibles : en d'autres termes, si tous les produits de la recherche se décrivent de la même manière, un seul bloc de réponses suffira et tous les produits de la recherche seront listés <a href=#liste_produits_sections> ici </a> (en réalité, il suffira d'indiquer "tous" en lieu de la liste complète).
   
Cette manière de faire un peu lourde est rendue nécessaire car pour l'heure DSW ne permet pas la création d'une liste déroulante qui puisse être insérée en lieu et place de cette <a href=#liste_produits_sections> question</a>.
   
Finalement, notons que pour la deuxième question 
   
<kbd><img id="liste_produits_sections" width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176623334-db379e30-67fa-4c32-892d-2e12187743f2.png"></kbd>
   
la collecte de la liste des produits de la recherche associées aux réponses se décline un peu différement.
   
<h2><strong>CHOISIR LE FORMAT D'EXTRACTION</strong></h2><br>

Lors du remplissage du questionnaire vous pouvez à tout moment choisir le format d’extraction, c'est à dire le « Output Template » ; ceci est nécéssaire si vous voulez soit pre-visualiser le questionnaire, soit en créer un document. Pour cela, il faut renseigner l'onglet "Settings" du questionnaire :

<kbd><img width="1000" alt="project_start" src="https://user-images.githubusercontent.com/47455219/176631523-45f14f3f-bc01-42c0-90de-c1a44d36bbb9.png"></kbd>

Le mieux est de choisir "Questionnaire Report", qui est d'ailleurs celui recommandé, et HTML comme format par défaut pour la prévisualisation :

<kbd><img width="1000" alt="questionnaire_report" src="https://user-images.githubusercontent.com/47455219/176632011-6c2627b9-4947-40da-9693-af8bdf42d027.png"></kbd>

Un autre gabarit d'extraction qui peut se relever interessant, est 'Insight' qui vous permet de voir un déroulé complet de la hiérarchie des questions, avec les réponses si elles sont présentes :  

<kbd><img width="1000" alt="questionnaire_report" src="https://user-images.githubusercontent.com/47455219/176632547-b4ba899c-0b6e-4c43-8538-a8ef8a2c3257.png"></kbd>

Ce gabarit met en œuvre un semblant de 'dépliage/repliage' de la hierarchie des questions, cela n'est pas parfait (nous espérons l'améliorer dans les mois qui viennent) mais il permet de palier à la difficulté de renseigner un PGD un peu long dans DSW. En voici un aperçu 
   
<kbd><img width="1000" alt="insight_report" src="https://user-images.githubusercontent.com/47455219/176653123-10c91ca9-e495-4518-aa32-854a81d66607.png"></kbd>


<h2><strong>CREER UN DOCUMENT</h2></strong><br>

Choisir le menu <img width="100" alt="document_menu" src="https://user-images.githubusercontent.com/19286219/115886914-b0c5ee80-a451-11eb-9f47-1f11efb9d600.png"> puis « Create ».

<kbd><img width="1000" alt="document_create" src="https://user-images.githubusercontent.com/47455219/176645354-05853371-5b63-453c-89ee-6b319c16479e.png"></kbd>

Votre document est maintenant disponible dans votre environnement « Projet » : 

<kbd><img width="1000" alt="document_create" src="https://user-images.githubusercontent.com/47455219/176645854-0da2b6e9-e404-4d67-9d77-a3fa97ffb202.png"></kbd>

<h2><strong> PARTAGER UN PROJET</h2></strong><a id="partager"></a><br>

Choisir l'onglet PROJET, puis selectionner le projet que vous voulez partager. Pour accéder aux options du menu "SHARE", appuyez sur le bouton en haut à droite. <img width="100" alt="document_create" src="https://user-images.githubusercontent.com/84018042/134765728-b02acf41-dd3a-4d58-9b2c-84b63edc91a7.jpg" >


Vous avez ensuite la possibilité de partager vos projets avec vos collègues, qu'ils disposent ou non d'un compte utilisateur DSW. Pour vos collègues ayant créé un compte, vous avez la possibilité d'inviter des personnes spécifiques et leur attribuer des droits cumulatifs, de lecteur à propriétaire.


<kbd><img width="1000" alt="share_button" src="https://user-images.githubusercontent.com/47455219/176651590-c68b0aa1-291b-488d-ad10-2cf91859b712.png"></kbd>

<kbd><img width="1000" alt="share_a" src="https://user-images.githubusercontent.com/47455219/176646675-5f7b0e64-f90a-4acb-99d3-8d59a147461a.png" ></kbd>

Ensuite, vous pouvez choisir de refuser ou d'ouvrir l' accès aux utilisateurs connectés à DSW et de leur attribuer certains droits

<kbd><img width="1000" alt="share_b_n" src="https://user-images.githubusercontent.com/47455219/176650114-083519b7-d1ea-4602-89d9-a0bd5571c9f3.png" ></kbd>

Enfin, vous pouvez rendre le lien unique de votre PGD (questionnaire) complété lisible par tout utilisateur non connecté : il faudra envoyer le lien du questionnaire à ces utilisateurs.

<kbd><img width="1000" alt="share_c" src="https://user-images.githubusercontent.com/47455219/176650651-44fce06c-fea5-49b5-b243-fa2dbfb5503c.png" ></kbd>

Notons plusieurs choses :

* le choix des droits à attribuer est aussi une fonction des paramètres globaux que les administrateurs choisissent au départ ; il se pourrait donc que ce choix soit plus restreint que celui démontré ici,
* vous êtes tenus de respecter les droits à la protection des données personnelles et donc il vous incombe de veiller à la manière dont vous partagez les projets,
* finalement, notez que le partage des documents issus du projet est soumis aux droits afférents au "Projet".


<h2><strong>QUESTIONS/REPONSES</h2></strong><a id="faq"></a><br>

* <strong>Quelle différence entre les PGDs Structure et les PGDs Projets ? </strong> Un PGD structure décrit la gestion des données pour une structure, suivant les types de données. Un PGD projet est associé à un projet scientifique, à un planning de réalisation, avec des dates. Le PGD structure va servir à remplir un PGD projet qui utilise des données produites par cette structure. Plus généralement, un PGD structure aide la structure à tracer ces données du moment de leur création à leur livraison aux donneurs d'ordre, les porteurs de projets donc.

* <strong>Pourquoi ne pas utiliser [DMP OPIDoR] (https://dmp.opidor.fr) ? </strong> Nous utilisons dans le cadre de ce projet DSW pour ses fonctionnalités de travail collaboratif de conception de modèles de PGD, et sa visibilité et utilisation européenne. DMP OPIDoR présente lui l'avantage d'une interface beaucoup plus simple pour l'utilisateur qui renseigne le PGD. De plus DMP OPIDoR, depuis la version V3.0, présente un PGD structuré, partiellement _machine-actionable_ (qui s'appuie sur des flux d'échange de données automatisés), et qui permet des spécialisations de certaines rubriques. Un recrutement est en cours pour developper des passerelles entre les deux outils ; notre but est à terme de déposer les modèles de PGD finalisés sur DMP OPIDoR. <br>
