# Un script simple pour exporter les membres des groupes et des chaînes de télégrammes vers un fichier CSV et pour ajouter automatiquement des membres aux groupes de télégrammes.

> L'exportation et l'ajout de membres aux chaînes nécessitent que l'utilisateur à partir duquel le script est lancé soit un administrateur de chaîne.

### Abonnez vous à notre chaine YouTube pour plus d'information :
[Abonnez-vous pour en savoir plus sur les outils termux] (https://youtube.com/channel/UCIrXzZNGq_HHYdBdcrcVUkA)

### Lire plus de blogs sur Termux, l'insformatique et le monde du CyberWorld :
[sktechareyousafe.com](https://sktechareyousafe.com/)

### Installer les dépendances

### python3 et pip3 doivent être installés et disponibles dans votre PATH.

### installer le module telethon en exécutant la commande
pip3 installer le téléthon

### Configuration du télégramme

1. Pour l'exécuter, vous devez générer des informations d'identification API pour votre utilisateur Telegram, vous pouvez le faire [ici] (https://core.telegram.org/api/obtaining_api_id), et accéder à celles déjà créées [ici] (https  ://my.telegram.org/apps)
2. Remplacez vos identifiants dans le script python


api_id = 12345 # Votre identifiant API

api_hash = 'XXXXXXXXXXXXXXX' # Votre hachage API

phone = '+11234567890' # Votre numéro de téléphone avec l'indicatif du pays.


### Exportation des utilisateurs

Suivez simplement les instructions du script après l'avoir exécuté depuis votre shell.

### Ajout d'utilisateurs à des groupes

Les utilisateurs peuvent être ajoutés en utilisant :

- Nom d'utilisateur : Obtient temporairement banni avec moins de demandes.

- ID utilisateur : est temporairement banni avec plus de demandes.

> *Les interdictions temporaires durent jusqu'à une journée*

L'ajout d'utilisateurs par nom d'utilisateur nécessite un fichier CSV avec un nom d'utilisateur par ligne.
L'ajout d'utilisateurs par ID d'utilisateur attend un fichier CSV tel que : username,user_id,user_access_hash
