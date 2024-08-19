🔥 **PompierNexDev V1.0** 🔥

**PompierNexDev** est un plugin qui permet aux joueurs de s'engager dans des missions de pompier dans le jeu. Avec ce plugin, les joueurs peuvent accepter des missions d'extinction d'incendie, allant de la prise en charge d'une mission à une récompense à la clé !

### 🔧 **Fonctionnalités**

- **Points de Départ pour Missions** : Crée un checkpoint pour commencer une mission de pompier à un emplacement prédéfini.
- **Missions d'Extinction** : Permet aux joueurs d'accepter une mission pour éteindre un incendie à une destination aléatoire.
- **Annulation de Mission** : Permet aux joueurs de tout annuler et de commencer une nouvelle mission si nécessaire.
- **Récompense** : Offre une récompense en argent à la fin de chaque mission, avec un montant aléatoire entre une valeur minimale et maximale définie.
- **UI pour Missions** : Affiche des panneaux d'interface utilisateur pour faciliter les interactions avec le joueur.

### 🔌 **Installation**

1. Téléchargez le fichier `PompierNexDev.dll`.
2. Placez le fichier dans le dossier `plugins` de votre serveur.
3. Redémarrez le serveur pour appliquer les changements.

### ⚙️ **Configuration**

Le plugin utilise un fichier de configuration JSON situé dans le dossier `PompierNexDev`. Vous pouvez définir les paramètres suivants :

- `GainMin` : Montant minimum de la récompense pour la mission (par défaut 500.0).
- `GainMax` : Montant maximum de la récompense pour la mission (par défaut 1000.0).
- `PompierPointX, PompierPointY, PompierPointZ` : Coordonnées du point de départ pour les missions (par défaut 70.11105, 50, 1026.927).
- `PompierDestinations` : Liste des destinations où les missions peuvent être effectuées.
- `CommonTimeInSeconds` : Temps en secondes que le joueur doit passer à accomplir une mission (par défaut 10).

### 🛠️ **Exemple d'Utilisation**

- **Début d'une Mission** :
  Lorsqu'un joueur entre dans le jeu, un checkpoint pour commencer la mission est créé. Le joueur peut alors accepter ou annuler la mission via un panneau UI.

- **Acceptation de Mission** :
  Si la mission est acceptée, un checkpoint est placé à une destination aléatoire. Le joueur est notifié pour se rendre à cette destination. Après arrivée et un temps d'attente, le joueur reçoit une récompense en argent.

- **Annulation de Mission** :
  Si un joueur a une mission en cours et souhaite en commencer une nouvelle, la mission actuelle est annulée, et une notification est envoyée.

### 📜 **Notes**

- Assurez-vous que les coordonnées et les paramètres de configuration sont adaptés à votre environnement de jeu pour éviter les conflits et garantir une expérience de jeu optimale.
- En cas de problème avec le plugin, consultez les logs du serveur pour tout message d'erreur éventuel.

Pour toute question ou support, n'hésitez pas à contacter le développeur du plugin sur le [support/discord](https://discord.gg/GZbwrPNYrS).

### ⚠️ **Avertissement**

La décompilation, modification, redistribution, et toute autre forme d'utilisation non autorisée du plugin sont strictement interdites sans l'autorisation expresse du développeur. Toute utilisation non conforme pourra entraîner des mesures appropriées.
