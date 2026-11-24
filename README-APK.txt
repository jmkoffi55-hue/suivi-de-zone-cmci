Génération de l’APK Android

Prérequis : Node.js LTS + Android Studio + Android SDK.
Depuis ce dossier :
  npm install
  npx cap add android
  npx cap sync android
  npx cap open android
Puis dans Android Studio : Build > Generate Signed Bundle / APK > APK.

Conserver la même clé de signature pour toutes les mises à jour.
