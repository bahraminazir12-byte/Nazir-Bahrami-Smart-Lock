NAZIR BAHRAMI SMART LOCK — Android starter project

Build:
1. Upload this folder's contents to a new GitHub repository.
2. Open Actions and run "Build Nazir Bahrami Smart Lock APK" (or push to main).
3. Open the completed workflow run and download the artifact named:
   Nazir-Bahrami-Smart-Lock-APK
4. Extract the artifact and install app-debug.apk on your Samsung A32.
5. Allow camera permission when prompted, then scan your printed QR card.

Important:
- This is an in-app QR identity demo. It does NOT unlock Android's system lock screen,
  bypass PIN/pattern/password, or change device security settings.
- The QR credential is embedded in this demo app. Anyone who has a copy of the QR
  can pass this demo check, so do not treat it as high-security authentication.
- For a real secure deployment, use server-side enrollment, revocation, and a
  second factor such as Android biometric/device credential.
