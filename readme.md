# Prerequis
- Install docker 
- Add user to docker group 
- Reopen session
- In vscode, install docker & Remote development extensions

# Git 
## Le fichier de config remote container à été configurer comme ceci
- F1 new remote container config -> all container -> php) Ce que j'ai fait pour generer le fichier de config devcontainer.json
- ouvrir le container 

# Dev
- Apache est lancé par defaut et sert les fichier de /var/www/html 
- Un lien est créer entre /var/www/html et /workspaces/dev à la création du container grace à ... dans le fichier de config 
- Ouvrir localhost:8080/index.php dans navigateur

# 2 PostgresQL & PGadmin

VPS sur ovh : 
Processeur 1 vCore				
Mémoire 2 Go				
Stockage 40 Go SSD NVMe				
Bande passante publique 250 Mbit/s				
Image Debian 11

Nom de domaine: bugtotal.fr / IP: 

Sur VPS

- j'ai installé minikupe 
- minikube qui lance postgresql avec un persistent volume, pgAdmin et php et apache
- la config k8s est dans <deployment>

En Local: 

docker-compose: 

## Production environment

Pour postgresQL et et pgAdmin cd precedemment








