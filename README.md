🔥 PompierNexDev V1.0

PompierNexDev est un plugin permettant aux joueurs d'accepter des missions de pompier dans le jeu. Il ajoute des points de départ pour les missions et des destinations aléatoires pour que les joueurs puissent participer à des missions d'extinction d'incendie, avec une récompense à la clé.
🔧 Fonctionnalités

    Points de Départ pour Missions: Crée un checkpoint pour commencer une mission de pompier à un emplacement prédéfini.
    Missions d'Extinction: Permet aux joueurs de choisir d'accepter une mission pour éteindre un incendie à une destination aléatoire.
    Annulation de Mission: Si un joueur a déjà une mission en cours, il peut annuler cette mission et en commencer une nouvelle.
    Récompense: Les joueurs reçoivent une récompense en argent à la fin de la mission, avec un montant aléatoire compris entre une valeur minimale et maximale définie.
    UI pour Missions: Affiche des panneaux d'interface utilisateur pour les interactions avec le joueur.

🔌 Installation

    Téléchargez le fichier PompierNexDev.dll.
    Placez le fichier dans le dossier plugins de votre serveur.
    Redémarrez le serveur pour appliquer les changements.

⚙️ Configuration

Le plugin utilise un fichier de configuration JSON situé dans le dossier PompierNexDev pour définir les paramètres suivants :

    GainMin: Montant minimum de la récompense pour la mission (par défaut 500.0).
    GainMax: Montant maximum de la récompense pour la mission (par défaut 1000.0).
    PompierPointX, PompierPointY, PompierPointZ: Coordonnées du point de départ pour les missions (par défaut 70.11105, 50, 1026.927).
    PompierDestinations: Liste des destinations où les missions peuvent être effectuées.
    CommonTimeInSeconds: Temps en secondes que le joueur doit passer à accomplir une mission (par défaut 10).

🛠️ Exemple d'Utilisation

    Début d'une Mission:
        Lorsqu'un joueur apparaît dans le jeu, un checkpoint pour commencer la mission est créé.
        Le joueur est invité à accepter ou annuler la mission via un panneau UI.

    Acceptation de Mission:
        Si accepté, un checkpoint est placé à une destination aléatoire, et le joueur reçoit une notification pour se rendre à cette destination.
        À l'arrivée et après un temps d'attente, le joueur reçoit une récompense en argent.

    Annulation de Mission:
        Si le joueur a une mission en cours et choisit d'en commencer une nouvelle, la mission actuelle est annulée, et le joueur reçoit une notification à ce sujet.

📜 Notes

    Assurez-vous que les coordonnées et les paramètres de la configuration sont adaptés à votre environnement de jeu pour éviter les conflits et assurer une bonne expérience de jeu.
    En cas de problème avec le plugin, vérifiez les logs du serveur pour des messages d'erreur éventuels.

Pour toute question ou support, n'hésitez pas à contacter le développeur du plugin.


le support/discord : https://discord.gg/GZbwrPNYrS
