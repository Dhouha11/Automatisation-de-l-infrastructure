## Installation VM à partir Vagrant
## Vangrant Cloud
https://app.vagrantup.com/eurolinux-vagrant/boxes/centos-stream-9

## Les étapes d'installation
ouvrir Git Bash
mkdir centos (création dossier sur /D/Vangrant-VMs/centos)
vagrant init eurolinux-vagrant/centos-stream-9
vagrant up (pour créer VM pour resume VM)
vagrant box list (pour consulter la liste des box installés)
vagrant status( pour check statut VM)
vagrant ssh (pour connerter à VM à partir de cmd)
exit pour terminer la connexion avec la VM
vagrant halt pour fermer la VM forcément.
vagrant suspend 
vagrant destroy pour détruire la VM.
vagrant reload (pour rebooter la VM)
vagrant global-status (--prune :pour supprimer les vms)