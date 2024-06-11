# Système de Stationnement Automatique de Voitures

## Description du Projet

Ce projet présente un Système de Stationnement Automatique de Voitures simulé dans Proteus, utilisant divers composants électroniques pour gérer efficacement le stationnement en temps réel. Le système permet de détecter la disponibilité des emplacements de parking, contrôler une barrière d'accès, et afficher des informations pertinentes sur un écran LCD.

## Composants du Système

### Arduino UNO
- **Rôle** : Cerveau central du système.
- **Fonctions** : Traite les données des capteurs, contrôle le servo-moteur et affiche des informations sur l'écran LCD.

### Module I2C
- **Rôle** : Facilite la communication entre l'écran LCD 20×4 et l'Arduino UNO.
- **Avantage** : Simplifie les connexions.

### Écran LCD 20×4
- **Usage** : Présente des informations sur les emplacements de stationnement (disponibilité des places et états du système).

### Mini Servo-Moteur
- **Fonction** : Régule l'ouverture et la fermeture d'une barrière ou porte.
- **Contrôle** : Basé sur les données des capteurs IR.

### Capteurs Infrarouges (IR)
- **Emplacements** : Six emplacements de stationnement, chacun équipé d'un capteur IR.
- **Fonction** : Détectent la présence des véhicules et surveillent l'occupation des emplacements.

## Instructions d'Installation et d'Utilisation

1. **Télécharger et Installer Proteus** : Si ce n'est pas déjà fait.
2. **Charger le Schéma** : Ouvrir le fichier de simulation du système de stationnement intelligent dans Proteus.
3. **Configurer le Matériel** : Assurez-vous que les composants sont correctement configurés et connectés selon le schéma.
4. **Téléverser le Code** : Utiliser l'IDE Arduino pour téléverser le code sur la carte Arduino UNO.
5. **Lancer la Simulation** : Démarrer la simulation dans Proteus et observer le fonctionnement du système.

