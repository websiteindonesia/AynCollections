# AynCollection
AynCollection [webview]

Install Cordova
- <code>npm install</code>

Add platform Android SDK 29
- <code>cordova platform add android@9.0.0</code>

Build Android App Bundle
- <code>./gradlew bundle</code>

Jarsigner
- <code>jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore AynCollections.keystore app-release.aab ayn</code>

Zipalign
- <code>zipalign app-release.aab AynCollections.aab</code
