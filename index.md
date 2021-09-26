## A propos

J'ai commencé le développement il y a une dizaine d'années, je me suis assez vite orienté vers le web. 

En 2013, pour mon stage de fin de License professionnel, j'ai rejoint l'agence Highfive en tant que Développeur web. Suite à mon stage, j'ai fait mon Master en alternance puis j'ai été embauché en CDI.

En 2020, j'ai commencé à encadrer des TPs à raison d'une demie-journée par semaine du calendrier scolaire dans le cadre de la License informatique de la Fac de Caen.
J'encadre des TPs en License 3 pour les cours "Bases de la programmation côté serveur avec le langage PHP" au premier semestre et en Licence 1 pour les cours de "Bases de la programmation web côté client avec le langage JavaScript" au second semestre. 

## Projets

Depuis mon arrivée chez Highfive, j'ai eu l'occasion de travailler sur différentes typologies de projets pour différents clients. 

Cette page présente quelques projets sur lesquels j'ai travaillé.


### Liste des projets

Nom du projet | Explications | URL
--- | --- | ---
ttt | ttt | ttt

### Back (Framework PHP)

#### Extranet Coopcreully

Création d'une application web à disposition des adhérents de la Coopérative agricole à Creully. 

Sur cet extranet : 
- des données sont importés chaque jours à partir de fichiers CSV, 
- les données importées sont affichées pour les adhérents, certaines données sont propres à chaque adhérent et d'autres sont communes à tous les adhérents
- des données provenant de fichiers CSV sont aussi affichés en direct, 
- des données provenant d'un WordPress sont aussi affichés.  

Sur ce projet l'utilisation d'un WordPress pour permettre au client d'éditer facilement du contenu sur l'extranet est pertinente car il y a aussi un site WordPress pour présenter la Coopcreully.

Le framework Laravel a été utilisé pour ce projet.

#### Espace membre du Pôle Hippolia

Création d'une application web à disposition des membres du Pole Hippolia.

Sur cet espace membre : 

- Gestion des utilisateurs,
- Gestion des documents,
- Gestion des catégories de documents,
- Gestion des droits des utilisateurs par catégories de documents,
- Mis en place d'un webservice pour afficher les membres sur le site internet du Pôle Hippolia.

Le framework Symfony a été utilisé pour ce projet.

#### Espace producteur Terroirs de Lait (Savencia)

Reprise du projet développé par un autre développeur de l'agence. 
Je m'occupe des demandes d'évolutions (faisabilités, estimations, développements, tests, mise en production)

Sur cet espace producteur : 

- Import de données de données à partir de fichiers CSV, de fichiers PDF, 
- Affichage des données pour les producteurs,
- Liaison avec un WordPress qui est affiché uniquement pour les producteurs connectés à leurs espaces

Le framework Laravel a été utilisé pour ce projet.

#### Extranet du CEMC

Reprise du projet développé par un autre développeur de l'agence. 
Je me suis occupé de la finalisation du projet (développement des dernières fonctionnalités, corrections des bugs, mise en ligne). Je m'occupe maintenant des différentes demandes d'évolutions et de la maintenance de cet extranet.

Sur cet extranet : 
- Gestion d'un calendrier des cours
- Gestion des utilisateurs
- Gestion d'une médiathèque 
- Gestion d'une messagerie
- Gestion administratives (factures profs, ...)
- Affichage des spectacles de fins d'années (photos, dossiers à télécharger, vidéos)

Le framework Symfony a été utilisé pour ce projet.

#### Calendrier des brocantes (admin)

Reprise du projet développé par un autre développeur de l'agence.
Je m'occupe des demandes d'évolutions (faisabilités, estimations, développements, tests, mise en production) et de la maintenance

Sur ce projet : 

- Gestion de manifestations/événements
- Gestion des organisateurs/utilisateurs
- Envoi de mails personnalisés
- Webservice pour afficher les manifestations sur calendrier-des-brocantes.com

Le framework Laravel a été utilisé pour ce projet.

#### Autres

J'ai aussi été amené à travailler sur des plus petits projets pour Bayeux Museum, Attitude Manche, Gipsy Toys, AD Normandie. 
Ces projets ne sont plus disponibles. 
Ils s'agissaient d'espaces privées de partages de documents, de formulaires spécifiques, ...

---

### Front (WordPress, Intégration)

Pour la plupart des projets, le CMS WordPress a été utilisé

#### Calvados Tourisme & Vivre dans le Calvados

Reprise du projet développé par un autre développeur de l'agence.
Pour le développement de Calvados Tourisme, c'est un autre développeur qui avait commencé à travailler dessus, j'ai été chargé de finaliser le projet et de sa mise en ligne. Sur cette première version du projet, nous utilisions uniquement WordPress.

Sur ce projet (Calvados Tourisme) : 
- Page de sommaires, éditoriales administrables par le client,
- Import des données/offres du système d'information du Calvados (Tourinsoft)
- Affichage de listing et de fiches de ces offres
- Affichage de formulaire lié à Tourinsoft

