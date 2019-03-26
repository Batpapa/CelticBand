# Manuel d'installation

## 1 - Créer un compte sur GitHub.com
1. S'inscrire sur GitHub au [lien suivant](https://github.com/join?source=header-home) en choisissant votre nom d'utilisateur (ex: **Toto**), une adresse mail (ex: **toto@gmail.com**) et un mot de passe (ex: **mdp_toto**).
2. Confirmer votre adresse mail en validant le courriel qui vous est automatiquement envoyé à **toto@gmail.com**.

Votre compte GitHub est désormais créé.

## 2 - Installer "GitHub Desktop for Windows"
1. Télécharger [GitHub Deskop for Windows](https://github.com/Batpapa/CelticBand/raw/master/Softwares/GitHubDesktopSetup.exe).
2. Installer le programme.
3. Créer un dossier quelque part sur votre ordinateur (sur le bureau par exemple) et le nommer **PlateformeCeltic**.
4. En installant "GitHub Desktop for Windows", celui-ci a dû créer un raccourci sur le bureau. Déplacer ce raccourci dans votre nouveau dossier **PlateformeCeltic**.
5. Lancer le logiciel et passer les étapes du tutoriel de lancement.
6. Taper `CTRL`+`,`, entrer vos identifiants **Toto** et **mdp_toto** sous l'onglet "Account", et valider.
7. Taper `CTRL`+`,`, entrer votre adresse mail **toto@gmail.com**  sous l'onglet "GIT", et valider. 
8. Taper `CTRL`+`SHIFT`+`O` (`O` comme Orange), aller sur l'onglet "URL", et taper dans le premier champ *Batpapa/CelticBand*, puis valider en cliquant sur "Clone". Le second champ représente le chemin où sera sauvegardé le répertoire du serveur, cliquer alors sur "Choose..." puis sélectionner votre dossier **PlateformeCeltic** nouvellement créé.
9. Cliquer finalement sur le troisième onglet "Fetch origin". (C'est ce bouton qui synchronise réellement votre dossier local avec celui du serveur).
10. M'envoyer vos identifiants **Toto** et **toto@gmail.com** afin que je vous octroye les droits d'édition. Après vous avoir donné les droits, vous devriez recevoir un mail d'invitation que vous devrez valider. 

Le répertoire est désormais synchronisé entre le serveur et votre ordinateur, celui-ci est alors présent sur votre ordinateur sous le dossier **PlateformeCeltic/CelticBand**.

## 3 - Installer VLC (OPTIONNEL)
1. Télécharger [VLC](https://github.com/Batpapa/CelticBand/raw/master/Softwares/VLC.exe).
2. Installer le programme.

L'objectif est d'uniformiser les formats de lecture, logiciel qui offre en bonus de multiples options très utiles pour l'apprentissage à l'oreille (loop, ralenti, filtrage...).

## 4 - Installer Guitar Pro 6 ou + (OPTIONNEL)
Acheter la dernière [version officielle](https://www.guitar-pro.com/fr/index.php?pg=accueil) ou me contacter pour connaître la marche à suivre.

Ce logiciel vous servira à lire les tablures/partitions au format *gpx*.

# Manuel d'utilisation

L'ensemble du réseau est désormais configuré. Nous allons maintenant voir comment s'utilise GitHub, c'est-à-dire la synchronisation entre le serveur et votre ordinateur.

## Fonctionnement général
La version du dossier *CelticBand* sur le serveur est la seule version qui compte: elle est visible par tous, tout le monde la partage.

L'avantage de cette plateforme par rapport aux autres est qu'ici tout changement est réversible. Par conséquent, il n'est ainsi pas grave d'effectuer des modifications car le serveur enregistre chacune d'entre elles.

Pour ajouter/modifier quoique ce soit sur le serveur, il est déjà nécessaire d'avoir sur son ordinateur une version du répertoire à-jour. Penser donc à souvent mettre à-jour la version présente sur votre ordinateur. Ensuite, vous pourrez envoyer vos propres modifications au serveur, qui intègrera dès lors vos nouveautés. Les autres membres n'auront plus qu'à mettre à-jour leur propre version afin de récupérer la vôtre.

## Instructions 

1. Mettre à-jour votre version du répertoire en cliquant sur l'onglet "Fetch Origin" (ou "Pull Origin" si le logiciel détecte qu'il y a eu une mise à-jour par quelqu'un d'autre sur le serveur).

2. Faire vos modifications (ajout, suppression et modification de fichiers et dossiers) directement dans le dossier **PlateformeCeltic/CelticBand**.

3. Engager (commit en anglais) votre modification: donner-lui un nom (impératif), une description, et cliquer sur "Commit to **master**".

![Image1](https://i.imgur.com/m6djmCQ.png)

4. Cliquer sur "**Push origin**" et attendre quelques secondes. (Attention: si vous n'avez pas reçu les droits d'édition, cette étape échouera avec un message d'erreur)

![Image2](https://i.imgur.com/SDaMMC3.png)

Et voilà, c'est fait, le serveur contient désormais votre modification.

*Disclaimer:
En cas de souci quelconque, n'oublier pas que Google est votre ami.*
