Projet 2 Reservia

**Objectifs:**
• Intégrer une maquette en responsive HTML et CSS du site Réservia, outil de planification de vacances, de réservation d'hébergements et d'activités dans la ville de leur choix.
• Les hébergements peuvent également être filtrés par thématique, par exemple leur budget ou leur ambiance.

**Cahier des charges:**
• Les usagers pourront rechercher des hébergements dans la ville de leur choix. 
• Le champ de recherche est donc un champ de saisie, dont le texte peut être édité par l’usager. 
• En revanche, à ce stade, le bouton de recherche ne sera pas fonctionnel.
• Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité. • Pour l’instant les liens seront vides.
• Les filtres ne seront pas fonctionnels pour cette version, en revanche, il faut qu’ils changent d’apparence au survol. Je te laisse décider de l’effet le plus approprié.
• Dans le menu, les liens “Hébergements” et “Activités” sont des ancres qui doivent mener aux sections de la page.

**Contraintes techniques:**
1ère interlocuteur (Loïc)
• Deux maquettes : l’une desktop et l’autre mobile. Le site devra également être adapté aux tablettes (adaptations libres)

• Choisir le format le plus adapté par rapport à la résolution et au temps de chargement.

• Les icônes proviennent de la bibliothèque Font Awesome. Les couleurs de la charte sont le bleu #0065FC, et sa version plus claire #DEEBFF ainsi que le gris pour le fond #F2F2F2.

• La police du site est Raleway.
2ème interlocuteur (Sarah)
• Ne pas utiliser de framework ou pré-compilateur CSS ( utiliser du HTML et CSS)

• Utiliser Visual Studio Code, et ses plugins Live Server ou Prettier…

• Intégrer les icônes Font Awesome en HTML ou CSS.

• Utilisation de flexbox et Grid

• Le code devra utiliser les balises sémantiques et ne doit contenir aucune erreur ni alerte au validateur W3C HTML et CSS.

• Le site devra être compatible avec les dernières versions de Chrome et Firefox.

• Séparer le HTML et le CSS et organiser le dossier de rendu.

• Versionner le code avec Git (outils ligne de commande ou GitKraken) puis le déployer sur la page GitHub Pages ou GitLab


**Outils:**
Pour ce projet, j'ai utilisé l'éditeur **VISUAL STUDIO CODE**, les plugins **LIVE SERVER**, **PRETTIER** , **GITHUB** , **AUTO RENAME** , **Git add commit push**  et son terminal de commande **GITBASH** en essaie **Git Graph** et pour facilter l'envoie GitHub Desktop
**Livrables:**
• Un lien vers votre repository GitHub ou GitLab. 
• Vous devez versionner votre code sur GitHub ou GitLab.
• Votre repository doit être accessible.
• Un lien vers votre page web hébergée en ligne sur GitHub Pages ou GitLab Pages, pour présenter votre maquette. 
**Dépots projet:**
• Dossier nommé “P2_nom_prenom”
• Sous dossier  “P2_01_lienGithub”, “P2_02_lienpageweb"
**Attention "Le repo GitHub doit être nommé avec la convention suivante : Nomcomplet_#_Datedémarrage. Le # correspond au numéro du projet sur le parcours et la date doit être au format jjmmaaaa. Par exemple, FrancoisLenotre_3_05032020.**

**Réalisation:**
Date de démarrage: 11 mai 2021
Notes sur l'élaboration du projet:
Choix crétion de la maquette avec la méthode dite  MobileFirst (intégration du site en commençant par la résolution la plus faible)
- Charte graphique:
.Polices Raleway
.Couleur
.Extension image .svg pour le logo (compression orientée design forme vertoriel pas de perte de qualité à prévilégier pour le responsive) et png pour les images (meilleur qualité d'image et aucune perte)
.Récupérarion des documents (image et support pdf desktop et mobile)
- Elaboration:
Afin de faciliter le code, la maquette a été délimité en différentes parties via les balises sémantiques (balise physique (responsable du style:gras, italique, police) et des balises logiques qui en prend en charge les balises sémantiques) afin de structurer la page.
. indentation (retrait automatique) du code html et css afin de facilter la lecture 
. Ajout de commentaire
**Balises de structuration de zone de page**
- HTML
[PremierNiveau]
    (htlm head et body)
[Entête]
    (link, meta, title, style, script)
[SectionnanteDelimitationsZone]
    (header,*nav*, main, aside, article, footer)                       
[Génériques]
    (div, span)
[formulaire]
    (*label*, *input*)
[listes]
    (ul, li)
[StructurationTexte]
    (a, p, h, strong,img, figure, figcaption)
- Propriétés CSS
.Mise en forme du texte (font, text)
.Couleur et fond (color, background)
.Propriétés des boîtes (width, height, margin, padding, border)
.Positionnement et affichage (display, position, top, bottom, left ..)**avec Flexbox et Grid**
.Listes (list-style-type ..)
.Tableaux (border)
.Autres(cursor)

Le responsive est intégré dans le fichier css
La version du projet a été visionné en partie avec Chrome et Edge
Le code ne contient aucune erreur au validateur W3C HTML et CSS.

Dépôt: 
https://github.com/kcartoon/MobileReservia.git
Visionner:
https://kcartoon.github.io/MobileReservia/

