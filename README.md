# MariaDB + Adminer

coloque dentro de src
docker-compose build
docker-compose up -d
docker exec -it hash bash
dentro do container: 
mysql -u root -p
pass: q1w2e3r4t5
create database NomeDaDatabase
exit
mysql -u root -p --database NomeDaDatabase < /files/dump.sql 
pass denovo 

