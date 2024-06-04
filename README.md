# weather-app
1. First step, build the ionic project
ionic build
2. Install Capacitor 
https://capacitorjs.com/docs/getting-started
3. Adding Android Platform to the System
ionic capacitor add android
4. Synchronization Process
ionic capacitor sync or npx cap sync
5. Building the Android application
ionic capacitor build android

6. Creating Logo and Splash
Copy the asset folder to the project root folder and run the code below
npx capacitor-assets generate

7.Adding Geolocation Plugin
npm install @capacitor/geolocation then run step 4 again
