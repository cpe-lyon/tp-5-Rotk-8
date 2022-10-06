# Compte rendu TP 5 :

## Exercice 1 :
  2 - Pour vérifier la création d'un nouveau disque on tape la commande "lsblk"
  3 - Pour creer de nouvelles partitions on utilise la commande "sudo fdisk /dev/sdb" ainsi on rentre dans le menu de création de partition sur notre nouveau disque.
  4 - On va formater la premiere partition en ext4 : "sudo mkfs -t ext4 /dev/sdb1"
  Puis la deuxieme en NTFS : "sudo mkfs -t ntfs /dev/sdb2"
  5 - C'est pas normal mais ça marche :
  
  
