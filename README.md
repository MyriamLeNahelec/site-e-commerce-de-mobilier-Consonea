# <p align="center">Création d’un site e-commerce de mobiliers : Consonea </p>

## Objectifs du site

> “Lauréline Fleury a lancé son entreprise “Anciens meubles pour une nouvelle vie”, de vente de meubles de seconde main. Pour gagner en visibilité, elle a besoin d’avoir un site internet pour afficher ses produits. En plus, cela lui permettra de gérer son stock. Son besoin est donc le suivant : J’ai besoin d’avoir une page principale qui regroupera les meubles en vente en ce moment. Pour l’affichage de chaque meuble, je souhaite un encart dans lequel on pourra retrouver une photo, le type de meuble, le prix et un bouton pour l’acheter. Chaque encart sera cliquable pour permettre d’accéder au détail du produit. Sur cette nouvelle page, on retrouvera une série de photos du meuble et toutes les informations nécessaires, c’est-à-dire, le type, le prix, les dimensions, les couleurs, les matières et bien sûr un bouton pour acheter. Pour ce qui est de l’administration, je souhaite une page de connexion. Lorsque je suis connectée je dois pouvoir accéder à une page de gestion des produits. Sur celle-ci je veux pouvoir avoir la liste de mes meubles. Je souhaite pouvoir modifier les informations de mes produits en ayant un bouton depuis ma liste. Je dois pouvoir également les supprimer s’ils ont été vendus en magasin.”



## Organisation de travail

- Agile - Scrum
- Stand up meetings
- Journaux de bord


## 🧐 Fonctionnalités   
- Page d’accueil avec l’ensemble des meubles à vendre
- Page descriptive pour chaque meuble en vente
- Page connexion pour la création d’un compte utilisateur
- Espace pour l’administratrice du site
- Accès à la mise en vente de meuble

## 👩🏽‍🎨 Aspects ergonomique et graphisme

Choix libre. Proposition faite par l’équipe Front de la première semaine qui a ensuite été validé par l’équipe back.

### Charte graphique

La charte graphique (Logo, couleurs, police) reflétait l’univers de l’harmonie, du calme et l’écologie.

### Design et ergonomie

- Les éléments graphiques doivent respecter la charte graphique : couleurs, police permettant d’identifier la marque
- L’interface utilisateur doit être optimisée UX et être responsive.
- L’affichage du site doit être optimisé pour tous les navigateurs et toutes les devices
- Le site doit être aéré

## 🛠️ Tech Stack
- Front : React / Bootstrap
- Back : Node.js / Express / SQL / mySql
  
![image](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white 
)  ![image](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E )
![image](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) 
![image](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![image](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![image](https://img.shields.io/badge/Express%20js-000000?style=for-the-badge&logo=express&logoColor=white)
![image](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)



## 💪🏾 Mes missions pendant ce projet   

- Créer et connecter le serveur
- Créer et connecter la base de données  


## 🔌 Configuration

### Setup global

- npm install
- create .env :  
  DB_USER=root  
  DB_PASSWORD=  
  DB_DATABASE=consonea  
  DB_PORT=3306

### Setup front

- cd client
- npm install

### Setup back

- cd ../Backend
- npm install

### Setup base de données

- installer MySQL sur votre machine
- mysqladmin -u root password 'votresupermotdepassetrescomplique'
- mysql -u root -p Mot de passe root : ""
- CREATE DATABASE consonea;
- USE consonea;
- ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '';
- mysql -u root -p consonea < backend_bdd.sql

## Lancement du server

- npm start

## 🙇 Auteurices 

France Huon, Laure Saint-Antonin, Mahinthan Gugananthan, Mehdi Grimault, Myriam Le Nahelec, Nathan Pesneau, Paula Rondao, Quentin Kerzelec et Romane Boireau.
        
## Visuels de la plateforme

![Alt text](/screenshots/Consonea_0.png "accueil")
![Alt text](/screenshots/Consonea_1.png "accueil")
![Alt text](/screenshots/Consonea_2.png "accueil")
