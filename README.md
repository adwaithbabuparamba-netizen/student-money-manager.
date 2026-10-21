# Student Money Manager Pro - Android APK Cloud Build

## How to Build the APK on Your Android Phone:
1. Open Chrome on your phone and go to https://github.com/new
2. Create a new repository named "student-money-manager" (set to Private or Public).
3. On your repository page, switch Chrome to "Desktop site" (three dots menu -> Desktop site).
4. Tap "uploading an existing file" and upload the files from this folder:
   - .github/workflows/build-apk.yml
   - capacitor.config.json
   - package.json
   - index.html (and/or www/index.html)
5. Tap "Commit changes".
6. Tap the "Actions" tab at the top. The "Build Android APK" workflow will start running automatically.
7. In about 2-3 minutes, tap the completed workflow, scroll to "Artifacts", and tap "StudentMoneyManagerPro-v1.0-APK" (or check the Releases tab on your repo for the direct APK file).
8. Tap the downloaded APK to install on your phone.
9. Turn on Airplane mode to test 100% offline functionality!
