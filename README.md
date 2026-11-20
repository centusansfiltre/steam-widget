# Centu Sans Filtre — Widget Steam

Les usages de l’IA déclarés par les développeurs, les informations utiles d’une fiche Steam et les vidéos de Centu : tout au même endroit.

À l’origine, ce widget était mon outil personnel pour préparer mes vidéos. Je le partage aujourd’hui sous la forme d’une **extension gratuite, encore en bêta**, que vous pouvez personnaliser selon vos besoins.

## Télécharger et installer

👉 **[Télécharger l’extension pour Chrome](./Centu-Steam-v0.5.0-Chrome.zip)**

Pour cette première version, l’installation se fait manuellement sur Chrome :

1. Téléchargez le fichier ZIP, puis **extrayez son contenu** dans un dossier que vous conserverez sur votre ordinateur.
2. Ouvrez `chrome://extensions` dans Chrome.
3. Activez le **Mode développeur**, en haut à droite.
4. Cliquez sur **Charger l’extension non empaquetée**.
5. Sélectionnez le dossier extrait qui contient le fichier `manifest.json`.
6. Ouvrez une fiche de jeu sur le [magasin Steam](https://store.steampowered.com/), ou actualisez une fiche déjà ouverte : le widget apparaît.

Gardez le dossier extrait à son emplacement : Chrome en a besoin pour faire fonctionner l’extension.

Les liens vers les versions sur les stores seront ajoutés ici lorsqu’elles seront disponibles.

## À quoi sert le widget ?

### Comprendre les usages de l’IA déclarés

Le widget indique si la fiche Steam contient une déclaration d’utilisation de l’intelligence artificielle. Il essaie ensuite d’identifier les usages décrits : graphismes, voix, musique, code, traduction, contenu promotionnel, génération pendant la partie…

La déclaration du développeur reste accessible dans le panneau pour vous permettre de lire le contexte et de vous faire votre propre opinion.

**Ce n’est pas un détecteur d’IA dans les fichiers du jeu.** L’extension se base sur les informations déclarées sur la fiche Steam. « Aucune IA déclarée » signifie qu’aucune déclaration n’a été trouvée sur cette fiche ; cela ne garantit pas l’absence d’IA. L’interprétation automatique peut aussi se tromper.

### Retrouver les informations pratiques

Le panneau rassemble plusieurs informations déjà présentes sur Steam, notamment les avis, la présence d’une démo, l’accès anticipé, les langues et la compatibilité Steam Deck.

Vous choisissez les informations à afficher, la présentation compacte ou détaillée et la position du widget.

### Accéder à mes vidéos sur le jeu

Lorsque vous affichez la page d'un jeu dont j'ai parlé sur YouTube, le widget propose des liens vers mes vidéos : le chapitre d’un Radar, un test complet ou les passages d’un live. Vous pouvez ainsi retrouver directement le contenu consacré au jeu que vous regardez.

## Fonctionnement et confidentialité

La lecture de la fiche Steam et l’interprétation de la déclaration d’IA se font **localement dans votre navigateur**, sans envoyer le texte à un service d’IA.

La fonction de liens vidéo récupère un catalogue JSON hébergé sur GitHub. Cette requête sert à télécharger la liste des liens ; elle ne transmet pas le contenu de la fiche Steam. Vous pouvez désactiver cette fonction dans la personnalisation du widget pour arrêter les requêtes liées au catalogue.

## Signaler un problème ou proposer une idée

Une déclaration mal interprétée ? Une information incorrecte ? Un souci d’affichage ?

Signalez-le dans les commentaires de la vidéo de présentation, en précisant **le lien de la fiche Steam concernée** et ce qui ne fonctionne pas. Une capture d’écran peut aussi aider.

Vos suggestions sont les bienvenues : c’est mon outil de travail, mais puisque je vous le partage, autant qu’il vous soit aussi utile qu’à moi !

## À propos de ce dépôt

Ce dépôt héberge :

- le fichier ZIP de l’extension à installer manuellement ;
- le fichier `videos.json`, qui associe les Steam ID des jeux aux liens vers mes vidéos et leurs chapitres.

Le catalogue sera enrichi au fil des vidéos. Vous n’avez pas besoin de télécharger le JSON vous-même pour utiliser le widget.

*Amusez-vous bien et à bientôt ! — Centu*
