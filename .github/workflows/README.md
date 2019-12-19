Définir la stratégie de l’application :

Dans le cadre du projet lié au site https://www.hatvp.fr, les fichiers en format CSV de la Haute Autorité pour la transparence de la vie publique, nous donnent accès à un répertoire de représentants d’intérêt en lien avec les responsables publics.
 
Afin de faciliter la lecture et l’exploitation de ces données en open sources, nous avons élaborés 2 stratégies pour n’en choisir qu’une seule :

IDÉE NUMÉRO 1 :
Notre première idée était de créer une application qui à partir d’une thématique juridique (exemple : l’environnement) affiche l’ensemble des organisations qui ont des intérêts liés à cette thématique, ainsi que la hauteur des montants investis. 

Nous voulions également afficher les responsables publics en lien avec des représentants privés, afin de mettre en lumière les activités des professionnels publics en matière de lobbying. 

Toutefois, le sujet étant particulièrement sensible et le public globalement non averti de ce qui fait l’actualité, plus important encore, le manque de données précises et claires ne nous permettent pas de pousser notre idée à son terme. Puisqu’il faudrait pour cela, catégoriser chaque thématique au cas par cas : nous avons renoncé à cette amusante façon d’aborder le projet. 

IDÉE NUMÉRO 2
Notre seconde idée, plus viable est de créer un générateur de données. Ainsi lorsqu’on sélectionne des données telles que : 
Le nom et prénom
La ville
L’update la plus récente
L’identifiant national
La dénomination
Le code postal
La dénomination 
Etc.

On retrouverait ainsi les déclarations des responsables publics et privés, des plus récentes aux plus anciennes.

Le choix de ces catégories d’action se ferait via l’usage de plusieurs CTA centrés sur l’interface principal afin de présélectionner une information et de limiter le risque de fautes d’orthographe. (dans un prénom ou nom, par exemple) 

Pour améliorer la navigation il faudrait idéalement coder un menu déroulant nous permettant d’effectuer les recherches par :
Ordre chronologique
Chronologie inversée
Par ordre alphabétique
Un calendrier daté

L’application serait également pourvue d’un footer et d’un espace archive pour consulter les données en vrac, selon la date de leur dernier ajout. 

Et des profils de chaque acteur public seront disponible, photo à l’appui, toujours dans le but de maximiser qualitativement l’expérience utilisateur. 

Notre avancée : 
Création du site grâce au framework Django
Nous avons commencé par créer notre projet sur Django grâce à la commande
$django-admin startproject mysite.
Puis nous avons crée le backoffice du site grâce à la commande 
$python manage.py createsuperuser  

Pour commencer le projet nous avons utilisé
$python manage.py startap <nom-app>
Ensuite pour créer et sauvegarder les modèles nous devons  passer par les répertoires  <nom-app>.models ainsi que  <nom-app>.admin
python manage.py makemigration permet de réaliser et créer des nouvelles migrations en fonction des modifications apportées aux modèles

Difficultés techniques inhérentes au projet : 

Puisque notre groupe, actuellement constitué de 6 personnes, est dans une impasse technique. Nous avons décidé chacun de nous abreuver de différentes ressources et tutoriels afin de rassembler nos forces et mener notre projet à bien : 

Nous nous sommes formés à l’utilisation de Django grâce à ces tutoriels
 
https://www.youtube.com/watch?v=JT80XhYJdBw&t=4824s
https://www.youtube.com/watch?v=SjRlmyEVXq4

Et à la documentation officielle 
https://docs.djangoproject.com/en/3.0/intro/tutorial01/

Et nous envisageons éventuellement d’utiliser cet outil pour coder (même si, nous le savons, l’outil ne fait pas l’ouvrier)
https://www.jetbrains.com/fr-fr/pycharm/

