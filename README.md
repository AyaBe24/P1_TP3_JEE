# 🩺 TP J2EE - Partie 1 : Gestion des Patients avec Spring Boot

Ce projet fait partie d’un TP sur Java EE / Spring Boot. Il vise à créer une mini-application web de gestion des patients. L'application permet de **lister**, **rechercher** et **supprimer** des patients à partir d'une base de données **MySQL**, à l’aide de **Spring Boot**, **Spring Data JPA** et **Thymeleaf**.

---


---

## ✨ Fonctionnalités principales

- Affichage **paginé** de la liste des patients  
- **Recherche** de patients par mot-clé (nom)  
- **Suppression** de patients  
- **Interface responsive** avec Bootstrap  
- Connexion à une base de données **MySQL**

---

## 🧠 Contrôleur `PatientController.java`

Ce contrôleur web gère les routes suivantes :

- `@GetMapping("/index")` : affiche la liste des patients avec pagination et recherche  
- `@GetMapping("/delete")` : supprime un patient via son ID  

## 🧬 Schéma de la table patient

![Capture d’écran (26)](https://github.com/user-attachments/assets/1aef3e64-0fe0-4c30-bddf-b1da71db3de2)

