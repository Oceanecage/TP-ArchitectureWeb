<h1>TP Architecture</h1>
<p>Voici le fichier PHP permettant de gérer la pagination d'une liste de commentaire.</p>
<p>Veuillez cloner mon dépot et déposer sur le votre (en ligne) une version corrigée du tp.<br>
Vous prendrez en charge les extrémités (première page et dernière page) dans l'affichage des numéros de pages.</p>

<p>Afin de mener à bien ce TP, je suis passée par plusieurs étapes :</p>

<p><H6>- CREATION D'UN NOUVEAU REPOSITORY :</H6></p>
<p>Je me suis connectée sur mon compte GitHub afin d'y créer un nouveau repository appellé "TP-ArchitectureWeb" dans lequel j'allais pouvoir effectuer le clonage du dossier "mère" et ensuite retransferer mon dossier. </p>

<p><H6>- CLONAGE DANS LE DEPOT :</H6></p>
<p>Afin de cloner le dossier mère, j'ai téléchargée GitBash afin de permettre ce clonage. J'ai dans un premier temps rentré le dossier dans lequel j'allais effectuer le clonage grâce au git clone. Puis j'ai lié ce dossier à l'adresse url où se situais le dossier et j'en ai obtenue l'accès, ce qui m'a permis de recevoir un clone des dossiers mères dans mon dossier personnel. J'ai ensuite lié les dossiers afin que les mises à jours soient effectuées grâce au gitpush.</p>

<p><H6>- CREATION DE LA BASE DE DONNEES :</H6></p>
<p>J'ai ensuite été sur le simulateur de serveur Wamp afin d'y créer ma base de données comprenant 3 informations : id de la clef primaire, le nom de la variable et le contenu de cette variable.</p>

<p><H6>- CORRECTIONS SUR LE FICHIER :</H6></p>
<p>Les corrections que j'ai apportés au fichier PHP m'ont été possible à l'aide de la base de données. En effet, le fichier PHP n'est fonctionnel que lorsqu'il est lié à une base de données PHPmyAdmin. J'ai alors vérifiée et fait en sorte, après plusieurs essais, que la pagination soit correctement affichée sur les premières et dernières pages, sans afficher de pagination sur les pages non existantes. Il a fallu pour cela faire en sorte que le formulaire soit compris entre la première et dernière page.</p>

<p><H6>- INTEGRER LICENCE ET DROITS D'UTILISATIONS :</H6></p>
<p>J'aurai aimer intégrer la licence</p>