🚀 TP 8 : Architecture Backend Robuste avec Spring Boot
Ce projet consiste en la réalisation d'une API REST complète et structurée suivant les meilleures pratiques de développement (Architecture multicouche).


📋 Points clés du TP
L'objectif est de séparer la logique métier de la persistance des données en utilisant :
DTO (Data Transfer Object) : Pour ne pas exposer directement les entités JPA.
Records Java : Pour des DTO immuables et concis.
Mappers : Pour transformer les Entités en DTO et inversement.
Service Layer : Pour centraliser la logique métier.
Swagger (OpenAPI) : Pour documenter et tester l'API interactivement.


🛠️ Stack Technique
Backend : Spring Boot 3.x, Spring Data JPA, Validation.
Base de données : MySQL.
Outils : MapStruct (ou mappers manuels), Swagger UI, Maven.


📂 Architecture du Code
Le projet suit une structure organisée par responsabilité :
ma.example.demo.entities : Modèles de données (JPA).
ma.example.demo.dto : Objets de transfert de données (Records).
ma.example.demo.mappers : Classes de conversion Entity <-> DTO.
ma.example.demo.repositories : Accès à la base de données.
ma.example.demo.services : Logique métier de l'application.
ma.example.demo.web : Contrôleurs REST (API).
ma.example.demo.exceptions : Gestion globale des erreurs.
