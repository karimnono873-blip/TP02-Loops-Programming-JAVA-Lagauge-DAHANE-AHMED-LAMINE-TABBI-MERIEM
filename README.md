# TP N°02 POO - Programmation des boucles en Java

Ce dépôt contient le rapport interactif avancé et les codes sources du deuxième Travail Pratique (TP) du module de Programmation Orientée Objet (POO) dispensé à l'USTHB (Faculté de Génie Electrique, Département d'Automatique, Spécialité M1 AII).

## ✨ Fonctionnalités du Projet (Version Avancée)

Ce projet se présente sous la forme d'une application web interactive complète (Single Page Application) adoptant le design **Google Pixel / Material Design** :
* **Interface UI/UX Premium :** Typographie `Google Sans` et `JetBrains Mono`, navigation latérale fluide, animations CSS, et mise en page 100% responsive.
* **Terminaux Interactifs (Machine à États) :** Le rapport intègre de faux terminaux codés en JavaScript Vanilla qui simulent parfaitement l'exécution des codes Java et de l'algorithme final, sans nécessiter de compilation externe.
* **Analyses Algorithmiques :** Chaque section de code est suivie d'une explication technique approfondie (gestion de la mémoire, risques de boucles infinies, méthodes POO comme `.equals()`).

## 📚 Contenu du Rapport

### 1. Théorie des Boucles (Rappels)
Analyse et exécution interactive des trois structures itératives fondamentales en Java :
* **La boucle `for` :** Idéale pour un nombre d'itérations connu.
* **La boucle `while` :** Structure basique nécessitant une gestion stricte du compteur.
* **La boucle `do...while` :** Structure inversée garantissant au minimum une exécution du bloc d'instructions.

### 2. Exercice d'Application : Système d'Authentification Sécurisé
Conception, code Java commenté et simulation d'un programme de sécurité respectant ces règles :
* L'utilisateur dispose de **3 tentatives maximum** pour saisir le mot de passe exact (`AIIMI`).
* En cas de blocage, une **procédure de récupération** est déclenchée (Question secrète).
* Si la réponse (`Auto`) est correcte, le compte est débloqué. Sinon, l'accès est définitivement refusé.

## 🚀 Comment utiliser ce projet ?

### Exécution Interactive (Navigateur)
1. Double-cliquez sur le fichier `TP02_POO.html`.
2. Le rapport s'ouvrira dans votre navigateur web par défaut (Chrome, Firefox, Safari, Edge).
3. Utilisez le menu latéral pour naviguer.
4. Dans les fenêtres noires (Terminaux), cliquez sur les boutons **Exécuter** ou tapez directement vos réponses au clavier pour tester l'algorithme d'authentification en temps réel.

### Exécution du Code Java (Machine)
Si vous souhaitez exécuter les codes de manière classique :
1. Installez le **JDK (Java Development Kit)**.
2. Copiez le code source souhaité depuis le rapport web et collez-le dans un fichier (ex: `AuthentificationSysteme.java`).
3. Compilez et exécutez via un terminal système :
   ```bash
   javac AuthentificationSysteme.java
   java AuthentificationSysteme
