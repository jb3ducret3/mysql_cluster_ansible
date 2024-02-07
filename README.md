# mysql_cluster_ansible
projet_prof_yann
mise en place d'un cluster de serveur mariadb ( deux machines ) grace a anbsible

ETAPE0: on par du principe que les trois machines peuvent communiquer en root ==> port 22 voir key_gen,copy_id,permit_rootlogin yes 

etape1:
installation ansible sur le master.

etape2:
premier inventaire.ini
premier playbook --ping.yml

etape3:
update pour les deux serveurs distants
installation de mariadb sur les deux
installation de galera et de la conf 
- master
- worker

etape 4:
verification
commande mysql de verif cluster
creation de data sur un srv-sql
verfication de la copie sur l'autre
  

