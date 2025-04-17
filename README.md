# AskMe AI - ChatBot App

AskMe AI est une application Flutter simple qui permet aux utilisateurs de discuter avec un chatbot propulsé par le modèle GPT-2 via l'API Hugging Face. L'application utilise une interface utilisateur moderne avec des messages différenciés pour l'utilisateur et le bot.

## Fonctionnalités

- Interface de chat intuitive
- Intégration de l'API Hugging Face GPT-2
- Envoi de messages utilisateur et réponses du bot
- Design sombre et moderne avec Google Fonts (Poppins)
- Scroll automatique vers le dernier message

## Prérequis

- Flutter SDK installé
- Un compte Hugging Face avec un token d'accès à l'API

## Installation

1. Clonez ce dépôt :

```bash
git clone https://github.com/votre-utilisateur/askme-ai-chatbot.git
cd askme-ai-chatbot
```

2. Installez les dépendances :

```bash
flutter pub get
```

3. Ajoutez votre clé API Hugging Face dans le fichier `lib/main.dart` :

```dart
final String apiKey = 'VOTRE_CLE_API_ICI';
```

## Utilisation

Exécutez l'application sur un simulateur ou un appareil :

```bash
flutter run
```

## Structure du Code

- **main.dart** : point d'entrée de l'application.
  - `ChatBotApp` : classe principale qui définit le `MaterialApp` et le thème.
  - `ChatPage` : page principale contenant l'interface de chat.
  - `Message` : modèle représentant un message utilisateur ou bot.
  - `_sendMessage()` : fonction qui gère l'envoi du message utilisateur et la récupération de la réponse du bot.
  - `_fetchBotReply()` : fonction qui appelle l'API Hugging Face pour obtenir la réponse du bot.

## Dépendances

- `http` : pour les requêtes HTTP
- `google_fonts` : pour utiliser la police Poppins

## Exemple d'écran

![screenshot](screenshot.png)

## Améliorations possibles

- Ajout du support pour plusieurs modèles Hugging Face
- Gestion des erreurs plus avancée
- Animation de chargement pendant la réponse du bot
- Sauvegarde de l'historique de chat

---

*Développé avec Flutter ❤ par votre MOUTAWASSIT ABDELALI.*
