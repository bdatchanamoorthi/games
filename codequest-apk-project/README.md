# CodeQuest APK project

## Easiest: build the APK in the cloud (no Android Studio)
1. Create a free account at github.com and make a new repository.
2. Upload ALL files from this folder (keep the .github folder).
3. Open the repository's Actions tab. The "Build APK" job starts by itself (about 5 minutes).
4. Open the finished run, download the CodeQuest-apk artifact, unzip it to get app-debug.apk.
5. Copy app-debug.apk to your Android phone and install it (allow "install unknown apps" when asked).

## Or build on your computer
Needs Node 18+, Java 17 and Android Studio.
    npm install
    npx cap add android
    npx cap sync android
    npx cap open android      (then Build > Build APK)

## Later
- Change the game: edit www/index.html, then build again.
- Play Store needs a signed release build and your own app icon.
