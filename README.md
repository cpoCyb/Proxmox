██████████████████████████████████████████████████████████
█                         PROXMOX                        █
██████████████████████████████████████████████████████████


========================================
           TABLE DES MATIÈRES
========================================

[ Version 9.1.1 ]
  └─ Supprimer le message (popup) lors de la connexion sans abonnement


============================================================
                    VERSION 9.1.1
============================================================

Titre :
Supprimer le message (popup) lors de la connexion sans abonnement


🎯 Objectif
------------------------------------------------------------
Supprimer le message (popup) affiché lors de la connexion
à l’interface web Proxmox lorsqu’aucun abonnement n’est présent.


📁 Fichier concerné
------------------------------------------------------------
/usr/share/javascript/proxmox-widget-toolkit/proxmoxlib.js


🛠 Procédure
------------------------------------------------------------

1) Remplacer le fichier proxmoxlib.js par votre version modifiée.

2) Redémarrer le service web Proxmox :

   systemctl restart pveproxy


↩ Restauration (annuler la modification)
------------------------------------------------------------

Pour revenir au fichier d’origine :

   apt-get install --reinstall proxmox-widget-toolkit


