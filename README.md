# NAZATE PROD Android WebView

Application Android native (WebView) pour `https://nazateprod.blogspot.com`.

## Compilation APK via GitHub Actions
1. Crée un dépôt GitHub, par exemple `nazate-prod-android`.
2. Téléverse **tout le contenu** de ce projet (les dossiers `.github`, `app`, etc.).
3. Va dans l'onglet **Actions** et active les workflows si GitHub le demande.
4. Lance le workflow **Build APK** (Run workflow) ou fais un commit.
5. Une fois terminé, ouvre le run réussi et télécharge l'artifact `NAZATE-PROD-APK`.
6. Dézippe l'artifact et installe `app-debug.apk` sur Android. Autorise l'installation depuis cette source si Android le demande.

## Compilation locale
Avec Android Studio et Android SDK, ouvre ce dossier et lance Build > Build APK(s).

## Fonctions
- WebView plein écran avec URL intégrée.
- Barre de progression.
- Actualiser (menu).
- Bouton retour Android: navigation Web, puis demande de quitter.
- Liens tel/mail/WhatsApp ouverts via applications disponibles.
- Gestion du téléchargement via navigateur externe.
- Pas de permissions inutiles; Internet uniquement.
