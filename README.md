TP 9 : Authentification en mémoire avec Spring Security

Objectif

Développer une application Spring Boot permettant de gérer l'authentification des utilisateurs en mémoire avec Spring Security.

Technologies utilisées

Java 25

Spring Boot 3.5.7

Spring Security

Thymeleaf

Maven

Fonctionnalités

Page d'accueil publique.

Authentification personnalisée.

Gestion des rôles USER et ADMIN.

Protection des routes selon les rôles.

Encodage des mots de passe avec BCrypt.

Déconnexion.
<img width="1882" height="852" alt="image" src="https://github.com/user-attachments/assets/00ce8d14-c906-4519-998b-14264a197098" />

Comptes de test

Rôle

Username

Password

Utilisateur

user

1111

Administrateur

admin

1234

Lancement du projet


mvn spring-boot:run

Application accessible sur : http://localhost:8080/