Pour la deuxième version du projet et le développement de Vivre dans le Calvados, nous avons géré l'import des données grâce à système externe que nous avons développé sur le framework Symfony. Nous avons été deux développeurs à travailler sur celui-ci, mon collègue a élaboré toute la structure et j'ai continué et finalisé les développement.


Suite à la sortie de Vivre dans le Calvados, nous avons mis en place le système sur Calvados Tourisme pour que la maintenance de ces deux sites soit plus simple.

Pour la sortie du site Calvados Tourisme, j'ai aussi été amené à developper un jeu concours que nous avons développé sur mesure. Il s'agissait pour l'internaute, de naviguer sur le site et de trouver trois illustrations (et cliquer dessus), une fois qu'il avait trouvé ces trois illustrations, il y avait un formulaire d'inscription.

Actuellement, je m'occupe des demandes d'évolutions sur les deux sites et leurs maintenances.

Sur ce site, un travail de SEO un peu plus conséquent qu'habituellement a été réalisé, en suivant les recommandations d'une agence spécialisée.

#### Chemins de la Baie (en développement)

Développement d'un site sur WordPress avec de l'e-commerce (WooCoomerce) et une liaison à une API.

L'API mis à disposition par une autre société permet plusieurs choses :
- Récupérer les sorties disponibles pour les traversées de la Baie du Mont-Saint-Michel pour les afficher sur le site,
- Envoyer les informations de réservations suite à la commande d'un utilisateur sur le site (pour que ces informations soient disponibles dans l'outil de compta du client).

Le WooCommerce permet de gérer toute la partie panier, paiement, gestion du compte.
Une partie éditoriale est aussi présente sur le site (Gutenberg).

Ce projet est en cours de finalisation, il ne devrait pas tarder à être disponible.

#### Calendrier des brocantes 

Développement d'un site sur WoordPress avec de l'e-commerce (WooCommerce) et une laison à un webservice.

Le webservice permet de récupérer les manifestations et les afficher dans des listings et des fiches.

Le WooCommerce permet de commandes des livres papiers du Calendrier des brocantes et de réserver des encarts publicités sur les listings et fiches des manifestations.

Une partie plus éditoriale est aussi présente sur le site pour gérer le blog.

Avant la refonte de Calendrier des brocantes (admin), anciennement Géopuces, c'était une autre société qui nous fournissait le webservice.

Sur ce site, un travail de SEO un peu plus conséquent qu'habituellement a été réalisé, en suivant les recommandations d'une agence spécialisée.

#### Baclesse & Protonthérapie

Refonte du site de Baclesse.

Nous sommes ici sur un site "vitrine" en multilingue (français, anglais). Le client a la main sur tous les contenus du site.

#### Mon Stage dans la Manche

Développement d'une plateforme d'offres de stages, où les lycéens peuvent s'inscrire et postuler à des offres et où les entreprises peuvent proposer des offres de stages, gérer les candidatures.

Sur ce site, on sort du cadre classique de WordPress, avec une utilisation plus poussée des utilisateurs, de formulaires (déclenchements d'actions suite à la soumission de formulaire), ...

#### Ma vie dans la Manche

Reprise du projet développé par un autre développeur de l'agence.

Développement des évolutions sur et maintenance sur celui-ci.

Parmi, les évolutions, j'ai été amené à développer un import d'offres d'emplois venant de l'API de Pole Emploi.

#### Normandinamik

Refonte d'un site des "articles de presse".

Petite particularité, l'ancien site étant sur Drupal, il a fallu développer un petit outil pour importer les articles sur le WordPress

Sur ce site, un travail de SEO un peu plus conséquent qu'habituellement a été réalisé, en suivant les recommandations d'une agence spécialisée.

#### Pôle TES

Développement d'un site éditorial et d'un sous-site d'actualités. 

WordPress assez classique, avec ACF et les custom post types.

#### Fédération des guides de Normandie

Développement d'un site présentation les guides de l'assocation. 

WordPress éditorial assez classique, où le client a la main sur le contenu.

Chaque guide a un compte sur le site, avec son compte, il peut gérer sa fiche, gérer son planning de disponibilités, créer des événements pour des visites, ...

#### Adepta

Développement d'un site constitué de plusieurs sous-sites (grâce à la fonctionnalité Multi-site de WordPress).

Le site principal a un thème unique avec de l'éditorial, ...
Les sous-sites partage un même thème avec une même typologie de site avec des couleurs différentes.

#### Calvados

Intégration HTML, CSS, JS des maquettes pour le Calvados.

Les gabarits sont utilisés sur plusieurs sites du département.

#### Festou (Intérim & Recrutement)

Développement de sites d'offres d'emploi saisis dans l'administration du site et des offres venant de webservices.

#### Autres 

- Caen Evenements
- Centre aquatique Auréo
- Vital Epargne Immobilier
- Le journal de Suzon (Mémorial)

Participation au développement, évolutions et maintenance des sites :

- Dejamobile 
- Caen Normandie Développement
- Normandie Aménagement

---

### Autres

J'ai aussi travaillé sur des projets d'applications mobiles. 

#### Application mobile GéoMares

#### Application mobile Mémorial Rockwell : Audioguide

Développer en React Native

#### Application mobile Mémorial

#### Application mobile Mam'route
