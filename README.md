<p align="center">
  <img src="docs/banniere-tv.png" alt="prizm." width="520">
</p>

<p align="center">
  <b>Tes films, séries et chaînes en direct, dans une vraie interface de TV.</b><br>
  Lecteur IPTV pour Android TV et projecteurs, par exr0.
</p>

<p align="center">
  <a href="https://github.com/alexrdg/prizm-releases/releases/latest/download/prizm.apk"><b>Télécharger la dernière version (APK)</b></a>
  ·
  <a href="https://prizm.exro.cool">Essayer la démo en ligne</a>
</p>

<p align="center">
  <img src="docs/accueil.jpg" alt="L’accueil de Prizm" width="900">
</p>

> Prizm est un **lecteur** : il ne fournit aucun contenu. Il affiche celui de ton abonnement IPTV (compte **Xtream Codes** : adresse du serveur, identifiant, mot de passe).

---

## Sommaire

- [Installation](#installation)
- [Premier lancement](#premier-lancement)
- [Fonctionnalités](#fonctionnalités)
  - [Accueil](#accueil)
  - [Films et séries](#films-et-séries)
  - [Fiches, casting et filmographies](#fiches-casting-et-filmographies)
  - [Live TV](#live-tv)
  - [Le lecteur](#le-lecteur)
  - [Recherche et Ma liste](#recherche-et-ma-liste)
- [Configuration (Réglages)](#configuration-réglages)
- [Effets légers ou complets](#effets-légers-ou-complets)
- [Télécommande : les touches](#télécommande--les-touches)
- [Mises à jour](#mises-à-jour)
- [Questions fréquentes](#questions-fréquentes)

---

## Installation

### Sur Android TV, un boîtier ou un projecteur (avec Downloader)

1. Installe l’app **Downloader** (by AFTVnews) depuis le Play Store de la TV.
2. Dans Downloader, saisis cette adresse :

   ```
   https://github.com/alexrdg/prizm-releases/releases/latest/download/prizm.apk
   ```

   Elle pointe toujours vers la dernière version (raccourci : `prizm.exro.cool/apk`).
3. Android demande d’autoriser Downloader à installer des applications : accepte, puis **Installer**.
4. Prizm apparaît dans la rangée des applications de la TV.

> **À retenir :** pour mettre à jour, installe **par-dessus** l’app existante. Ne désinstalle jamais Prizm avant : c’est la désinstallation qui efface tes comptes, réglages, listes et progression. Depuis la 0.1.3, la mise à jour se fait directement depuis l’app (voir [Mises à jour](#mises-à-jour)).

### Configuration requise

- Android 7 ou plus récent (Android TV, Google TV, boîtier ou projecteur Android, tablette, téléphone).
- Un abonnement IPTV compatible **Xtream Codes**.
- Facultatif : une clé **TMDB** gratuite pour les affiches HD, le casting et les filmographies.

---

## Premier lancement

<p align="center">
  <img src="docs/connexion.jpg" alt="Écran de connexion" width="760">
</p>

1. Saisis l’**adresse du serveur** (par exemple `http://exemple.com:8080`), ton **identifiant** et ton **mot de passe**, puis **Se connecter**.
   Pas encore d’abonnement ? **Essayer la démo** ouvre un catalogue d’exemple.
2. Prizm charge tout ton catalogue **une seule fois** : films, séries, catégories et chaînes. L’écran de préparation montre où il en est (« 13 099 · 32 % », puis « x / y » aux rechargements suivants).

<p align="center">
  <img src="docs/chargement.jpg" alt="Préparation de la bibliothèque" width="760">
</p>

Ensuite, tout est gardé sur l’appareil : l’app démarre vite et ne recharge rien toute seule. Quand ton fournisseur ajoute des titres : **Réglages → Données → Recharger les données**.

> Même avec des dizaines de milliers de films, le chargement se fait en flux sur la TV : seules les informations utiles sont gardées.

---

## Fonctionnalités

### Accueil

- **À la une** : un bandeau de cinq titres choisis pour toi (bien notés, récents, proches de tes goûts). La sélection est gardée pour la journée, et le bandeau ne change pas tant que tu parcours les rangées.
- **Continuer** : les films et épisodes commencés (à partir de 3 minutes de visionnage), pour reprendre là où tu t’es arrêté.
- **À regarder**, **Favoris**, les **personnes que tu suis**, les nouveautés et les catégories de ton fournisseur.
- Le **menu** s’ouvre en allant à gauche. Aller à droite (ou **Retour**) le referme et te remet exactement où tu étais.

<p align="center">
  <img src="docs/menu.jpg" alt="Menu ouvert" width="760">
</p>

### Films et séries

- Toutes les catégories de ton fournisseur, en pastilles.
- **Tris à trois états** : un clic dans le sens habituel (ajouts récents, mieux notés, années récentes, A → Z), un deuxième dans le sens inverse, un troisième pour revenir à l’ordre du fournisseur. Une flèche indique le sens.
- Avec une clé TMDB, **Mieux notés** tient compte du nombre de votes : un film noté par trois personnes ne passe pas devant un classique.

<p align="center">
  <img src="docs/films.jpg" alt="Films, triés par note" width="900">
</p>

### Fiches, casting et filmographies

- Résumé, durée, classification, pays, réalisation, scénario, bande-annonce.
- Un bouton principal qui sait où tu en es : **Lecture**, **Reprendre · 42 min restantes**, ou pour une série **Regarder S1 · É3** (l’épisode après celui que tu as fini).
- Saisons et épisodes, avec la progression de chacun.
- **Distribution**, et des rangées « Du même réalisateur », « Avec… » tirées de ton catalogue.

<p align="center">
  <img src="docs/fiche-film.jpg" alt="Fiche d’un film" width="440">
  <img src="docs/fiche-serie.jpg" alt="Fiche d’une série" width="440">
</p>

- Fiche **personne** : biographie, ce qui est disponible chez ton fournisseur, puis la **filmographie complète**. Un titre hors catalogue peut être ajouté à « À regarder » : il sera retrouvé s’il arrive chez ton fournisseur. **Suivre** une personne ajoute sa rangée sur l’accueil.

<p align="center">
  <img src="docs/personne.jpg" alt="Fiche d’une personne" width="760">
</p>

### Live TV

<p align="center">
  <img src="docs/live.jpg" alt="Live TV" width="900">
</p>

- **Ma TV** : choisis tes pays, Prizm en fait un bouquet numéroté comme à la maison (TF1 en 1, France 2 en 2…). Le reste est rangé dans **Autres chaînes**, jamais caché.
- **Doublons regroupés** : une même chaîne en SD, HD, FHD ou 4K devient une seule entrée ; tu choisis la qualité dans l’aperçu.
- **Aperçu vidéo** (en effets complets), programme en cours et à venir, **chaînes favorites**.

### Le lecteur

Films, épisodes et direct sont lus par le **lecteur natif de la TV** (Media3) : le décodage se fait sur la puce de la TV, y compris l’audio AC3/E-AC3 des fichiers mkv.

<p align="center">
  <img src="docs/lecteur.jpg" alt="Le lecteur" width="900">
</p>

- Des contrôles sobres, pensés pour un grand écran : reculer, lecture, avancer.
- **Audio et sous-titres** : un panneau sur le côté, avec la langue de chaque piste écrite en clair (« Français », « Anglais · 5.1 », « Désactivés »). Le bouton n’apparaît que s’il y a un choix à faire.

<p align="center">
  <img src="docs/lecteur-pistes.jpg" alt="Panneau Audio et sous-titres" width="900">
</p>

- **Épisode suivant**, façon Netflix : le bouton apparaît pendant le générique (OK pour lancer, Retour pour finir le générique), puis se remplit et enchaîne tout seul en fin d’épisode. Il est aussi dans les contrôles, pour passer à l’épisode suivant à tout moment.

<p align="center">
  <img src="docs/serie-controles.jpg" alt="Contrôles d’un épisode" width="440">
  <img src="docs/episode-suivant.jpg" alt="Épisode suivant en fin d’épisode" width="440">
</p>

- **Direct** : zapping sans quitter le lecteur, avec un bandeau qui montre le numéro, la chaîne et le **programme en cours**. La pastille **Qualité** (FHD, HD…) change de version. Si un flux tombe, Prizm bascule tout seul sur une autre version ; s’il prend du retard, il repart au direct.

<p align="center">
  <img src="docs/direct-zapping.jpg" alt="Bandeau de zapping" width="440">
  <img src="docs/direct-controles.jpg" alt="Contrôles du direct" width="440">
</p>

### Recherche et Ma liste

- **Recherche** dans tout le catalogue (titres, acteurs, réalisateurs, chaînes), sans tenir compte des accents.
- **Ma liste** regroupe **À regarder**, **Favoris** et les **Personnes** suivies.

<p align="center">
  <img src="docs/recherche.jpg" alt="Recherche" width="440">
  <img src="docs/ma-liste.jpg" alt="Ma liste" width="440">
</p>

### Aussi sur téléphone et tablette

La même app s’adapte : le menu devient une barre en bas, les pages passent en colonne.

<p align="center">
  <img src="docs/telephone-accueil.jpg" alt="Accueil sur téléphone" width="260">
  <img src="docs/telephone-live.jpg" alt="Live TV sur téléphone" width="260">
</p>

---

## Configuration (Réglages)

<p align="center">
  <img src="docs/reglages.jpg" alt="Réglages" width="900">
</p>

| Rubrique | Ce qu’on y règle |
|---|---|
| **Compte** | Changer de compte, ajouter un compte, se déconnecter, oublier un compte. Chaque compte a ses propres listes et sa propre progression. |
| **Apparence** | Thème (sombre, clair, comme le système), [effets légers ou complets](#effets-légers-ou-complets), outils de diagnostic. |
| **Lecture** | Langue audio, langue et affichage des sous-titres, taille des sous-titres (détails ci-dessous). |
| **Live TV** | Qualité lancée par défaut (la meilleure, Full HD, HD, SD), et « Recomposer Ma TV » pour changer de pays. |
| **Fiches et filmographies** | La clé TMDB (facultative). |
| **Données** | Recharger le catalogue, ou vider le cache. |
| **Mise à jour** | Installer la dernière version de Prizm. |
| **À propos** | Version et mentions. |

### Lecture : langues et sous-titres

<p align="center">
  <img src="docs/reglages-lecture.jpg" alt="Réglages de lecture" width="760">
</p>

- **Langue audio préférée** : une langue, ou **VO (langue originale)**. Avec la VO, Prizm prend la langue d’origine du film, connue grâce à TMDB. Sans clé TMDB, il prend la piste annoncée « VO », sinon la première qui n’est pas en français.
- **Langue des sous-titres**, puis **Afficher les sous-titres** :
  - **Si l’audio n’est pas en français** (recommandé) : un film anglais en VO a des sous-titres français, un film français n’en a pas ;
  - **Toujours** ou **Jamais**.
- **Taille des sous-titres** : petits, moyens ou grands.

> Les fournisseurs étiquettent souvent mal leurs pistes (code vide, ou langue écrite seulement dans le nom : « VFF », « English 5.1 », « VOSTFR »). Prizm lit le code **et** le nom de chaque piste pour choisir la bonne. Tu peux toujours changer pendant la lecture, dans **Audio et sous-titres**.

### Clé TMDB (facultative, gratuite)

Elle apporte les affiches et images HD, les photos du casting, les filmographies complètes, les titres similaires, le classement par note pondérée et la langue originale (pour la VO).

1. Crée un compte sur [themoviedb.org](https://www.themoviedb.org).
2. **Paramètres → API** : copie la clé (v3) ou le jeton d’accès (v4).
3. Dans Prizm : **Réglages → Fiches et filmographies**, colle la clé, puis **Enregistrer**.

### Live TV : composer « Ma TV »

1. Ouvre **Live TV** : la première fois, Prizm propose les pays trouvés chez ton fournisseur.
2. Choisis-en un ou plusieurs, puis **Créer ma TV**.
3. Pour changer plus tard : le bouton des drapeaux en haut de Live TV, ou **Réglages → Live TV → Recomposer Ma TV**.

### Données

<p align="center">
  <img src="docs/reglages-donnees.jpg" alt="Réglages, Données" width="760">
</p>

- **Recharger les données** : retélécharge films, séries et chaînes. Les fiches TMDB, longues à reconstituer, sont gardées.
- **Tout effacer (y compris TMDB)** : vide aussi le cache TMDB. Tes comptes, réglages, listes et progression ne sont **pas** touchés.

---

## Effets légers ou complets

<p align="center">
  <img src="docs/reglages-apparence.jpg" alt="Réglages, Apparence" width="760">
</p>

**Réglages → Apparence → Effets visuels.** C’est le réglage qui compte le plus pour la fluidité.

| | **Légers** (projecteur, boîtier TV) | **Complets** (verre flouté, ambiance animée) |
|---|---|---|
| Pour qui | Projecteurs, boîtiers et TV d’entrée de gamme | Appareils puissants, ordinateur |
| Fond | Dégradé fixe | Image du titre sélectionné, floue, qui suit ta navigation |
| Panneaux | Sombres et opaques | Verre dépoli translucide |
| Aperçu vidéo du Live | Coupé | Activé |
| Lecteur | Boutons opaques, aucune animation | Boutons translucides, léger grossissement au focus, fondu des contrôles |
| Par défaut | **Sur Android (TV, projecteur)** | Sur ordinateur |

<p align="center">
  <img src="docs/accueil-leger.jpg" alt="Accueil en effets légers" width="440">
  <img src="docs/accueil.jpg" alt="Accueil en effets complets" width="440">
  <br><sub>À gauche : effets légers. À droite : effets complets.</sub>
</p>

**Conseil :** commence en **Légers**. Si la navigation est parfaitement fluide, essaie **Complets**, et reviens en arrière au moindre ralentissement.

### Diagnostic de fluidité

Toujours dans **Apparence** :

- **Compteur d’images par seconde** : une pastille en haut à droite, par exemple « 58 i/s · pire 24 ms ». Plus « pire » est bas, plus c’est fluide : sous 50 ms, la navigation est agréable ; au-delà de 200 ms, elle rame.
- **Bandeau « À la une »** : le masquer pour comparer la fluidité de l’accueil.

---

## Télécommande : les touches

| Où | Touche | Effet |
|---|---|---|
| Partout | Flèches, OK | Naviguer, valider |
| Partout | Retour | Revenir en arrière (ferme d’abord un panneau ou le menu) |
| Contenu | Gauche, depuis le bord | Ouvrir le menu |
| Menu | Droite ou Retour | Refermer le menu et revenir où tu étais |
| Lecteur | OK, haut, bas | Afficher les contrôles |
| Lecteur | Gauche, droite (sur la barre) | Reculer, avancer |
| Direct | Haut, bas, CH+, CH− | Chaîne suivante, précédente |
| Direct | Chiffres | Aller au numéro de « Ma TV » |
| Direct | 0 ou « dernière chaîne » | Revenir à la chaîne précédente |
| Direct | Info, Guide | Afficher le bandeau de la chaîne |
| Fin d’épisode | OK | Lancer l’épisode suivant tout de suite |

---

## Mises à jour

Depuis la 0.1.3 : **Réglages → Mise à jour**. Un point rose sur l’icône Réglages signale une nouvelle version.

1. **Installer la 0.1.x** : Prizm télécharge la mise à jour, avec une barre de progression.
2. **La première fois seulement**, Android demande d’autoriser Prizm à installer des applications : active l’option, reviens dans Prizm, relance l’installation.
3. Android propose **Mettre à jour** : accepte. Prizm redémarre dans la nouvelle version, **avec toute ta configuration** (comptes, clé TMDB, langues, listes, favoris, progression).

Les notes de chaque version sont sur la page [Releases](https://github.com/alexrdg/prizm-releases/releases).

---

## Questions fréquentes

**Le premier chargement est long.**
C’est normal avec un gros catalogue, et il n’a lieu qu’une fois. Le compteur montre l’avancée ; les lancements suivants partent du catalogue gardé sur l’appareil.

**Un film ne se lance pas (« Lecture interrompue »).**
Choisis **Essayer l’autre lecteur**. Si rien ne passe, le fichier est probablement indisponible chez ton fournisseur.

**Une chaîne coupe ou rame.**
Prizm essaie déjà tout seul les autres versions de la chaîne. Tu peux aussi choisir une qualité plus basse avec la pastille **Qualité**, ou régler la qualité par défaut dans **Réglages → Live TV**.

**La navigation n’est pas fluide.**
Passe en **effets légers** (Réglages → Apparence) et mesure avec le compteur d’images.

**Je ne trouve pas un titre de la filmographie d’un acteur.**
S’il n’est pas chez ton fournisseur, il apparaît grisé dans « Filmographie complète ». OK l’ajoute à « À regarder », et Prizm le retrouvera s’il arrive au catalogue.

**Mes identifiants sont-ils envoyés quelque part ?**
Non. Ils restent sur l’appareil et ne servent qu’à joindre ton serveur IPTV.

---

<sub>Prizm par exr0. Ce produit utilise l’API TMDB sans être approuvé ni certifié par TMDB. Polices Geist et Quicksand sous licence SIL Open Font License.</sub>
