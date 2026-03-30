# TP N°02 POO - Programmation des boucles en Java

Ce dépôt contient le rapport interactif et le code source du deuxième Travail Pratique (TP) du module de Programmation Orientée Objet (POO) dispensé à l'USTHB (Faculté de Génie Electrique, Département d'Automatique, Spécialité M1 AII).

## 🚀 Fonctionnalités du Rapport

Ce projet n'est pas un simple document texte, c'est une page web interactive conçue avec le design **Google Pixel** (Material Design) :
* **Interface UI/UX moderne :** Typographie `Google Sans`, navigation latérale fluide, et mise en page responsive.
* **Terminal Interactif Intégré :** Un faux terminal codé en JavaScript (Machine à états) permet d'exécuter la logique algorithmique de l'exercice Java directement dans le navigateur, sans avoir besoin de compiler le code au préalable !
* **Explications Détaillées :** Analyse approfondie du choix des boucles et du fonctionnement des méthodes Java spécifiques (comme `.equals()` et `.equalsIgnoreCase()`).

## 📚 Contenu du TP

### 1. Théorie des Boucles
Rappels sur les trois structures itératives fondamentales en Java :
* La boucle `for` (pour un nombre d'itérations connu).
* La boucle `while` (avec gestion manuelle du compteur).
* La boucle `do...while` (qui garantit au moins une exécution).

### 2. Exercice Pratique : Système d'Authentification
Création d'un programme d'authentification robuste avec les règles suivantes :
* L'utilisateur a **3 tentatives** pour deviner le mot de passe (`AIIMI`).
* En cas d'échec (compte bloqué), une **alternative de secours** est proposée via une question secrète.
* Si la réponse à la question secrète est correcte (`Auto`), l'accès est débloqué. Sinon, l'accès est définitivement refusé.

## 🛠️ Comment utiliser ce projet ?

### Option 1 : Tester directement dans le navigateur (Recommandé)
Double-cliquez simplement sur le fichier `TP02_POO.html` pour l'ouvrir dans n'importe quel navigateur web moderne (Chrome, Edge, Firefox, Safari). 
Naviguez vers la dernière section et utilisez la fenêtre de terminal intégrée pour tester l'algorithme d'authentification en temps réel.

### Option 2 : Exécuter le code Java (Méthode classique)
Le code source Java complet et commenté (`Authentification.java`) est fourni dans le rapport. Pour l'exécuter sur votre machine :
1. Assurez-vous d'avoir le **JDK (Java Development Kit)** installé.
2. Copiez le code source et collez-le dans un fichier nommé `Authentification.java`.
3. Ouvrez un terminal système et compilez-le :
   ```bash
   javac Authentification.java
