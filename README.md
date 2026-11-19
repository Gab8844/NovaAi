# NOVA - Application Android Native (Android 16 / HyperOS 3)

## Generer l'APK sans installer Android Studio (via GitHub Actions)

1. Creez un nouveau depot gratuit sur GitHub (meme depuis le navigateur de votre telephone).
2. Importez tous les fichiers contenus dans cette archive ZIP dans le depot (y compris le dossier `.github/workflows/build-apk.yml`).
3. Ouvrez l'onglet **Actions** du depot GitHub.
4. Lancez le workflow **Compiler NOVA APK (Android 16)** (ou attendez la fin de l'execution automatique).
5. Telechargez l'artifact **NOVA-Android16-APK** puis extrayez `app-debug.apk` et installez-le sur votre Xiaomi Redmi Note 15 4G.

## Compilation locale (optionnelle)

Si vous utilisez Android Studio :
1. Ouvrez le dossier `NOVA-Android16` dans Android Studio (JDK 17, Android SDK 36).
2. Cliquez sur **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
