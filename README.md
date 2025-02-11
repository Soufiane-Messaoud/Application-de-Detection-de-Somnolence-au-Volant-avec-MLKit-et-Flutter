Application de Détection de Somnolence au Volant avec ML Kit et Flutter
Description
Ce projet propose une application mobile développée avec Flutter et utilisant ML Kit pour détecter les signes de somnolence chez le conducteur. Grâce à la caméra frontale du smartphone, l'application analyse les comportements du conducteur (fermeture des paupières, bâillements, etc.) et émet une alerte sonore lorsque des signes de fatigue sont détectés. Ce système vise à améliorer la sécurité routière en aidant les conducteurs à rester vigilants.

Fonctionnalités
Détection en temps réel de la somnolence du conducteur via la caméra frontale.
Alerte sonore lorsque des signes de fatigue sont détectés (bâillement, yeux fermés).
Utilisation de ML Kit pour la détection des visages et des expressions.
Développement avec Flutter pour une application cross-platform.
Prérequis
Avant d'exécuter ce projet, assurez-vous d'avoir les éléments suivants installés sur votre machine :

Flutter SDK
Dart SDK
Android Studio / Visual Studio Code
Xcode (pour iOS)
Installation:
  Clonez ce dépôt sur votre machine :
bash
Copier
Modifier
git clone https://github.com/username/driver_sleep_detection.git
Accédez au répertoire du projet :
bash
Copier
Modifier
cd driver_sleep_detection
Installez les dépendances :
bash
Copier
Modifier
flutter pub get


Android : modifiez le fichier AndroidManifest.xml pour ajouter les permissions nécessaires et Aussi le dependance de Camera 
