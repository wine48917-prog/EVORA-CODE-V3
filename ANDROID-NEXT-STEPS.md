# Android APK — next stage

This ZIP is the website source, not an APK.

Recommended path:
1. Put this site on a secure HTTPS host.
2. Initialize a Capacitor shell (`npm install @capacitor/core @capacitor/cli @capacitor/android`).
3. Run `npx cap init "EVORA CODE" "com.wine.evoracode"`.
4. Configure the web asset directory and copy the site into it.
5. Run `npx cap add android`, then `npx cap sync android`.
6. Open the Android project in Android Studio and build a debug APK.
7. Configure signing before distributing a release APK.
