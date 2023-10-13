## DevOps lab
## Installation des outils 
outil de virtualisation VMware Workstation 17
Créer une VM template (Ubuntu server 22.04 LTS) 
-> 2 GO RAM, 20 GO disque 
-> executer le script reset-template.sh (reset machine-id , update system)
créer VM devopslab (ubuntu server 22.04 LTS) (VM Ware work station)
-> minimun 4GO RAM, 40 GO disque, 4 coeurs .
-> Générer une pair de clé SSH 
-> Installer docker


apt install docker-compose -y 

-> Installer Python 3
-> Installer Ansible 
-> Installer Portainer (Docker Web Interface manager)

Utiliser ansible pour:
installer apache2 sur les 2 vm:
-> création dossier myproject
-> cd myproject
-> création des fichiers inventory.ini  install_apache.yml index.html et ansible.cfg
avec les commandes "ansible all -i inventory.ini -m ping" pour tester la connectivité entre devopslab et les VM hosts, "ansible-playbook -i inventory.ini  install_apache.yml -K" pour exécuter les tasks dans le fichier yaml.
-> modifier les pages index.html