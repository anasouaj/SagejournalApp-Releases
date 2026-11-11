# SagejournalApp — versions Windows

Application Windows d'importation, de révision et de saisie de journaux dans Sage.
Ce dépôt contient uniquement les fichiers de distribution. Le code source et les
données comptables des utilisateurs ne sont pas publiés ici.

## Installer

Ouvrir la [dernière version](https://github.com/anasouaj/SagejournalApp-Releases/releases/latest)
et télécharger le fichier **SagejournalApp-<version>-Setup.exe**. Exécuter ce fichier
et suivre les étapes. Windows 10/11 64 bits et une installation Sage compatible sont requis.
Python et Excel ne sont pas nécessaires sur le PC de l'utilisateur.

Une licence individuelle fournie par le propriétaire est requise pour la saisie dans Sage.
La validation de licence nécessite une connexion Internet.

## Mettre à jour

Dans l'application : **··· → Mises à jour → Vérifier en ligne**, puis **Installer et redémarrer**.
L'adresse du catalogue est intégrée à partir de la version 1.0.2.
Les versions antérieures peuvent recevoir un fichier `.sjupdate` ou le nouvel installateur.
Il ne faut pas désinstaller l'application avant une mise à jour.

Les journaux, les réglages et la licence restent dans Data. Une sauvegarde précède le
remplacement du programme. Une saisie Sage en cours doit être terminée avant l'installation.
Il n'y a pas de vérification périodique ni d'installation silencieuse imposée.

Le catalogue permanent est :

```text
https://github.com/anasouaj/SagejournalApp-Releases/releases/latest/download/latest.json
```

Les paquets `.sjupdate` sont signés par le propriétaire. Cette signature est distincte
d'une signature Authenticode Windows. Les fichiers Setup.exe et SageJournal.exe peuvent
donc provoquer un avertissement Windows.

Ne jamais ajouter à ce dépôt de journaux, de clés de licence, de dossiers Data ou
Publisher-Private, ni de fichiers du code source de l'application.
