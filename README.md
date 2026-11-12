# AK OneTap Panel — Android project

This is an Android app project with an offline WebView interface.

## Build an APK using only your Android phone (GitHub Actions)
1. Sign in or create an account at https://github.com.
2. In your browser, switch on **Desktop site** if the page is hard to use.
3. Create a new repository. Give it a name such as `AKOneTapPanel`.
4. Upload the contents of this ZIP into the repository (upload the files/folders inside the project, not the outer project folder).
5. Open the repository's **Actions** tab and select **Build AK OneTap APK**.
6. Tap **Run workflow** (or wait for the first push build), then open the completed run.
7. In **Artifacts**, download `AK-OneTap-Panel-APK`. Extract it to get `app-debug.apk`.
8. Open the APK on your phone and follow Android's install prompt. Only install APKs you built and trust.

## Included
- Android launcher activity and app label
- Red neon AK OneTap interface
- Sensitivity and DPI preference sliders
- Activate/deactivate UI state
- Offline WebView interface
- GitHub Actions workflow for cloud APK builds

## Important limitation
The sliders and button are in-app UI controls only. They do not modify game input, game aim, Android system DPI, or settings in other apps. The app does not request overlay or accessibility permissions.
