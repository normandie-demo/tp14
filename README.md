# TP numéro 14

## Objectif:

Exécuter un module nécessitant un pré-requis système

## Besoin:

- Créer un Playbook *db.yaml* tel que:
  - S’exécute sur les hosts *back*
  - Charge le contenu *mysql.yaml*
  - Exécute la création d’un utilisateur sur la base mariadb avec le module **community.mysql.mysql_user**
  - Exécuter le Playbook en mode verbose


> Le module mysql fait partie d’une collection de module Ansible qui n’est pas nécessairement installée par défaut. Pour l’installer lancer `ansible-galaxy collection install community.mysql`  
Voir le pré-requis système associé au module sur https://docs.ansible.com/ansible/latest/collections/community/mysql/mysql_user_module.html et installer ce paquet en pre_tasks

