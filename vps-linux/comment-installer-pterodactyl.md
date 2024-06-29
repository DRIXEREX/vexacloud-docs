# Comment installer Pterodactyl sur un VPS Linux ?

## Partie 1 : Installation du panel

Chez VexaCloud, nous possédons l'installation One-Click de Pterodactyl permettant d'installer Pterodactyl avec une node, PhpMyAdmin déjà prêt a l'emploi.

Ce pendant, vous pourriez tout de même effectuer manuellement l'installation depuis un OS.   

Nous allons effectuer l'installation avec un script automatique.

Pour commencer, effectuez ces commandes :

### Mettre à jour le système

`apt update -y && apt full-upgrade -y`

### Installation de quelques dépendances :

`apt install bash wget curl -y`

### Mise en place du script d'installation

`bash <(curl -s https://pterodactyl-installer.se)`

# En cours de redaction ..
