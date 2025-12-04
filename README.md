# WebApp

**WebApp** est l'interface utilisateur du projet, développée avec **Spring Boot**. Elle sert de point d'entrée principal pour les utilisateurs finaux qui souhaitent interagir avec les fonctionnalités fournies par nos services.

## Description

Cette application web constitue la couche frontale de notre stack, permettant aux utilisateurs de visualiser, manipuler et exploiter les données gérées par le backend. Elle communique notamment avec l'API principale [`Api-Employee`](https://github.com/Berlin-40/Api-Employee) pour toutes les opérations métier liées à la gestion des employés.

## Fonctionnalités principales

- Interface utilisateur moderne et intuitive
- Connexion et authentification des utilisateurs
- Gestion et visualisation des employés
- Requêtes en temps réel vers les API backend
- Tableaux de bord, listes, formulaires

## Technologies utilisées

- **Spring Boot** (Java)
- Consommation d'API REST via HTTP/HTTPS
- HTML, (via modèles Spring)
- Thymeleaf

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Berlin-40/WebApp.git
   ```
2. Importez le projet dans votre IDE favori (**IntelliJ**, **Eclipse**, etc.).
3. Vérifiez/installez Java (JDK 17 ou version compatible recommandée) et que le back est lancé.
4. Lancez l'application :
   ```bash
   # Depuis la racine du projet
   ./mvnw spring-boot:run
   ```
   ou
   ```bash
   mvn spring-boot:run
   ```
5. L'application est disponible à [http://localhost:9001](http://localhost:9001).

## Configuration

L'application nécessite un accès fonctionnel à l'API backend [`Api-Employee`](https://github.com/Berlin-40/Api-Employee). Renseignez l'URL de l'API dans `application.properties` ou via les variables d'environnement selon votre configuration.

## Contribution

Les contributions sont les bienvenues ! Veuillez ouvrir une issue ou soumettre une Pull Request pour toute suggestion ou amélioration.

## Liens utiles

- [Api-Employee (backend)](https://github.com/Berlin-40/Api-Employee)
