# Christian Canvas Designer AI — Android build package

This project has been prepared as a Capacitor Android wrapper around the existing web app.

## Build requirements
- Node.js 20+
- npm
- Android Studio + Android SDK
- Java 17

## Build
1. Install dependencies:
   npm install
2. Build the web app:
   npm run build
3. Add Android platform:
   npx cap add android
4. Sync:
   npx cap sync android
5. Open in Android Studio:
   npx cap open android
6. In Android Studio, Build > Generate App Bundles or APKs > Generate APKs.

## Important
The AI functionality still requires the project's existing server/API configuration (including the xAI API key where the app expects it). Do not put a private API key directly in client-side code.
