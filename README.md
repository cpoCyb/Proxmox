# Proxmox

## Version 9.1.1

Supprimer le message (popup) lors de la connexion sans abonnement

Fichier :
/usr/share/javascript/proxmox-widget-toolkit/**proxmoxlib.js**

--------------------------------------------------

Procédure :

1. Remplacer le fichier proxmoxlib.js par votre version modifiée

2. Redémarrer le service web Proxmox :

systemctl restart pveproxy

--------------------------------------------------

Pour annuler la modification :

apt-get install --reinstall proxmox-widget-toolkit
